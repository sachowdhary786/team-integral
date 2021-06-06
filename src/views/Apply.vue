<template>
  <div class="wrapper">
    <div class="section page-header header-filter" :style="headerStyle">
      <div class="container">
        <div class="md-layout">
          <div
            class="md-layout-item md-size-33 md-small-size-66 md-xsmall-size-100 md-medium-size-40 mx-auto"
          >
            <form id="application" @submit-prevent="processForm">
              <login-card header-color="green">
                <h4 slot="title" class="card-title">
                  Want to be a part of the team?
                </h4>
                <md-field class="md-form-group" slot="inputs">
                  <md-icon>face</md-icon>
                  <label>Twitch Channel...</label>
                  <md-input v-model="channel" type="text"></md-input>
                </md-field>
                <md-field class="md-form-group" slot="inputs">
                  <md-icon>email</md-icon>
                  <label>Email...</label>
                  <md-input v-model="email" type="email"></md-input>
                </md-field>
                <md-field class="md-form-group" slot="inputs">
                  <md-icon>face</md-icon>
                  <label>A little about you...</label>
                  <md-input v-model="about" type="text"></md-input>
                </md-field>
                <md-field class="md-form-group" slot="inputs">
                  <md-icon>face</md-icon>
                  <label>What can we do for you...</label>
                  <md-input v-model="what" type="textarea" textarea></md-input>
                </md-field>
                <md-button
                  slot="footer"
                  class="md-simple md-success md-lg"
                  v-on:click="processForm"
                >
                  Get Started
                </md-button>
              </login-card>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { LoginCard } from "@/components";

var emailRegExp = /^[a-zA-Z0-9.!#$%&'*+\/=?^_`{|}~-]+@[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?(?:\.[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?)*$/;

export default {
  data() {
    return {
      channel: "",
      email: "",
      about: "",
      what: ""
    };
  },
  methods: {
    processForm: function() {
      this.submitted = true;
    },
    validate: function() {
      if (type === "email") {
        this.email.valid = this.isEmail(value) ? true : false;
      }
    },
    isEmail: function(value) {
      return emailRegExp.test(value);
    },
    checkAll: function(event) {
      this.selection.features = event.target.checked ? this.features : [];
    }
  },
  watch: {
    "email.value": function(value) {
      this.validate("email", value);
    }
  },
  components: {
    LoginCard
  },
  bodyClass: "login-page",

  props: {
    header: {
      type: String,
      default: require("@/assets/img/profile_city.jpg")
    }
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.header})`
      };
    }
  }
};
</script>

<style lang="css"></style>
