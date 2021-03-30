<template>
  <div class="wrapper">
    <parallax class="section page-header header-filter" :style="headerStyle">
      <div class="container">
        <div class="md-layout"></div>
      </div>
    </parallax>
    <div class="main main-raised">
      <div class="section text-center">
        <div class="container">
          <h2 class="title">Our Team</h2>
          <div class="team">
            <div class="md-layout">
              <!-- Keezog -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg2"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      Keezog
                      <br />
                      <small class="card-description text-muted">Founder</small>
                    </h4>

                    <md-card-content>
                      <p class="card-description">22 years old from Scotland! I stream a variety of different games. Mostly multiplayer games such Apex Legends. I love interacting and playing with my viewers, so if you want to play some games together, stop by when I\'m live and let\'s play!</p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="https://www.twitter.com/keezog"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
              <!-- SAC -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg5"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      SAC
                      <br />
                      <small class="card-description text-muted"
                        >Founder / Twitch Streamer</small
                      >
                    </h4>

                    <md-card-content>
                      <p class="card-description">I am NOT Scottish</p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="www.twitter.com/saadchowdhary"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-rose"
                      >
                        <i class="fab fa-instagram"></i>
                      </md-button>
                      <md-button
                        href="https://www.twitch.tv/sacnquack"
                        class="md-just-icon md-simple md-primary"
                      >
                        <i class="fab fa-twitch"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
              <!-- Teeoh -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg6"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      Teeoh
                      <br />
                      <small class="card-description text-muted"
                        >Founder / Lifestyle &amp; Content Creator
                      </small>
                    </h4>

                    <md-card-content>
                      <p class="card-description">Born in the concrete jungle of Toronto, ON. Ever since a young age with nothing but influences from different backgrounds, I picked up the camera &amp; fashion and never looked back</p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-rose"
                      >
                        <i class="fab fa-instagram "></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
            </div>
            <div class="md-layout">
              <!-- Dusklux -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg1"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      dusklux
                      <br />
                      <small class="card-description text-muted"
                        >Twitch Streamer / Artist</small
                      >
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        You can write here details about one of your team
                        members. You can give more details about what they do.
                        Feel free to add some <a href="#">links</a> for people
                        to be able to follow them outside the site.
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-rose"
                      >
                        <i class="fab fa-instagram"></i>
                      </md-button>
                      <md-button
                        href="https://www.twitch.tv/dusklux"
                        class="md-just-icon md-simple md-primary"
                      >
                        <i class="fab fa-twitch"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>

              <!-- Megan -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg3"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      MeganPi
                      <br />
                      <small class="card-description text-muted"
                        >Twitch Streamer</small
                      >
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        You can write here details about one of your team
                        members. You can give more details about what they do.
                        Feel free to add some <a href="#">links</a> for people
                        to be able to follow them outside the site.
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-rose"
                      >
                        <i class="fab fa-instagram"></i>
                      </md-button>
                      <md-button
                        href="https://www.twitch.tv/meganpi_"
                        class="md-just-icon md-simple md-primary"
                      >
                        <i class="fab fa-twitch"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
              <!-- QuiGonKin -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg4"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      QuiGonKin
                      <br />
                      <small class="card-description text-muted"
                        >Twitch Streamer</small
                      >
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        You can write here details about one of your team
                        members. You can give more details about what they do.
                        Feel free to add some <a href="#">links</a> for people
                        to be able to follow them outside the site.
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-rose"
                      >
                        <i class="fab fa-instagram"></i>
                      </md-button>
                      <md-button
                        href="https://www.twitch.tv/quigonkin"
                        class="md-just-icon md-simple md-primary"
                      >
                        <i class="fab fa-twitch"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
              </div>
              <div class="md-layout">
              <!-- The Narrator -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg7"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      The Narrator
                      <br />
                      <small class="card-description text-muted"
                        >Streamer / Voice Over Artist</small
                      >
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        You can write here details about one of your team
                        members. You can give more details about what they do.
                        Feel free to add some <a href="#">links</a> for people
                        to be able to follow them outside the site.
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-rose"
                      >
                        <i class="fab fa-instagram"></i>
                      </md-button>
                      <md-button
                        href="https://www.twitch.tv/iamthe_narrator"
                        class="md-just-icon md-simple md-primary"
                      >
                        <i class="fab fa-twitch"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
              <!-- The Llama -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg8"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      The Llama42
                      <br />
                      <small class="card-description text-muted"
                        >Twitch Streamer / Real Estate Mogul</small
                      >
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        You can write here details about one of your team
                        members. You can give more details about what they do.
                        Feel free to add some <a href="#">links</a> for people
                        to be able to follow them outside the site.
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="javascript:void(0)"
                        class="md-just-icon md-simple md-rose"
                      >
                        <i class="fab fa-instagram"></i>
                      </md-button>
                      <md-button
                        href="https://www.twitch.tv/iamthe_narrator"
                        class="md-just-icon md-simple md-primary"
                      >
                        <i class="fab fa-twitch"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
              <!-- Brendon -->
              <div class="md-layout-item md-medium-size-33 md-small-size-100">
                <div class="team-player">
                  <md-card class="md-card-plain">
                    <div class="md-layout-item md-size-50 mx-auto">
                      <img
                        :src="teamImg9"
                        alt="Thumbnail Image"
                        class="img-raised rounded-circle img-fluid"
                      />
                    </div>
                    <h4 class="card-title">
                      Brendon Alekseii 
                      <br />
                      <small class="card-description text-muted"
                        >Social Justice Storyteller</small
                      >
                    </h4>

                    <md-card-content>
                      <p class="card-description">
                        Brendon Alekseii is a writer, performer, director and activist from Trinidad &amp; Tobago. 
                        When he's not screaming at flamewheels in Hades or missing all his shots in Valorant, he's sharing his literary and Spoken Word passions with his followers,
                         or having thoughtful conversations about social justice issues on stream. 
                      </p>
                    </md-card-content>

                    <md-card-actions class="text-center">
                      <md-button
                        href="https://twitter.com/BrendonAlekseii"
                        class="md-just-icon md-simple md-info"
                      >
                        <i class="fab fa-twitter"></i>
                      </md-button>
                      <md-button
                        href="https://www.instagram.com/brendon.alekseii/"
                        class="md-just-icon md-simple md-primary"
                      >
                        <i class="fab fa-twitch"></i>
                      </md-button>
                    </md-card-actions>
                  </md-card>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- 
      <div class="section section-contacts">
        <div class="container">
          <div class="md-layout">
            <div class="md-layout-item md-size-66 md-xsmall-size-100 mx-auto">
              <h2 class="text-center title">
                Want to become part of the team?
              </h2>
              <h4 class="text-center description">
                Want to become a part of the team? Think you have what it takes
                to hang with us?
                <br />

                <br />
              </h4>
              <form class="contact-form" id="signup-form">
                <div class="md-layout">
                  <div class="md-layout-item md-size-50">
                    <md-field>
                      <label>Your Name</label>
                      <md-input v-model="name" type="text"></md-input>
                    </md-field>
                  </div>
                  <div class="md-layout-item md-size-50">
                    <md-field>
                      <label>Your Email</label>
                      <md-input v-model="email" type="email"></md-input>
                    </md-field>
                  </div>
                </div>
                <md-field maxlength="5">
                  <label>Your Message</label>
                  <md-textarea v-model="message"></md-textarea>
                </md-field>
                <div class="md-layout">
                  <div class="md-layout-item md-size-33 mx-auto text-center">
                    <md-button class="md-rose md-round">Send Message</md-button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
        -->
    </div>
  </div>
</template>

<script>
export default {
  bodyClass: "landing-page",
  props: {
    header: {
      type: String,
      default: require("@/assets/img/website.png")
    },
    teamImg1: {
      type: String,
      default: require("@/assets/img/faces/dusk.png")
    },
    teamImg2: {
      type: String,
      default: require("@/assets/img/faces/keez.png")
    },
    teamImg3: {
      type: String,
      default: require("@/assets/img/faces/meg.png")
    },
    teamImg4: {
      type: String,
      default: require("@/assets/img/faces/kin.png")
    },
    teamImg5: {
      type: String,
      default: require("@/assets/img/faces/sac.png")
    },
    teamImg6: {
      type: String,
      default: require("@/assets/img/faces/tee.png")
    },
    teamImg7: {
      type: String,
      default: require("@/assets/img/faces/narrator.png")
    },
    teamImg8: {
      type: String,
      default: require("@/assets/img/faces/llama.png")
    },
    teamImg9: {
      type: String,
      default: require("@/assets/img/faces/brendon.png")
    }
  },
  data() {
    return {
      name: null,
      email: null,
      message: null
    };
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
