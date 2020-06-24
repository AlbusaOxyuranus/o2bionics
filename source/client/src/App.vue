<template>
  <section>
    <div class="header">
      <div class="logo">
        <img src="logo.png" class="img-logo" width="7%" />
        <span class="logo-text">O2 BIONICS</span>
      </div>
      <ul id="navigation">
        <li>
          <router-link to="/">Главные</router-link>
        </li>
        <li>
          <router-link to="/services">Услуги</router-link>
        </li>
        <li>
          <router-link to="/products">Продукты</router-link>
        </li>
        <li>
          <router-link to="/for_clients">Клиентам</router-link>
        </li>
        <li>
          <router-link to="/contacts">Контакты</router-link>
        </li>
        <li>
          <router-link to="/vacancies">Вакансии</router-link>
        </li>
        <i class="fa fa-times x2" onclick="menuToggle()"></i>
      </ul>
    </div>
    <router-view></router-view>


    <div class="copyright">
      2020
      <i class="fa fa-copyright"></i> Все права защищены.
      O2 Bionics Inc. Разработка и продвижение веб-сайтов
    </div>
  </section>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
