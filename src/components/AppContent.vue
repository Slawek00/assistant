<template>
<div id = content>
  <img src="../assets/top-view-arrangement-of-natural-material-stationery.jpg" alt="banner">
  <div id = "container" class="centred">
    <h1>Wirtualny asystent</h1>
    <h1>dla Twojej firmy</h1>
    <button type="submit">Zobacz usługi</button>
  </div>
  <div id="container-about" class="centred-bottom">
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
</div>
</template>

<script>
export default {
  name: "AppContent"
}
</script>

<style scoped>
#content{
  width: 100%;
  height: 1000px;
}


img{
  height: 600px;
  width: 100%;
}

button{
  width: 150px;
  height: 40px;
  background-color: coral;
  border: none;
  color: #444554;
}

button:hover{
  background-color: whitesmoke;
  transition: 600ms;
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

.centred{
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.centred-bottom{
  position: absolute;
  top: 90%;
  left: 50%;
  transform: translate(-50%, -50%);
}

</style>