<template>
  <div>
    <p>Наши продукты</p>

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
          <td>
              
              
          </td>
          <td>Услуги размещения</td>
          <td>1 месяц</td>
          <td>12</td>
        </tr>
      </tbody>
    </table>

    <social-network></social-network>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SocialNetwork from "@/components/SocialNetwork.vue";
export default {
  name: "Products",
  components: {
    SocialNetwork
  }
};
</script>
