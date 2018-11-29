<template>
  <div>
    {{ msg }}
    <div id="app-2">
      <span v-bind:title="message">
        艾菲特
      </span>
    </div>
  </div>

</template>

<script>
export default {
    name: "hand",
    data() {
        return {
            msg: "afjqr",
            message: "页面加载于 " + new Date().toLocaleString()
        };
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
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
