<template>
<div id="container-bottom-content">
  <div id="container-opinion">
      <h1>Zaufały mi firmy i przedsiębiorcy<br>
        z całego świata</h1>
      <div id="container-logo">
        <div id="logo-1"><img src="../assets/anchor-solid.svg" alt="logo"></div>
        <div id="logo-2"><img src="../assets/blogger.svg" alt="logo"></div>
        <div id="logo-3"><img src="../assets/drupal.svg" alt="logo"></div>
        <div id="logo-4"><img src="../assets/digg.svg" alt="logo"></div>
        <div id="logo-5"><img src="../assets/pied-piper.svg" alt="logo"></div>
      </div>
      <div id="opinion-one">
        <h2>Zorganizowany i skuteczny</h2>
      </div>
      <div id="opinion-two">
        <h2>Elastyczny i zangażowany</h2>
      </div>
      <div id="opinion-three">
        <h2>Kreatywny i pomysłowy</h2>
      </div>
  </div>
  <div id="contact">
    <div id="container">
    <div>
      <img src="../assets/gadgety.png" alt="image">
    </div>
    <div>
      <h1>Przeniosę Twój biznes na wyższy poziom!</h1>
    </div>
    <div>
      <button type="submit">Kontakt</button>
    </div>
    </div>
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

#container-opinion img{
  width: 150px;
  height: 100px;
}

#container-logo{
  width: 100%;
  display: grid;
  grid-template-columns: 265px 265px 265px 265px 265px;
  text-align: center;
  margin-top: 100px;
}

#contact{
  width: 100%;
  height: 800px;
  background-color: #b9b9b9;
}

#container{
  text-align: center;
  position: absolute;
  top: 500%;
  left: 50%;
  transform: translate(-50%, -50%);
}

#container img{
  width: 400px;
  height: 300px;
}

#opinion-one{
  text-align: center;
  position: absolute;
  top: 420%;
  left: 15%;
  transform: translate(-50%, -50%);
  background-color: whitesmoke;
  height: 400px;
  width: 25%;
  color: black;
}

#opinion-two{
  text-align: center;
  position: absolute;
  top: 420%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: whitesmoke;
  height: 400px;
  width: 25%;
  color: black;
}

#opinion-three{
  text-align: center;
  position: absolute;
  top: 420%;
  left: 85%;
  transform: translate(-50%, -50%);
  background-color: whitesmoke;
  height: 400px;
  width: 25%;
  color: black;
}

button:hover{
  background-color: #444554;
  color: whitesmoke;
  transition: 500ms;
}



</style>