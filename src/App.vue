<template>
  <div id="app">
    <div class="container">
      <section id="intro">
        <div class="row align-items-center">
          <div class="col-6">
            <div class="intro-heading">
              <h3 class="text-uppercase">Hello, IM Akash Preet</h3>
              <h1 class="display-4">Full Stack Developer</h1>
              <h5 class="text-muted text-capitalize">
                active learner, Speaker, Photographer
              </h5>
              <div class="intro-heading-btn mt-3">
                <button class="btn btn-primary m-2 text-uppercase">
                  Hire me
                </button>
                <button class="btn btn-outline-primary m-2 text-uppercase">
                  Get&nbsp;resume
                </button>
              </div>
            </div>
          </div>
          <div class="col-3">
            <img src="../src/assets/Me.png" alt="Me" height="700px;" />
          </div>
          <div class="col-3">
            <div class="intro-social">
              <div class="btn-group">
                <a
                  class="btn m-2"
                  href="https://stackoverflow.com/users/5678983/akash-preet"
                  target="_blank"
                >
                  <img
                    src="../src/assets/sm/stack-overflow.png"
                    alt="stack-overflow"
                /></a>
                <a
                  class="btn m-2"
                  href="https://www.linkedin.com/in/akashpreet/"
                  target="_blank"
                >
                  <img src="../src/assets/sm/linkedin.png" alt="linkedin"
                /></a>
                <a
                  class="btn m-2"
                  href="https://github.com/Akash-Preet"
                  target="_blank"
                >
                  <img src="../src/assets/sm/github.png" alt="github"
                /></a>
                <a
                  class="btn m-2"
                  href="https://twitter.com/akash_preets"
                  target="_blank"
                >
                  <img src="../src/assets/sm/twitter.png" alt="twitter"
                /></a>
                <a
                  class="btn m-2"
                  href="https://www.facebook.com/akashpreets"
                  target="_blank"
                >
                  <img src="../src/assets/sm/facebook.png" alt="facebook"
                /></a>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<style lang="scss">
#app {
  background: #f2f2f2;
}
.container {
  width: 90vw !important;
}
#intro {
  height: 75vh;
  position: relative;
  .text-muted {
    margin: 0px 5px;
  }
  .intro-heading-btn {
    .btn {
      width: 150px;
    }
  }
  .intro-social {
    img {
      width: 30px;
      height: 30px;
    }
    .btn-group {
      position: absolute;
      top: 25vh;
      left: 5vw;
    }
  }
}
@media screen and (min-width: 800px) and (max-width: 1450px) {
  #intro {
    .intro-social {
      .btn-group {
        position: absolute;
        left: -64.5vw;
      }
    }
  }
}
@media screen and (min-width: 100px) and (max-width: 799px) {
  #intro {
    .intro-social {
      .btn-group {
        display: inline-grid;
        left: -64.5vw;
      }
    }
  }
}
</style>
