<template>
  <div class="hello">
    <div id="card">
      <header>
        {{title}}
      </header>
      <div>
        {{content}}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      title: "Dianosaur",
      content: "Dinosaurs are a diverse group of animals of the clade Dinosauria that first appeared during the Triassic period. Although the exact origin and timing of the evolution of dinosaurs is the subject of active research, the current scientific consensus places their origin between 231 and 243 million years ago."
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
