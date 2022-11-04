<template>
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
  <div id = container-services>
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
</template>

<script>
export default {
  name: "AppTest"
}
</script>

<style scoped>
#container-about{
  margin-top: 75px;
  height: 500px;
  width: 750px;
  background-color: white;
  box-shadow: 5px 5px 5px #444554;
}

.centre-container-box{
  text-align: center;
  position: absolute;
  top: 80%;
  left: 50%;
  transform: translate(-50%, -50%);
}

#container-li{
  width: 100%;
  height: 1000px;
  background-color: white;
}





.opinion{
  width: 350px;
  height: 400px;
  background-color: white;
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

#container-box{
  width: 500px;
  height: 400px;
  background-color: white;
}

#container-services{
  text-align: center;
}

#container-services ul{
  list-style-type: none;
}

#container-opinion{
  width: 100%;
  height: 500px;
  background-color: #444554;
}

#container-link{
  width: 100%;
  height: 800px;
  background-color: #e3e7e6;
  text-align: center;
}
</style>