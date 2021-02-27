<template>
  <div>
    <h1>{{ msg }}</h1>
    <contact-details></contact-details> <contact-details></contact-details>
    <contact-details></contact-details>
  </div>
</template>

<script>
import ContactDetails from "./ContactDetails.vue";

export default {
  data() {
    return {
      msg: "Welcome to Vue3 Bangla Tutorial"
    };
  },
  components: {
    ContactDetails
  }
};
</script>
