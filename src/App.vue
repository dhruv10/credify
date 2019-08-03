<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>-->
      <div class="logo">
        <img
          data-v-64fe992e
          src="@/assets/credify_logo.svg"
          style="width: 50px; margin-top: 3px; margin-left: -10px;"
        />
      </div>
      <div class="user-display">
        <div class="notifications">
          <img
            data-v-4279a8fa
            src="https://app.incento.io/_nuxt/img/5d8e998.svg"
            style="width: 40px;"
          />
        </div>
        <div class="profile">
          <img
            data-v-126af358
            style="width: 40px;"
            src="https://app.incento.io/_nuxt/img/13533ce.svg"
          />
        </div>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 20px;
  display: flex;
  justify-content: space-between;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.user-display {
  display: flex;
  justify-content: flex-end;
}

.profile {
  margin-right: -20px;
  margin-left: 20px;
}
</style>

<style scoped>
</style>

