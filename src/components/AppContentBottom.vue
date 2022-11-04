<template>
<div id="container-bottom-content">
  <div id="container-opinion">
      <h1>Zaufały mi firmy i przedsiębiorcy<br>
        z całego świata</h1>
    <ul>
      <li><img src="../assets/drupal.svg" alt="logo"></li>
      <li><img src="../assets/digg.svg" alt="logo"></li>
      <li><img src="../assets/pied-piper.svg" alt="logo"></li>
    </ul>
    <div class="opinion"></div>
    <div class="opinion"></div>
    <div class="opinion"></div>
  </div>
  <div id="container-button">
    <button type="submit">Kontakt</button>
  </div>
</div>
</template>

<script>
export default {
  name: "AppContentBottom"
}
</script>

<style scoped>
#container-opinion{
  background-color: #444554;
  width: 100%;
  height: 700px;
  text-align: center;
  color: #e3e7e6;
}

#container-opinion h1{
  padding-top: 120px;
}

#container-opinion ul{
  margin-left: 23%;
  padding: 30px;
  list-style-type: none;
  display: grid;
  grid-template-columns: 250px 250px 250px;
  grid-template-rows: 200px;
}

#container-opinion li img{
  width: 120px;
  height: 100px;
}

#container-button{
  width: 100%;
  height: 900px;
  background-color: #e3e7e6;
}

#container-button button:hover{
  background-color: #444554;
  color: white;
  transition: 500ms;

}

</style>