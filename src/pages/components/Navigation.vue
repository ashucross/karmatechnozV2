<template>
  <div class="section section-navbars">
    <!-- <div class="container" id="menu-dropdown">
      <div class="row">
        <div class="col-md-6">
          <h4>Menu</h4>
          <navbar type="primary">
            <a class="navbar-brand" href="#">Menu</a>
            <button
              class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#example-navbar"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-bar bar1"></span>
              <span class="navbar-toggler-bar bar2"></span>
              <span class="navbar-toggler-bar bar3"></span>
            </button>

            <template slot="navbar-menu">
              <li class="nav-item active">
                <a class="nav-link" href="#">
                  <p>Link</p>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <p>Link</p>
                </a>
              </li>
              <drop-down class="nav-item" title="Dropdown">
                <a class="dropdown-item" href="#">Action</a>
                <a class="dropdown-item" href="#">Another action</a>
                <a class="dropdown-item" href="#">Something else here</a>
              </drop-down>
            </template>
          </navbar>
        </div>
        <div class="col-md-6">
          <h4>Menu with Icons</h4>
          <navbar type="info" menu-classes="ml-auto">
            <a class="navbar-brand" href="#">Icons</a>
            <button
              class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#example-navbar-icons"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-bar bar1"></span>
              <span class="navbar-toggler-bar bar2"></span>
              <span class="navbar-toggler-bar bar3"></span>
            </button>
            <template slot="navbar-menu">
              <li class="nav-item">
                <a class="nav-link" href="#pablo"
                  ><i class="now-ui-icons ui-1_send" aria-hidden="true"></i
                ></a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#pablo"
                  ><i
                    class="now-ui-icons users_single-02"
                    aria-hidden="true"
                  ></i
                ></a>
              </li>
              <drop-down
                class="nav-item dropdown"
                icon="now-ui-icons ui-1_settings-gear-63"
              >
                <a class="dropdown-header">Dropdown header</a>
                <a class="dropdown-item" href="#">Action</a>
                <a class="dropdown-item" href="#">Another action</a>
                <a class="dropdown-item" href="#">Something else here</a>
                <div class="divider"></div>
                <a class="dropdown-item" href="#">Separated link</a>
                <div class="divider"></div>
                <a class="dropdown-item" href="#">One more separated link</a>
              </drop-down>
            </template>
          </navbar>
        </div>
      </div>
      <h4>Navigation</h4>
    </div> -->
    
      <navbar type="primary" menu-classes="ml-auto">
        <!-- Navbar Transparent --> 
          <div class="navbar-translate">
            <a class="navbar-brand" href="#pablo">Catch service provider</a>
            <button
              class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#example-navbar-transparent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-bar bar1"></span>
              <span class="navbar-toggler-bar bar2"></span>
              <span class="navbar-toggler-bar bar3"></span>
            </button>
          </div>
          <template slot="navbar-menu">
            <li class="nav-item">
              <a class="nav-link" href="https://www.facebook.com/people/Karma-Technoz/pfbid02ceYppbAWyH68fNRH5NrEuVj3oP1WnRBfrXf8vzbzij8BNZoAZhyhhbQfP2bGjghTl/">
                <i class="fab fa-facebook-square"></i>
                <p>Facebook</p>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.facebook.com/people/Karma-Technoz/pfbid02ceYppbAWyH68fNRH5NrEuVj3oP1WnRBfrXf8vzbzij8BNZoAZhyhhbQfP2bGjghTl/">
                <i class="fab fa-twitter"></i>
                <p>Twitter</p>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.instagram.com/karmatechnoz/">
                <i class="fab fa-instagram"></i>
                <p>Instagram</p>
              </a>
            </li>
          </template>
        </navbar>
        <!-- End Navbar Transparent-->
      </div>
    
</template>
<script>
import { Navbar } from '@/components';
// import { Navbar, DropDown } from '@/components';

export default {
  components: {
    Navbar, 
  }
};
</script>
<style></style>
