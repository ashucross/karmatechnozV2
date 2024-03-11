<template>
  <div
    class="section section-signup"
    style="background-image: url('img/bg11.jpg'); background-size: cover; background-position: top center; min-height: 700px;"
  >
    <div class="container">
      <div class="row">
        <card class="card-signup" header-classes="text-center" color="orange">
          <template slot="header">
            <h3 class="card-title title-up">Find Your Service</h3> 
          </template>
          <template>
            
            <fg-input
              class="no-border"
              placeholder="Enter Your Phone Number"
              addon-left-icon="now-ui-icons text_caps-small"
            >
            </fg-input>  
            <fg-input
              class="no-border"
              placeholder="Enter what type of service you want !"
              addon-left-icon="now-ui-icons text_caps-small"
            >
            </fg-input>  
          </template>
          <div class="card-footer text-center">
            <n-button type="neutral" round size="lg">Get call</n-button>
          </div>
        </card>
      </div>
      <!-- <div class="col text-center">
        <router-link
          to="/login"
          class="btn btn-simple btn-round btn-white btn-lg"
        >
          Login
        </router-link>
      </div> -->
    </div>
  </div>
</template>
<script>
import { Card, FormGroupInput, Button } from '@/components';

export default {
  components: {
    Card,
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput
  }
};
</script>
<style></style>
