<template>
  <div id="app">
    <NavigationMobile />
    <div class="content" :class="{'open':showNav}">
      <div class="top-bar mob-nav">
        <div id="navigation-icon" v-if="mobileView"
          @click="showNav = !showNav">
          <i class="fas fa-bars clr-wht"></i>
        </div>
        <div id="navigation-icon" v-if="mobileView"
          >
          <img class="logo1" src="./assets/logo.png" />
        </div>
        <Navigation v-if="!mobileView" />
      </div>
      <Content />
    </div>
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import NavigationMobile from "./components/NavigationMobile.vue";
import Content from "./components/Content.vue";

export default {
  data: () => {
    return {
      mobileView: true,
      showNav: false
    };
  },
  methods: {
    handleView() {
      this.mobileView = window.innerWidth <= 990;
    }
  },
  components: {
    Navigation,
    NavigationMobile,
    Content
  },
  created() {
    this.handleView();
    window.addEventListener('resize', this.handleView);
  }
};
</script>

<style lang="scss">
@import url("https://use.fontawesome.com/releases/v5.9.0/css/all.css");

* {
  font-size: 1rem;
}

body {
   margin: 0;
background: transparent linear-gradient(350deg, #0E0E0E 0%, #1E1E1E 49%, #0E0E0E 100%) 0% 0% no-repeat padding-box;
opacity: 1;
}

#app {
  position: relative;
  width: calc(100% - 20px);
  height: calc(100vh - 20px);
  padding: 10px;
  color: black;
  overflow: hidden;
  // background-color: linear-gradient(87deg, #fb6340 0, #da1c5f 100%) !important;
}
.clr-wht{
color: white;
}
.top-bar {
  display: flex;
  width: 100%;
}
.logo1{
  width: 1.5rem;
  padding: 10px;
}
#navigation-icon {
  padding: 10px;
  margin-right: 10px;
  cursor: pointer;

  i {
    font-size: 2rem;
  }
}
.mob-nav{
    justify-content: space-between;
    display: flex;
}
.content {
  position: absolute;
  top: 10px;
  width: calc(100% - 60px);
  height: calc(100vh - 60px);
  padding: 20px;
  // background-color: black;
  background-image: url("./assets/hero1.png");

  // border-radius: 30px;
  box-shadow: 2px 2px 2px 1px rgba(0, 0, 0, 0.2);
  transition: 1s transform cubic-bezier(0,.12,.14,1);
}

.open {
  transform: translateX(300px);
}
</style>
