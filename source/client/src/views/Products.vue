<template>
  <div class="special-block">
    <h2>Наши продукты</h2>

    <table
      id="table-cert table-nonfluid"
      class="table table-striped table-bordered"
      style="width: 100%;"
    >
      <!-- HEADER of Table -->
      <thead>
        <tr>
          <th>Название продукта</th>
          <th>Короткое описание</th>
          <th>Тип системы авторизации</th>
          <th>веб-сайт продукта</th>

          <th>Тип распространения</th>
        </tr>
      </thead>
      <tbody id="data-cert">
        <tr>
          <td>O2 Business <br>("О2 Бизнес")</td>
          <td>Программный продукт предназначенный для ведения бизнеса в удаленном режиме.</td>
             <td>
            <p>Аккаунт на базе единого аккаунта<br> O2 Auth</p>
          </td>
          <td>
            <a href="http://www.o2-bus.com">www.o2-bus.com</a>
          </td>

          <td>Подписка</td>
        </tr>
        <tr>
          <td>O2 Presentsigth <br>("О2 Презентсайт")</td>
          <td>Программный продукт предназначенный для покупки и продажи видео-курсов.</td>
            <td>
            <p>Аккаунт на базе единого аккаунта<br> O2 Auth</p>
          </td>
           <td>
            <a href="http://www.o2presentsight.com">www.o2presentsight.com</a>
          </td>

          <td>Подписка</td>
        </tr>
        <tr>
          <td>O2 Chat <br>("О2 Чат")</td>
          <td>Программный продукт. Бизнес-чат. Возможности: установка на веб-сайт с любой платформой(CMS)</td>
             <td>
            <p>Аккаунт на базе единого аккаунта<br> O2 Auth</p>
          </td>
          <td>
            <a href="http://www.o2-chat.com">www.o2-chat.com</a>
          </td>
          <td>Подписка</td>
        </tr>
        <tr>
          <td>O2 Certificate <br>("О2 Сертификаты")</td>
          <td>Программный продукт. Бизнес-чат. Возможности: установка на веб-сайт с любой платформой(CMS)</td>
           <td>
            <p>Аккаунт на базе единого аккаунта<br> O2 Auth</p>
          </td>
          <td>
            <p>Распространяется как часть платформы "O2 Business"</p>
          </td>
          <td>Подписка+лицензия</td>
        </tr>

        <tr>
          <td> O2 Bionics Global <br> ("О2 Бионикс Глобал")</td>
          <td>Програмнный продукт. Мобильная версия для клиентов корпорации O2 Bionics Inc.</td>
    
             <td>
           <p>Аккаунт на базе единого аккаунта<br> O2 Auth</p>
          </td>
                <td>
            <p>Распространяется в магазине <br><a href="http://">Google Play</a>, <a href="http://">Apple Store</a></p>
          </td>
          <td>Условно бесплатно. <br>Платный доп. функционал.</td>
        </tr>

         <tr>
          <td> PFR Center Global <br> ("ПФР Центр Глобал")</td>
          <td>Программный продукт. Бизнес-чат. Возможности: установка на веб-сайт с любой платформой(CMS)</td>
         
             <td>
           <p>Аккаунт на базе единого аккаунта<br> O2 Auth</p>
          </td>
           <td>
            <p>Распространяется в магазине <br><a href="http://">Google Play</a>, <a href="http://">Apple Store</a></p>
          </td>
          <td>Условно бесплатно. <br>Платный доп. функционал.</td>
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
  name: "Products",
  components: {
    SocialNetwork
  }
};
</script>
