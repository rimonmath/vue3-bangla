<template>
  <header>
    <h2>{{ msg }}</h2>
  </header>
  <div>
    <the-card cardTitle="About Me">
      <template #default>
        <p>Hi, I am Mamunur Rashid Rimon, blah blah blah ...</p>
      </template>

      <template #footer>
        <a href="https://rimonbd.com">Learn More</a>
      </template>
    </the-card>

    <the-card cardTitle="Website">
      <template #default>
        <p>www.rimonbd.com</p>
      </template>
    </the-card>
  </div>
</template>

<script>
import TheCard from "./TheCard.vue";

export default {
  data() {
    return {
      msg: "Vue3 Bangla Tutorial"
    };
  },
  components: {
    TheCard
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

ul {
  margin-left: 22px;
}

body {
  font-family: sans-serif;
  line-height: 1.8;
}

header {
  background-color: #1f2c46;
  color: #41b883;
  font-size: 22px;
  padding: 22px;
}

header h2 {
  text-align: center;
}

button {
  margin: 5px;
  padding: 5px 11px;
  cursor: pointer;
}
</style>
