<template>
  <div class="hello">
    <form action>
      <blockquote>Matarpantanir</blockquote>
      <label for="first">Starfsmaður</label>
      <br>

      <select name="starfsmadur" id="id">
        <option value="odinn">Óðinn</option>
        <option value="robert">Róbert</option>
        <option value="oli">Óli</option>
        <option value="torvald">Þorvaldur</option>
        <option value="steina">Steina</option>
        <option value="halla">Halla</option>
        <option value="ragna">Ragna</option>
      </select>
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

  data() {
    return {
      starfsmadur,
      stadur
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style <style lang="stylus">
#app {
  .hello {
    blockquote {
      background: black;
      color: white;
      padding: 5px;
    }
  }
}
</style>