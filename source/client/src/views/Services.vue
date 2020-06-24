<template>
  <div>
    <h2>Наши услуги</h2>
    <table
      id="table-cert table-nonfluid"
      class="table table-striped table-bordered"
      style="width: 100%;"
    >
      <!-- HEADER of Table -->
      <thead>
        <tr>
          <th>Название услуги</th>
          <th>Доп. описание работ</th>
          <th>Стоимость в экв. $</th>
          <th>Стоимость в бел. рублях</th>
        </tr>
      </thead>
      <tbody id="data-cert">
        <tr>
          <td>Продвижение веб-сайта</td>
          <td>Полная оценку стоимости услуги будет произведена после анализа вашей сферы бизнеса и т.д.</td>
          <td>от 350</td>
          <td>от 840</td>
        </tr>

        <tr>
          <td>Услуги контекстной рекламы</td>
          <td>Полная оценку стоимости услуги будет произведена после анализа вашей сферы бизнеса и т.д.</td>
          <td>от 100</td>
          <td>от 240</td>
        </tr>
        <tr>
          <td>Разработка веб-сайта</td>
          <td>Полная оценка на разработку сайта может варировать цену в зависимости от Технического задания.</td>
          <td>от 300</td>
          <td></td>
        </tr>
      </tbody>
    </table>
    <social-network></social-network>
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
  name: "Services",
  components: {
    SocialNetwork
  }
};
</script>
