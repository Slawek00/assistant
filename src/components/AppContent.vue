<template>
<div id = content>
  <div class="parallax"></div>
  <div id = "container" class="centre-container">
    <h1>Wirtualny asystent</h1>
    <h1>dla Twojej firmy</h1>
    <button type="submit">Zobacz usługi</button>
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