<template>
  <Category title="Contact Me" border-color="border-purple-600">
    <p>Want to speak with me?</p>
    <p>There's multiple ways to get in contact with me.</p>
    <div class="flex flex-wrap justify-center align-items-center mt-4">
      <a
        class="button button-linkedin mr-2"
        href="https://www.linkedin.com/in/patrick-ratzow-685452157/"
        >LinkedIn</a
      >
      <a
        class="
          button
          border-purple-600
          hover:bg-purple-600
          text-purple-600
          hover:text-white
          mr-2
        "
        href="mailto:patrickratzow@hotmail.dk"
        >Email</a
      >
      <a
        class="
          button
          border-white
          hover:bg-white
          text-white
          hover:text-black
          mr-2
        "
        href="https://steamcommunity.com/id/randomiddududu"
        >Steam</a
      >
      <a
        class="
          button
          border-blue-600
          hover:bg-blue-600
          text-blue-600
          hover:text-white
        "
        href="https://www.gmodstore.com/users/sleeppyy"
        >GmodStore</a
      >
    </div>
  </Category>
</template>

<script lang="ts">
import Vue from "vue"
import Category from "~/components/Category.vue"

export default Vue.extend({
  components: {
    Category,
  },
})
</script>

<style>
.button {
  @apply p-2 border-2 rounded mt-2 transition-all;
}

/*
  .button-discord {
    border-color: #7289DA;
    color: #7289DA;
  }
  .button-discord:hover {
    background: #7289DA;
    color: black;
  }
  */

.button-linkedin {
  border-color: #0077b5;
  color: #0077b5;
}
.button-linkedin:hover {
  background: #0077b5;
  color: white;
}
</style>
