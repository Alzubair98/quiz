<template>
  <div class="ctr">
    <questions></questions>
    <results></results>

    <button type="button" class="reset-btn">Reset</button>
  </div>
</template>

<script>
import Questions from "./component/Questions.vue";
import Results from "./component/Results.vue";
export default {
  name: "App",
  components: {
    Questions,
    Results,
  },
};
</script>

<style scoped></style>
