<template>
  <div class="hello">
    <form action>
      <blockquote>Matarpantanir</blockquote>
      <label for="first">Starfsmaður</label>
      <br>
      <input type="text" v-model="starfsmadur">
      <br>
      <br>
      <label for="first">Veitingastaður</label>
      <br>
      <input type="text" v-model="stadur">
    </form>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style <style lang="stylus" scoped>
body {
  background: red;
}
</style>