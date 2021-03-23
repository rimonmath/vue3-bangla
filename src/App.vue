<template>
  <div>
    <h1>{{ msg }}</h1>
    <contact-details
      v-for="contact in contacts"
      :key="contact.name"
      :name="contact.name"
      :website-address="contact.website"
      :address="contact.address"
    ></contact-details>
  </div>
</template>

<script>
import ContactDetails from "./ContactDetails.vue";

export default {
  data() {
    return {
      msg: "Welcome to Vue3 Bangla Tutorial",

      contacts: [
        {
          name: "Mamunur Rashid",
          website: "http://rimonbd.com",
          address: "Dhaka, Bangladesh"
        },
        {
          name: "Rimon",
          website: "http://rimoned.com",
          address: "Rajshahi, Bangladesh"
        },
        {
          name: "Rashid",
          website: "http://radhis.com",
          address: "Pabna, Bangladesh"
        }
      ]
    };
  },
  components: {
    ContactDetails
  }
};
</script>
