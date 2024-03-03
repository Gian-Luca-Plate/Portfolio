<template>
  <div id="home-page">
    <table>
      <tr>
        <td>
          <h1 class="homePageüberschrift">Gian Luca</h1>
        </td>
        <td>
          <router-link to="/About" class="Nav-link link td-a">About</router-link>
        </td>
        <td>
          <router-link to="/About" class="Nav-link link td-a-weitere">Contact</router-link>
        </td>
        <td>
          <a href="https://www.linkedin.com/in/gian-luca-plate-6b2192293/"
            class="Nav-link link td-a-weitere">Linkedin</a>
        </td>
        <td>
          <a href="https://twitter.com/GianLucaPlate" class="Nav-link link td-a-weitere">Twitter</a>
        </td>
      </tr>
    </table>


    <table>
      <tr>
        <td>
          <img src="../assets/profilbild.JPG" alt="" class="profilebild">
        </td>
        <td>
          <h2 class="kleineubershriftBild">Hallo ich bin</h2>
          <h1 class="homePageüberschriftBild">Gian Luca</h1>
          <button class="githup-button">
            <a href="https://github.com/Gian-Luca-Plate">
              <table>
                <tr>
                  <td>
                    <img src="https://tangerine-hummingbird-1479b6.netlify.app/assets/github.png" alt="">
                  </td>
                  <td>
                    <div>Gian-Luca-Plate</div>
                  </td>
                </tr>
              </table>

            </a>
          </button>
        </td>
      </tr>
    </table>


  </div>
</template>

<script>
import Navbar from './Navbar.vue';
export default {
  name: "Home-Page",
  components: {
    Navbar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300..700&family=Playpen+Sans&display=swap');

.profilebild {
  border-radius: 50px;
  width: 300px;
  display: flex;
  justify-content: left;
  margin-left: 570px;
  margin-top: 140px;
}

.homePageüberschrift {
  font-weight: bold;
  font-family: "Comfortaa", sans-serif;
  font-size: 40px;
  margin-left: 80px;
}

.homePageüberschriftBild {
  font-weight: bold;
    font-family: "Comfortaa", sans-serif;
    font-size: 40px;
    margin-left: 173px;
}
.kleineubershriftBild{
  font-weight: bold;
    font-family: "Comfortaa", sans-serif;
    font-size: 20px;
    margin-left: 201px;
    margin-top: 128px;
    color: rgb(85, 85, 85);
}

.td-a {
  margin-left: 1160px;
}

.td-a-weitere {
  margin-left: 10px;

}

.githup-button {
  background-color: white;
    border-radius: 2rem;
    width: 160px;
    height: 49px;
    border: rgb(0, 0, 0) 0.1rem solid;
    margin-left: 200px;
}
 


.githup-button:hover {
  background-color: rgb(53, 53, 53);
  border-radius: 2rem;
  width: 160px;
  height: 49px;
  border: none;
  margin-left: 200px;
}

.githup-button a table tr td img {
  width: 32px;
  display: flex;
  justify-content: left;
}

.githup-button a table tr td div {
  color: black;
}

.githup-button a {
  text-decoration: none;
}
</style>