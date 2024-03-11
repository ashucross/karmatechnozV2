<template>
  <div class="section section-tabs">
    <div class="container">
      <div class="title">
        <h4>How we process</h4>
      </div>
      <div class="row">
        <div class="col-md-10 ml-auto col-xl-12 mr-auto">
          <p class="category">Steps</p>
          <!-- Nav tabs -->
          <card>
            <tabs
              slot="raw-content"
              tab-content-classes="tab-content-padding text-center"
            >
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons arrows-1_minimal-right"></i> Enter service requirement
                </template>
                <p>
                  Enter the service name or explain the service you want...
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons tech_mobile"></i> Get call
                </template>
                <p>
                  Our specialist will call you for service confirmation...
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons ui-1_check"></i> Finalize your service
                </template>
                <p>
                  Our team member will finalize the time to reach the service to you...
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons business_money-coins"></i> Make payment
                </template>
                <p>
                  Make payment and receive service.
                </p>
              </tab-pane>
            </tabs>
          </card>
        </div>
        <!-- <div class="col-md-10 ml-auto col-xl-6 mr-auto">
          <p class="category">Tabs with Background on Card</p> 
          <div class="card">
            <tabs
              centered
              type="neutral"
              tab-nav-wrapper-classes="card-header"
              tab-content-classes="card-body text-center"
              data-background-color="orange"
            >
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons objects_umbrella-13"></i> Home
                </template>
                <p>
                  I think that’s a responsibility that I have, to push
                  possibilities, to show people, this is the level that things
                  could be at. So when you get something that has the name Kanye
                  West on it, it’s supposed to be pushing the furthest
                  possibilities. I will be the leader of a company that ends up
                  being worth billions of dollars, because I got the answers. I
                  understand culture. I am the nucleus.
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons shopping_cart-simple"></i> Profile
                </template>
                <p>
                  I will be the leader of a company that ends up being worth
                  billions of dollars, because I got the answers. I understand
                  culture. I am the nucleus. I think that’s a responsibility
                  that I have, to push possibilities, to show people, this is
                  the level that things could be at. I think that’s a
                  responsibility that I have, to push possibilities, to show
                  people, this is the level that things could be at.
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons shopping_shop"></i> Messages
                </template>
                <p>
                  I think that’s a responsibility that I have, to push
                  possibilities, to show people, this is the level that things
                  could be at. So when you get something that has the name Kanye
                  West on it, it’s supposed to be pushing the furthest
                  possibilities. I will be the leader of a company that ends up
                  being worth billions of dollars, because I got the answers. I
                  understand culture. I am the nucleus.
                </p>
              </tab-pane>
              <tab-pane>
                <template slot="label">
                  <i class="now-ui-icons ui-2_settings-90"></i> Settings
                </template>
                <p>
                  "I will be the leader of a company that ends up being worth
                  billions of dollars, because I got the answers. I understand
                  culture. I am the nucleus. I think that’s a responsibility
                  that I have, to push possibilities, to show people, this is
                  the level that things could be at."
                </p>
              </tab-pane>
            </tabs>
          </div> 
        </div> -->
      </div>
    </div>
  </div>
</template>
<script>
import { Card, Tabs, TabPane } from '@/components';

export default {
  components: {
    Card,
    Tabs,
    TabPane
  }
};
</script>
<style>
.tab-content.tab-content-padding {
  padding: 20px;
}
</style>
