<template>
  <div>
    <h1>{{ msg }}</h1>
    <h2>{{ msg2 }}</h2>
    <h3>{{ msg3 }}</h3>
    <h4>{{ msg4 }}</h4>
    <h5>{{ msg5 }}</h5>
  </div>
</template>

<script>
export default {
  name: "LandingPage",
  props: {
    msg: String,
    msg2: String,
    msg3: String,
    msg4: String,
    msg5: String
  }
};
</script>
