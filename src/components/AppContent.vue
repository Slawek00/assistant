<template>
<div id = content>
  <div class="parallax"></div>
  <div id = "container" class="centre-container">
    <h1>Wirtualny asystent</h1>
    <h1>dla Twojej firmy</h1>
    <button type="submit">Zobacz usługi</button>
  </div>
  <div id="container-about" class="centre-container-about">
    <button type="submit">Czytaj więcej</button>
  </div>
  <div id="container-li">
    <h1>Jak mogę Ci pomóc?</h1>
    <ul>
      <li>Obsługa administracyjna</li>
      <li>Obsługa klienta</li>
      <li>Zarządzanie projektami</li>
      <li>Zarządzanie social mediami</li>
      <li>Dane i badania</li>
      <li>Osobisty asystent</li>
    </ul>
    <button type="submit">Zobacz plany</button>
  </div>
  <div id="container-opinion">
    <div class="opinion left-opinion"></div>
    <div class="opinion center-opinion"></div>
    <div class="opinion right-opinion"></div>
  </div>
  <div id="container-link">
    <div id="container-link-content" class="center-content-container-link">
    <h1>Przeniosę Twój biznes na wyższy poziom!</h1>
    <button type="submit">Kontakt</button>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "AppContent"
}
</script>

<style scoped>
button{
  width: 150px;
  height: 40px;
  background-color: coral;
  border: none;
  color: #444554;
}

#content button:hover{
  background-color: #444554;
  color: white;
  transition: 500ms;
}

#container button:hover{
  background-color: whitesmoke;
  color: #444554;
  transition: 500ms;
}

#container{
  position: absolute;
  color: #444554;
}

#container-about{
  margin-top: 75px;
  height: 500px;
  width: 750px;
  background-color: white;
  box-shadow: 5px 5px 5px #444554;
}

#container-opinion{
  width: 100%;
  height: 500px;
  background-color: #444554;
}

#container-li{
  width: 100%;
  height: 1000px;
  background-color: white;
}

#container-link{
  width: 100%;
  height: 800px;
  background-color: #e3e7e6;
  text-align: center;
}

.parallax{
  background-image: url("../assets/top-view-arrangement-of-natural-material-stationery.jpg");
  min-height: 600px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.opinion{
  width: 350px;
  height: 400px;
  background-color: white;
}

.centre-container{
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.centre-container-about{
  position: absolute;
  top: 90%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.left-opinion{
  position: absolute;
  top: 310%;
  left: 20%;
  transform: translate(-50%, -50%);
}

.center-opinion{
  position: absolute;
  top: 310%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.right-opinion{
  position: absolute;
  top: 310%;
  left: 80%;
  transform: translate(-50%, -50%);
}

.center-content-container-link{
  position: absolute;
  top: 390%;
  left: 50%;
  transform: translate(-50%, -50%);
}

</style>