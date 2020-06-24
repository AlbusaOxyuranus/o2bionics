<template>
  <div>
    <p>На данный момент свободные вакансии отстуствуют</p>
    <social-network />
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