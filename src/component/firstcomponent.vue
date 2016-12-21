<template>
  <div id="firstcomponent">
    <h1>{{ msg2 }}</h1>
    <a> powered by {{ author }} </a>
  </div>
</template>

<script type="text/javascript">
export default {
  data () {
    return {
      msg2:"vue2.0",
      author: "ryansbeans"
    }
  }
}
</script>

<style>
</style>
