<template>
  <div class="ctr">
    <questions></questions>
    <div class="result">
      <div class="title">You got sample result 1!</div>
      <div class="desc">Enter a short description here about the result.</div>
    </div>
    <button type="button" class="reset-btn">Reset</button>
  </div>
</template>

<script>
import Questions from "./component/Questions.vue";
export default {
  name: "App",
  components: {
    Questions,
  },
};
</script>

<style scoped></style>
