<template>
  <ul class="sci">
    <li>
      <a href="https://vk.com/public181997456">
        <i class="fa fa-vk"></i>
      </a>
    </li>
    <li>
      <a href="https://www.facebook.com/o2bionics/">
        <i class="fa fa-facebook"></i>
      </a>
    </li>
    <li>
      <a href="https://twitter.com/BionicsO2">
        <i class="fa fa-twitter"></i>
      </a>
    </li>
    <li>
      <a href="https://www.instagram.com/o2bionics/">
        <i class="fa fa-instagram"></i>
      </a>
    </li>
    <li>
      <a href="https://www.youtube.com/channel/UCcimVtTZZhlEP78qv4l896A">
        <i class="fa fa-youtube"></i>
      </a>
    </li>
  </ul>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class SocialNwtwork extends Vue {
  @Prop() private msg!: string;
}
</script>