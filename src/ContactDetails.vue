<template>
  <div class="contact-details">
    <h1 class="contact-heading">Contact Details</h1>
    <p><strong> Name:</strong>{{ name }}</p>
    <p><strong> Website:</strong> www.rimonbd.com</p>
    <p><strong> Address:</strong> Dhaka, Bangladesh</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "Mamunur Rashid"
    };
  }
};
</script>

<style scoped>
.contact-details {
  border: 1px solid gray;
  margin: 11px 22px;
  padding: 22px;
}

.contact-heading {
  color: rgb(0, 73, 107);
}
</style>
