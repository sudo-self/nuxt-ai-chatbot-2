<script>
  export default {
    data() {
      return {
        colors: ['system', 'light', 'dark', 'sepia']
      }
    }
  }
</script>
<li
  v-for="color of colors"
  :key="color"
  @click="$colorMode.preference = color"
></li>
