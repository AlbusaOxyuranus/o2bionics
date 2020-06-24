<template>
  <div>
    <div class="bannerText">
      <h2>Креативный подход</h2>
      <h3>Мы синтезируем дизайн и новые технологии</h3>
      <p>Мы быстро развивающаяся компания, которая предлагает широкий спектр услуг. От разработки специфического программного обеспечения, до небольших сайтов. Также мы предоставляем услуги SEO продвижения. В нашем штате имеются сертифицированные специалисты по контекстной рекламы Google Adwords, Яндекс Директ.</p>
      <a href="#" class="read-more">Читать больше</a>
    </div>
    <img src="bulb.png" class="bulb" />
    <social-network></social-network>
    <div class="element1"></div>
    <div class="element2"></div>
    <div class="element3"></div>
    <div class="element4"></div>
    <div class="element5"></div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import SocialNetwork from "@/components/SocialNetwork.vue";
export default {
  name: "Home",
  components: {
    SocialNetwork
  }
};
</script>
