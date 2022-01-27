<template>
  <div id="app">
    <nav class="navbar navbar-expand-sm bg-white fixed-top mb-0">
      <a class="navbar-brand" href="#">
        <img
          src="./assets/logo.png"
          width="30"
          height="30"
          alt="logo"
          class="align-bottom"
        />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarCollapse"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbarCollapse" class="collapse navbar-collapse">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a href="" class="nav-link"> About Us </a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link"> Pricing </a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link"> Feature </a>
          </li>
        </ul>
      </div>
    </nav>
    <div class="carousel">
      <div
        id="myCarousel"
        class="carousel slide"
        data-interval="6500"
        data-ride="carousel"
      >
        <ol class="carousel-indicators">
          <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
          <li data-target="#myCarousel" data-slide-to="1"></li>
          <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="active item carousel-fade">
            <a href="#"
              ><img
                src="https://speakzeasy.files.wordpress.com/2015/05/twa_blogpic_timisoara-4415.jpg"
            /></a>
          </div>
          <div class="item carousel-fade">
            <a href="#"
              ><img
                src="https://speakzeasy.files.wordpress.com/2015/05/twa_blogpic_timisoara-4415.jpg"
            /></a>
          </div>
          <div class="item carousel-fade">
            <a href="#"
              ><img
                src="https://speakzeasy.files.wordpress.com/2015/05/twa_blogpic_timisoara-4415.jpg"
            /></a>
          </div>
        </div>
        <a class="carousel-control left" href="#myCarousel" data-slide="prev">
          <span class="glyphicon glyphicon-chevron-left"></span>
        </a>
        <a class="carousel-control right" href="#myCarousel" data-slide="next">
          <span class="glyphicon glyphicon-chevron-right"></span>
        </a>
      </div>
    </div>
    <div
      class="pricing px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center border-top"
    >
      <h1 class="display-4">Pricing</h1>
    </div>
    <div class="container">
      <div class="card-deck mb-3 text-center">
        <div class="card mb-4 box-shadow">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Free</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">
              $0 <small class="text-muted">/ mo</small>
            </h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>10 users included</li>
              <li>2 GB of storage</li>
              <li>Email support</li>
              <li>Help center access</li>
            </ul>
            <button type="button" class="btn btn-lg btn-block btn-primary">
              Subscribe Now
            </button>
          </div>
        </div>
        <div class="card mb-4 box-shadow">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Pro</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">
              $15 <small class="text-muted">/ mo</small>
            </h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>20 users included</li>
              <li>10 GB of storage</li>
              <li>Priority email support</li>
              <li>Help center access</li>
            </ul>
            <button type="button" class="btn btn-lg btn-block btn-primary">
              Subscribe Now
            </button>
          </div>
        </div>
        <div class="card mb-4 box-shadow">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Enterprise</h4>
          </div>
          <div class="card-body">
            <h1 class="card-title pricing-card-title">
              $29 <small class="text-muted">/ mo</small>
            </h1>
            <ul class="list-unstyled mt-3 mb-4">
              <li>30 users included</li>
              <li>15 GB of storage</li>
              <li>Phone and email support</li>
              <li>Help center access</li>
            </ul>
            <button type="button" class="btn btn-lg btn-block btn-primary">
              Subscribe Now
            </button>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid text-center">
      <h1>What We Offer</h1>
      <br />
      <div class="row">
       <div class="col-sm">
          <span class="glyphicon glyphicon-certificate logo-small"></span>
          <h4>Certified</h4>
          <p>Lorem ipsum dolor sit</p>
        </div>
        <div class="col-sm">
          <span class="glyphicon glyphicon-wrench logo-small"></span>
          <h4>Hard Work</h4>
          <p>Lorem ipsum dolor sit </p>
        </div>
      </div>
      <br /><br />
      <div class="row">
        <div class="col-sm">
          <span class="glyphicon glyphicon-briefcase logo-small"></span>
          <h4>Job Done</h4>
          <p>Lorem ipsum dolor sit </p>
        </div>
        <div class="col-sm">
          <span class="glyphicon glyphicon-certificate logo-small"></span>
          <h4>Certified</h4>
          <p>Lorem ipsum dolor sit</p>
        </div>
      </div>
    </div>
    <div class="carousel">
      <h1 class="mt-5">Testimoni</h1>
      <hr />
      <div
        id="myCarousel"
        class="carousel slide"
        data-interval="6500"
        data-ride="carousel"
      >
        <ol class="carousel-indicators">
          <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
          <li data-target="#myCarousel" data-slide-to="1"></li>
          <li data-target="#myCarousel" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="row">
              <div class="col-lg-2"></div>
              <div class="col-lg-8">
                <p>
                  "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodo consequat. Duis aute
                  irure dolor in reprehenderit in voluptate velit esse cillum
                  dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                  cupidatat non proident, sunt in culpa qui officia deserunt
                  mollit anim id est laborum"
                </p>
                <hr />
                <h5>Irihanto Bunadiki</h5>
              </div>
              <div class="col-lg-2"></div>
            </div>
          </div>
          <div class="item carousel-fade">
            <div class="carousel-item active">
              <div class="row">
                <div class="col-lg-2"></div>
                <div class="col-lg-8">
                  <p>
                    "Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                    sed do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    Duis aute irure dolor in reprehenderit in voluptate velit
                    esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
                    occaecat cupidatat non proident, sunt in culpa qui officia
                    deserunt mollit anim id est laborum"
                  </p>
                  <hr />
                  <h5>Irihanto Bunadiki</h5>
                </div>
                <div class="col-lg-2"></div>
              </div>
            </div>
          </div>
          <div class="item carousel-fade">
            <div class="carousel-item active">
              <div class="row">
                <div class="col-lg-2"></div>
                <div class="col-lg-8">
                  <p>
                    "Lorem ipsum dolor sit amet, consectetur adipiscing elit,
                    sed do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    Duis aute irure dolor in reprehenderit in voluptate velit
                    esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
                    occaecat cupidatat non proident, sunt in culpa qui officia
                    deserunt mollit anim id est laborum"
                  </p>
                  <hr />
                  <h5>Irihanto Bunadiki</h5>
                </div>
                <div class="col-lg-2"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="pt-4 my-md-5 pt-md-5 border-top">
      <div class="row">
        <div class="col-12 col-md">
          <img
            class="mb-2"
            src="./assets/logo.png"
            alt="logo"
            width="24"
            height="24"
          />
          <small class="d-block mb-3 text-muted"
            >Copyright &copy; 2017-2018</small
          >
        </div>
        <div class="col-6 col-md">
          <h5>Features</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="#">Random feature</a></li>
            <li><a class="text-muted" href="#">Team feature</a></li>
          </ul>
        </div>
        <div class="col-6 col-md">
          <h5>About</h5>
          <ul class="list-unstyled text-small">
            <li><a class="text-muted" href="#">Privacy Policy</a></li>
            <li><a class="text-muted" href="#">Terms & Condition</a></li>
          </ul>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style lang="scss" scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
