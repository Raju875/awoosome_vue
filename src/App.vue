<template>
  <div>
    <h3>
      {{ msg }}
      <Contact></Contact>
    </h3>
  </div>
</template>

<script>
import ContactDetails from "./ContactDetails.vue";

export default {
  components: {
    Contact: ContactDetails,
  },

  data() {
    return {
      msg: "Hi! I am vue cli.",
    };
  },
};
</script>
