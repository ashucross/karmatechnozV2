<template>
  <footer
    class="footer"
    :class="{ [`footer-${type}`]: type }"
    :data-background-color="backgroundColor"
  >
    <div class="container">
      <nav>
        <ul>
          <li>
            <a href="https://www.karmatechnoz.com">
              Karmatechnoz
            </a>
          </li>
          <li>
            <a href="https://karmatechnoz.com">
              About Us
            </a>
          </li>
          <li>
            <a href="https://karmatechnoz.com">
              Blog
            </a>
          </li>
          <li>
            <a href="https://www.karmatechnoz.com">
              License
            </a>
          </li>
        </ul>
      </nav>
      <div class="copyright">
        &copy; {{ year }}, Designed by
        
        <a href="https://www.karmatechnoz.com" target="_blank" rel="noopener"
          >karmatechnoz</a
        >.
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  props: {
    backgroundColor: String,
    type: String
  },
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
