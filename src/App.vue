<template>
  <VTrafalgar />
</template>

<script>
import VTrafalgar from "./components/VTrafalgar.vue";

export default {
  name: "App",
  components: {
    VTrafalgar,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;

  font-family: "Mulish", sans-serif;
  font-style: normal;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
  display: block;
}
body {
  line-height: 1;
}
ol,
ul {
  list-style: none;
}
blockquote,
q {
  quotes: none;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
html,
body {
  height: 100%;
}
body {
  * {
    margin: 0;
    padding: 0;
  }
}
#app {
  height: 100%;
  display: flex;
  justify-content: center;
  font-size: 1.6rem;
}
</style>
