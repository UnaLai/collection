<template>
  <div class="intro">
    <div class="intro_name"></div>
    <div class="intro_information"></div>
  </div>
</template>

<script>
export default {
  name: "Intro"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.intro {
  width: 100%;
  height: 100vh;
  &_name {
    height: 40vh;
  }
  &_information {
    height: 60vh;
    background-color: #a6afb6;
  }
}
</style>
