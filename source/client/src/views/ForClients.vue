<template>
  <div>
    <p>For client</p>
    <social-network />
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
