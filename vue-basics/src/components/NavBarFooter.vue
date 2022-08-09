<template>
  <div>
    <nav class="navbar">
    <img class="logo" src="https://i0.wp.com/eltallerdehector.com/wp-content/uploads/2022/06/b79b0-batman-logo-png-images-download-free.png?resize=700%2C700&ssl=1" alt="logo">
    <ul class="nav-menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact Us</a></li>
    </ul>
  </nav>
  <footer>
    <img class="footer-logo" src="https://i0.wp.com/eltallerdehector.com/wp-content/uploads/2022/06/b79b0-batman-logo-png-images-download-free.png?resize=700%2C700&ssl=1" alt="logo">
    <ul class="footer-menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact Us</a></li>
    </ul>
  </footer>
  </div>
</template>

<script>
export default {

}
</script>

<style>

    .navbar {
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .logo {
        width: 7rem;
    }

    .nav-menu {
        display: flex;
        justify-content: space-around;
    }

    .nav-menu li {
        padding: 0 1rem;
        list-style-type: none;
    }

    .nav-menu a {
        text-decoration: none;
        font-weight: 700
    }

    footer {
        height: 10rem;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .footer-menu {
        display: flex;
        justify-content: space-around;
    }

    .footer-logo {
        width: 10rem;
    }

    .footer-menu li {
        padding: 0 1rem;
        list-style-type: none;
    }

    .footer-menu a {
        text-decoration: none;
        font-weight: 700
    }
</style>