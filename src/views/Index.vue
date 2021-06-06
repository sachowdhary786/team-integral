<template>
  <div class="wrapper" v-bind:data-background-color="backgroundColor">
    <parallax class="page-header header-filter">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="brand">
            <h1>Team Integral</h1>
            <h3>Neccesary to make a whole complete</h3>
          </div>
        </div>
      </div>
    </parallax>
    <div class="main main-raised">
      <div class="section text-center">
        <basic-elements></basic-elements>
      </div>
    </div>
  </div>
</template>

<script>
import BasicElements from "./components/BasicElementsSection";

export default {
  components: {
    BasicElements,
  },
  bodyClass: "index-page",
  props: {
    type: String,
    backgroundColor: String,
  },
};
</script>

<style lang="scss" scoped>
.md-card-actions.text-center {
  display: flex;
  justify-content: center !important;
}
.contact-form {
  margin-top: 30px;
}

.md-has-textarea + .md-layout {
  margin-top: 15px;
}
</style>
