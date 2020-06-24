<template>
  <div>
    <p>Service</p>
    <social-network></social-network>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SocialNetwork from "@/components/SocialNetwork.vue";
export default {
  name: "Services",
  components: {
    SocialNetwork
  }
};
</script>
