<template>
<div id = content>
  <div class="parallax"></div>
  <div id = "container" class="centre-container">
    <h1>Wirtualny asystent</h1>
    <h1>dla Twojej firmy</h1>
    <button type="submit">Zobacz usługi</button>
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

.parallax{
  background-image: url("../assets/top-view-arrangement-of-natural-material-stationery.jpg");
  min-height: 600px;
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.centre-container{
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
</style>