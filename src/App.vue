<template>
  <div id="app">
    <LandingPage msg="Здесь будет все про того самого Пиздабота (http://tele.click/pizda_da_bot), а пока подпишитесь на меня в Твиторе (https://twitter.com/scherbakovx) или напишите мне в Телегу (http://t.me/@scherbakovx)" />
    <LandingPage msg2="Это, конечно, лучший сайт в Интернете, спасибо, что надонатили мне денег на pizda.bot!" />
  </div>
</template>

<script>
import LandingPage from "./components/LandingPage.vue";

export default {
  name: "app",
  components: {
    LandingPage
  }
};
</script>
