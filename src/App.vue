<template>
  <header>
    <h2>{{ msg }}</h2>
  </header>
  <div>
    <the-card cardTitle="About Me">
      <p>Hi, I am Mamunur Rashid Rimon, blah blah blah ...</p>
    </the-card>
    <the-card cardTitle="Apple iPhone 12 Pro">
      <img
        src="https://fdn2.gsmarena.com/vv/bigpic/apple-iphone-12-pro--.jpg"
        alt=""
      />
      <p>
        Versions: A2407 (International); A2341 (USA); A2406 (Canada, Japan);
        A2408 (China, Hong Kong)
      </p>
    </the-card>
    <the-card cardTitle="Services">
      <ul>
        <li>Web Development</li>
        <li>Software Development</li>
        <li>Mobile app Development</li>
      </ul>
    </the-card>

    <the-card cardTitle="Test card"> </the-card>
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
</style>
