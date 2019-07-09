<template>
  <div>
    <h1>{{ msg }}</h1>
    <h1>{{ msg2 }}</h1>
  </div>
</template>

<script>
export default {
  name: "LandingPage",
  props: {
    msg: String,
    msg2: String
  }
};
</script>
