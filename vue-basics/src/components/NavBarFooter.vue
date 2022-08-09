<template>
  <div>
    <nav class="navbar">
    <img class="logo" src="https://i0.wp.com/eltallerdehector.com/wp-content/uploads/2022/06/b79b0-batman-logo-png-images-download-free.png?resize=700%2C700&ssl=1" alt="logo">
    <ul class="nav-menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">BatCave</a></li>
        <li><a href="#">BatMobile</a></li>
        <li><a href="#">Contact Alfred</a></li>
    </ul>
  </nav>
  <h1>{{2+2}}</h1>  
  <h1>{{iAmBatman}}</h1>
  <h1 v-if="robin">{{robin}}</h1>
  <h1 v-for="villain in villains" :key="villain">{{villain.name}} - {{villain.place}} - {{villain.realName}}</h1>

  <footer>
    <img class="footer-logo" src="https://i0.wp.com/eltallerdehector.com/wp-content/uploads/2022/06/b79b0-batman-logo-png-images-download-free.png?resize=700%2C700&ssl=1" alt="logo">
    <ul class="footer-menu">
        <li><a href="#">Home</a></li>
        <li><a href="#">BatCave</a></li>
        <li><a href="#">BatMobile</a></li>
        <li><a href="#">Contact Alfred</a></li>
    </ul>
  </footer>
  </div>
</template>

<script>
export default {
    data() {
        return {
            iAmBatman: "Batman",

            robin: "Robin",

            villains: [
                {name: "Joker", place: "Gotham City", realName: "Jack Napier"},
                {name: "Catwoman", place: "Gotham City", realName: "Selina Kyle"},
                {name: "Riddler", place: "Gotham City", realName: "Edward E. Nigma"}
            ]
        }
    }
}
</script>

<style>

    .navbar {
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: rgb(61, 58, 58);
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
        font-weight: 700;
        color: white;
        
    }

    footer {
        height: 10rem;
        display: flex;
        justify-content: space-around;
        align-items: center;
        background-color: rgb(61, 58, 58);
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
        font-weight: 700;
        color: white;
    }
</style>