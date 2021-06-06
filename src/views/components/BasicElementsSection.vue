<template>
  <div class="container">
    <h2 class="title">Our Team</h2>
    <div class="team">
      <div class="md-layout">
        <!-- Keezog -->
        <div class="md-layout-item md-medium-size-50 md-small-size-100">
          <div class="team-player" id="keezog">
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
                <p class="card-description">
                  22 years old from Scotland! I stream a variety of different
                  games. Mostly multiplayer games such Apex Legends. I love
                  interacting and playing with my viewers, so if you want to
                  play some games together, stop by when I'm live and let's
                  play!
                </p>
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
        <div class="md-layout-item md-medium-size-50 md-small-size-100">
          <div class="team-player" id="sac">
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
                <small class="card-description text-muted">Founder</small>
              </h4>

              <md-card-content>
                <p class="card-description">
                  Variety streamer who ADORES management games!
                  <br />
                  Come and see me struggle with games like Endzone, Football
                  Manager, Planet Zoo. <br />I also have an Instagram and
                  Twitter?
                </p>
              </md-card-content>

              <md-card-actions class="text-center">
                <md-button
                  href="https://www.twitter.com/saadchowdhary"
                  class="md-just-icon md-simple md-info"
                >
                  <i class="fab fa-twitter"></i>
                </md-button>
                <md-button
                  href="https://www.instagram.com/sahmedc786/"
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
      </div>
      <div class="md-layout">
        <!-- Dusklux -->
        <div class="md-layout-item md-medium-size-33 md-small-size-100">
          <div class="team-player" id="dusk">
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
                  My name's Ashe (she/her or they/them) and I'm a casual
                  Canadian streamer. Come watch me play some random games that I
                  enjoy and see how I can take some simple tasks and make them
                  extremely difficult!
                </p>
              </md-card-content>

              <md-card-actions class="text-center">
                <md-button
                  href="https://twitter.com/dusklux"
                  class="md-just-icon md-simple md-info"
                >
                  <i class="fab fa-twitter"></i>
                </md-button>
                <md-button
                  href="https://www.instagram.com/dusk.lux/"
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
          <div class="team-player" id="megan">
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
                  Hi! I'm a 21 year old Physics student from the UK. I'm a
                  variety streamer and I play games like minecraft, GTA,
                  warzone, and stardew valley. Come hang out!
                </p>
              </md-card-content>

              <md-card-actions class="text-center">
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
        <!-- FireFly -->
        <div class="md-layout-item md-medium-size-33 md-small-size-100">
          <div class="team-player" id="firefly">
            <md-card class="md-card-plain">
              <div class="md-layout-item md-size-50 mx-auto">
                <img
                  :src="teamImg6"
                  alt="Thumbnail Image"
                  class="img-raised rounded-circle img-fluid"
                />
              </div>
              <h4 class="card-title">
                Firefly
                <br />
                <small class="card-description text-muted"
                  >Twitch Streamer</small
                >
              </h4>

              <md-card-content>
                <p class="card-description">
                  UK based makeup artist and lover of all things macabre. I
                  mainly stream dead by daylight/ survival games. Send cat pics.
                </p>
              </md-card-content>

              <md-card-actions class="text-center">
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
          <div class="team-player" id="narr">
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
                  Do you like movies, comics, gaming, &amp; obscure pop culture
                  references? If so, then you've come to the right place! Hi!
                  I'm the Narrator; a voiceover artist and variety streamer from
                  Ontario, Canada. I like sunsets, long walks on the beach,
                  cinema, &amp; Star Wars. Let's be friends?
                </p>
              </md-card-content>

              <md-card-actions class="text-center">
                <md-button
                  href="https://twitter.com/iamthe_narrator"
                  class="md-just-icon md-simple md-info"
                >
                  <i class="fab fa-twitter"></i>
                </md-button>
                <md-button
                  href="https://www.instagram.com/iamthe_narrator/"
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
                <md-button
                  href="https://www.youtube.com/channel/UCnAw98QjJhAiqWurU0V6EwA"
                  class="md-just-icon md-simple md-danger"
                >
                  <i class="fab fa-youtube"></i>
                </md-button>
              </md-card-actions>
            </md-card>
          </div>
        </div>
        <!-- The Llama -->
        <div class="md-layout-item md-medium-size-33 md-small-size-100">
          <div class="team-player" id="llama">
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
                  Yo yo yo! It's your man The Llama! I'm a 31 year old life long
                  gamer. Man of many trades. Real estate agent, house flipper,
                  COD player, dart thrower and beer drinker. Love making people
                  laugh and smile! I've lived a lot of life and love to share my
                  experiences and stories!
                </p>
              </md-card-content>

              <md-card-actions class="text-center">
                <md-button
                  href="https://twitter.com/TheLlama42"
                  class="md-just-icon md-simple md-info"
                >
                  <i class="fab fa-twitter"></i>
                </md-button>
                <md-button
                  href="https://www.instagram.com/thellama42/"
                  class="md-just-icon md-simple md-rose"
                >
                  <i class="fab fa-instagram"></i>
                </md-button>
                <md-button
                  href="https://www.twitch.tv/thellama4288/"
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
          <div class="team-player" id="brendon">
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
                  Brendon Alekseii is a writer, performer, director and activist
                  from Trinidad &amp; Tobago. When he's not screaming at
                  flamewheels in Hades or missing all his shots in Valorant,
                  he's sharing his literary and Spoken Word passions with his
                  followers, or having thoughtful conversations about social
                  justice issues on stream.
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
                  class="md-just-icon md-simple md-rose"
                >
                  <i class="fab fa-instagram"></i>
                </md-button>
                <md-button
                  href="https://www.twitch.tv/brendonalekseii"
                  class="md-just-icon md-simple md-primary"
                >
                  <i class="fab fa-twitch"></i>
                </md-button>
              </md-card-actions>
            </md-card>
          </div>
        </div>
        <!-- Tythis -->
        <div class="md-layout-item md-medium-size-33 md-small-size-100">
          <div class="team-player" id="tythis">
            <md-card class="md-card-plain">
              <div class="md-layout-item md-size-50 mx-auto">
                <img
                  :src="teamImg4"
                  alt="Thumbnail Image"
                  class="img-raised rounded-circle img-fluid"
                />
              </div>
              <h4 class="card-title">
                Tythis
                <br />
                <small class="card-description text-muted"
                  >Twitch Streamer</small
                >
              </h4>

              <md-card-content>
                <p class="card-description">
                  Hello! I am Tythis, a chaotic variety streamer from The North
                  with a DnD addiction. Come hangout and nerd out with us!
                </p>
              </md-card-content>

              <md-card-actions class="text-center">
                <md-button
                  href="https://www.twitch.tv/tythis"
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
</template>

<script>
export default {
  props: {
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
      default: require("@/assets/img/faces/tythis.jpeg")
    },
    teamImg5: {
      type: String,
      default: require("@/assets/img/faces/sac.jpg")
    },
    teamImg6: {
      type: String,
      default: require("@/assets/img/faces/firefly.png")
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
  }
};
</script>

<style lang="scss" scoped>
.md-card-actions.text-center {
  display: flex;
  justify-content: center !important;
}
</style>
