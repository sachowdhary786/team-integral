<template>
  <div id="material-kit">
    <div :class="{ 'nav-open': NavbarStore.showNavbar }">

      <router-link v-if="authenticated" to="/login" v-on:click.native="logout()" replace>Logout</router-link>

      <router-view @authenticated="setAuthenticated" name="header" />
        <router-view />
        <div></div>
      <router-view name="footer" />
    </div>
  </div>
</template>

<script>
export default ({
  name: 'App', 
  data() {
    return {
      authenitcated: false, 
      mockAccount: {
        username: "integral",
        password: "Kx]:(!3Sj2T3&yt"
      }
    }
  }, 
  mounted(){
    if(!this.authenitcated){
      this.$router.replace({name: "login"});
    }
  },
  methods: {
    setAuthenticated(status){
      this.authenitcated = status;
    },
    logout() {
      this.authenitcated = false;
    }
  } 
})
</script>
