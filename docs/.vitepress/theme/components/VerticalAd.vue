<script>
export default {
  data() {
    return {
      show: false
    }
  },
  mounted() {
    this.show = navigator.language.indexOf('zh') > -1
  }
}
</script>
