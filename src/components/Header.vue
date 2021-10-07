<template>
  <header>
    <a href="#" class="logo"
      ><span>MOVIES</span><i class="fas fa-thumbtack"></i>SPOT</a
    >

    <div
      id="menu"
      :class="{ 'fas fa-bars': menuClass, 'fas fa-times': !menuClass }"
      @click="menu"
    ></div>

    <!-- <nav class="navbar"> -->
    <nav :class="{ navbar: navbarClass, 'navbar nav-toggle': !navbarClass }">
      <ul>
        <li><a class="active" href="#home">home</a></li>
        <li><a href="#gallery">gallery</a></li>
        <li><a href="#about">about</a></li>
        <li><a href="#movies">movies</a></li>
        <li><a href="#product">product</a></li>
      </ul>
    </nav>
  </header>
</template>
<script>
export default {
  data() {
    return {
      menuClass: true,
      navbarClass: true,
    };
  },
  created: function() {
    window.addEventListener("scroll", this.handleScroll);
  },
  unmounted: function() {
    window.removeEventListener("scroll", this.handleScroll);
  },
  methods: {
    menu() {
      // alert("menu clicked");
      this.menuClass = !this.menuClass;
      this.navbarClass = !this.navbarClass;
      // this.searchIconClass = true;
    },
    // search() {
    //   // alert("search clicked");
    //   this.searchIconClass = !this.searchIconClass;
    //   this.menuClass = true;
    //   this.navbarClass = true;
    // },
    handleScroll() {
      this.menuClass = true;
      this.navbarClass = true;
      // this.searchIconClass = true;
    },
  },
};
</script>
<style>
header {
  position: fixed;
  top: 2.5rem;
  left: 50%;
  transform: translateX(-50%);
  width: 93%;
  z-index: 1000;
  /* background: #fff; */
  background-image: radial-gradient(
    circle farthest-corner at 10% 20%,
    rgba(255, 209, 67, 1) 0%,
    rgba(255, 145, 83, 1) 90%
  );
  box-shadow: 0 0.5rem 1rem rgba(0, 0, 0, 0.1);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1.3rem 3rem;
  border-radius: 0.5rem;
}

header .logo {
  color: #333;
  font-size: 2.5rem;
  letter-spacing: 1px;
}

header .logo span {
  color: var(--red);
}

header .navbar ul {
  display: flex;
  align-items: center;
  justify-content: center;
  list-style: none;
}

header .navbar ul li {
  margin-left: 3rem;
}

header .navbar ul li a {
  font-size: 2rem;
  color: #333;
}

header .navbar ul li a.active,
header .navbar ul li a:hover {
  /* color: var(--red); */
  color: #3c40c6;
}

#menu {
  font-size: 3rem;
  /* color: #666; */
  color: #1e272e;
  cursor: pointer;
  display: none;
}
</style>
