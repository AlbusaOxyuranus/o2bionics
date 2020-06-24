<template>
  <div>
      <h2>Для клиентов</h2>
      <h4>Доступ к личному кабинету</h4>
      <a href="http://">Перейти к личному кабинету</a>
      <div>
          <p>Для получения информации об оказаных услугах, новых ценах на услугах, а также о дополнительной информации, пожалуйста авторизуйтесь в системе.</p>
      </div>
    <!-- <p>For client</p> -->
    <social-network />
        <div class="element1"></div>
    <div class="element2"></div>
    <div class="element3"></div>
    <div class="element4"></div>
    <div class="element5"></div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SocialNetwork from "@/components/SocialNetwork.vue";
export default {
  name: "ForClients",
  components: {
    SocialNetwork
  }
};
</script>
