<template>
    <div id="navbar">
        <nav>
            <ul class="nav-list">
                <li>
                    <router-link to="/" class="Nav-link link">Home</router-link>
                </li>
                <br>
                <li>
                    <router-link to="/About" class="Nav-link link">About</router-link>
                </li>
                <br>
                <li>
                    <router-link to="/Contact" class="Nav-link link">Contact</router-link>
                </li>
                <br> 
                <li>
                    <a href="https://www.linkedin.com/in/gian-luca-plate-6b2192293/" class="Nav-link link">Linkedin</a>
                </li>
                <br>
                <li>
                    <a href="https://twitter.com/GianLucaPlate" class="Nav-link link">Twitter</a>
                </li>
            </ul>
        </nav>
    </div>
</template>
  
<script>
export default {

}
</script>
  
<style>
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300..700&family=Playpen+Sans&display=swap');

#navbar {
    position: fixed;
    top: 265px;
    left: 20px;
    width: 10%;
    height: 50%;
    background-color: rgb(255, 255, 255);
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 15px;
    z-index: 1000;
}

.nav-list {
    list-style: none;
    padding: 0;
    display: flex;
    flex-direction: column;
}

.nav-list ul li{
    margin-top: 20px;
}

.Home-link {
    font-size: 25px;
    color: #06c;
}

.Nav-link {
    font-size: 25px;
    color: #06c;
    margin-top: 30px;
}


.link {
    text-decoration: none;
    font-weight: bold;
    font-family: "Comfortaa", sans-serif;
}

.link:hover {
    font-weight: bold;
    font-family: "Comfortaa", sans-serif;
    text-decoration: underline;
}
</style>