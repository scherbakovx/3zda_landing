<template>
  <div id="app">
    <LandingPage 
    msg="Здесь будет все про того самого Пиздабота (http://tele.click/pizda_da_bot)"
    msg2="Пока подпишитесь на меня в Твиторе (https://twitter.com/scherbakovx) или напишите мне в Телегу (http://t.me/@scherbakovx)"
    msg3="Это, конечно, лучший (НАИПИЗДАТЕЙШИЙ, ДА?) сайт в Интернете, спасибо, что надонатили мне денег на pizda.bot! (правда, спасибо)"
    msg4="<3 (люблю)"
    msg5="Конечно, этот сайт шутка, нормальный я сделаю ASAP, но вы сами знаете, какой из меня фронтендер (хуевый)"
    />
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
