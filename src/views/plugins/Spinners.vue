<template>
  <div class="animated fadeIn">
    <b-card no-body>
      <div slot="header">
        <i class="fa fa-spinner fa-spin mr-1"></i> Spinners - SpinKit
        <a href="https://coreui.io/pro/react/" class="badge badge-danger">CoreUI Pro Component</a>
        <div class="card-header-actions">
          <a href="https://github.com/tobiasahlin/SpinKit" rel="noopener noreferrer" target="_blank" class="card-header-action">
            <small class="text-muted">docs</small>
          </a>
        </div>
      </div>
      <b-card-body>
        <p>
          Simple loading spinners animated with CSS. SpinKit uses hardware accelerated (translate and opacity) CSS animations to create smooth and easily customizable animations.
        </p>
      </b-card-body>
    </b-card>
    <b-row>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Rotating plane
          </div>
          <b-card-body>
            <div class="sk-rotating-plane"></div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Double bounce
          </div>
          <b-card-body>
            <div class="sk-double-bounce">
              <div class="sk-child sk-double-bounce1"></div>
              <div class="sk-child sk-double-bounce2"></div>
            </div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Wave
          </div>
          <b-card-body>
            <div class="sk-wave">
              <div class="sk-rect sk-rect1"></div>&nbsp;<div class="sk-rect sk-rect2"></div>&nbsp;<div class="sk-rect sk-rect3"></div>&nbsp;<div class="sk-rect sk-rect4"></div>&nbsp;<div class="sk-rect sk-rect5"></div>&nbsp;
            </div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Wandering cubes
          </div>
          <b-card-body>
            <div class="sk-wandering-cubes">
              <div class="sk-cube sk-cube1"></div>
              <div class="sk-cube sk-cube2"></div>
            </div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Pulse
          </div>
          <b-card-body>
            <div class="sk-spinner sk-spinner-pulse"></div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Chasing dots
          </div>
          <b-card-body>
            <div class="sk-chasing-dots">
              <div class="sk-child sk-dot1"></div>
              <div class="sk-child sk-dot2"></div>
            </div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Three bounce
          </div>
          <b-card-body>
            <div class="sk-three-bounce">
              <div class="sk-child sk-bounce1"></div>
              <div class="sk-child sk-bounce2"></div>
              <div class="sk-child sk-bounce3"></div>
            </div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Circle
          </div>
          <b-card-body>
            <div class="sk-circle">
              <div class="sk-circle1 sk-child"></div>
              <div class="sk-circle2 sk-child"></div>
              <div class="sk-circle3 sk-child"></div>
              <div class="sk-circle4 sk-child"></div>
              <div class="sk-circle5 sk-child"></div>
              <div class="sk-circle6 sk-child"></div>
              <div class="sk-circle7 sk-child"></div>
              <div class="sk-circle8 sk-child"></div>
              <div class="sk-circle9 sk-child"></div>
              <div class="sk-circle10 sk-child"></div>
              <div class="sk-circle11 sk-child"></div>
              <div class="sk-circle12 sk-child"></div>
            </div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Cube grid
          </div>
          <b-card-body>
            <div class="sk-cube-grid">
              <div class="sk-cube sk-cube1"></div>
              <div class="sk-cube sk-cube2"></div>
              <div class="sk-cube sk-cube3"></div>
              <div class="sk-cube sk-cube4"></div>
              <div class="sk-cube sk-cube5"></div>
              <div class="sk-cube sk-cube6"></div>
              <div class="sk-cube sk-cube7"></div>
              <div class="sk-cube sk-cube8"></div>
              <div class="sk-cube sk-cube9"></div>
            </div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Fading circle
          </div>
          <b-card-body>
            <div class="sk-fading-circle">
              <div class="sk-circle1 sk-circle"></div>
              <div class="sk-circle2 sk-circle"></div>
              <div class="sk-circle3 sk-circle"></div>
              <div class="sk-circle4 sk-circle"></div>
              <div class="sk-circle5 sk-circle"></div>
              <div class="sk-circle6 sk-circle"></div>
              <div class="sk-circle7 sk-circle"></div>
              <div class="sk-circle8 sk-circle"></div>
              <div class="sk-circle9 sk-circle"></div>
              <div class="sk-circle10 sk-circle"></div>
              <div class="sk-circle11 sk-circle"></div>
              <div class="sk-circle12 sk-circle"></div>
            </div>
          </b-card-body>
        </b-card >
      </b-col>
      <b-col xl="3" lg="4" md="6">
        <b-card no-body>
          <div slot="header">
            <i class="fa fa-spinner"></i> Folding Cube
          </div>
          <b-card-body>
            <div class="sk-folding-cube">
              <div class="sk-cube1 sk-cube"></div>
              <div class="sk-cube2 sk-cube"></div>
              <div class="sk-cube4 sk-cube"></div>
              <div class="sk-cube3 sk-cube"></div>
            </div>
          </b-card-body>
        </b-card >
      </b-col>
    </b-row>
  </div>
</template>

<script>
  export default {
    name: 'spinners',
  }
</script>

<style src="spinkit/scss/spinkit.scss" lang="scss" />

<style scoped>
  .sk-fading-circle .sk-circle {
    margin: 0 auto;
  }
  .sk-three-bounce {
    height: 40px;
  }
</style>
