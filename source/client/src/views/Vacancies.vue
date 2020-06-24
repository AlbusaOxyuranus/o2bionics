<template>
  <div>
    <p>На данный момент свободные вакансии отстуствуют</p>
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
  name: "Vacancies",
  components: {
    SocialNetwork
  }
};
</script>