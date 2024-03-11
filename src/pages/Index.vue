<template>
  <div>
    <div class="page-header clear-filter" filter-color="orange">
      <parallax
        class="page-header-image"
        style="background-image:url('img/header.jpg')"
      >
      </parallax>
      <div class="container">
        <div class="content-center brand">
          <img class="n-logo" src="img/now-logo.png" alt="" />
          <h1 class="h1-seo">Karma Technologies</h1> 
          <a style="color:white" href="https://karmatechnoz.com" target="_blank">
          <h3 >Find Service</h3>
          <i class="now-ui-icons arrows-1_minimal-down"></i>
          </a>
        </div>
        <!-- <h6 class="category category-absolute">
          Designed by
          <a href="https://karmatechnoz.com" target="_blank">
            <img src="img/now-logo.png" class="invision-logo" /> </a> 
        </h6> -->
      </div>
    </div>
    <div class="main">
      <div class="section section-images">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <div class="hero-images-container">
                <img src="img/hero-image-1.png" alt="" />
              </div>
              <div class="hero-images-container-1">
                <img src="img/hero-image-2.png" alt="" />
              </div>
              <div class="hero-images-container-2">
                <img src="img/hero-image-3.png" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <signup-form></signup-form>
    <!-- <basic-elements></basic-elements> -->
    <navigation></navigation>
    <tabs-section></tabs-section>
    <!-- <progress-pagination></progress-pagination> -->
    <!-- <notifications></notifications> -->
    <!-- <typography></typography>
    <javascript-components></javascript-components> -->
    <carousel-section></carousel-section>
    <nucleo-icons-section></nucleo-icons-section>
    <div class="section">
      <div class="container text-center">
        <div class="row justify-content-md-center">
          <div class="col-md-12 col-lg-8">
            <h2 class="title">Trust Us</h2>
            <h5 class="description">
              We are a social service provider company which works
              to devliver the best service to our users. We do not limit the 
              service provider capabilities to privide there service where
              we found a customer.
            </h5>
          </div>
        </div>
      </div>
    </div>
    <!-- <examples-section></examples-section> -->
    <download-section></download-section>
  </div>
</template>
<script>
import { Parallax } from '@/components';
// import BasicElements from './components/BasicElementsSection';
import Navigation from './components/Navigation';
import TabsSection from './components/Tabs';
// import ProgressPagination from './components/ProgressPagination';
// import Notifications from './components/Notifications';
// import Typography from './components/Typography';
// import JavascriptComponents from './components/JavascriptComponents';
import CarouselSection from './components/CarouselSection';
import NucleoIconsSection from './components/NucleoIconsSection';
import SignupForm from './components/SignupForm';
// import ExamplesSection from './components/ExamplesSection';
import DownloadSection from './components/DownloadSection';

export default {
  name: 'index',
  bodyClass: 'index-page',
  components: {
    Parallax,
    // BasicElements,
    Navigation,
    TabsSection,
    // ProgressPagination,
    // Notifications,
    // Typography,
    // JavascriptComponents,
    CarouselSection,
    NucleoIconsSection,
    SignupForm,
    // ExamplesSection,
    DownloadSection
  }
};
</script>

