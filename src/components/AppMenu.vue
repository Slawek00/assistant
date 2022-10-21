<template>
<div id="container-menu">
  <div id="user-avatar">
      <h1>J</h1>
  </div>
  <div id="user-baner">
    <h2>Jarosław Wiczkowski</h2>
    <p>Wirtualny asystent</p>
  </div>
  <div id="menu-option">
    <ul>
      <li>Główna</li>
      <li>Usługi i cennik</li>
      <li>O mnie</li>
      <li>Kontakt</li>
      <li><img src=../assets/square-facebook.svg alt="Logo&facebook"></li>
      <li><img src="../assets/instagram.svg" alt="Logo&instagram"></li>
      <li><img src="../assets/linkedin.svg" alt="Logo&linkedin"></li>
    </ul>
  </div>
</div>
</template>



<script>
export default {
  name: "AppMenu"
}
</script>



<style scoped>
#container-menu{
  width: 100%;
  height: 75px;
  background-color: #444554;
}

#user-avatar{
  float: left;
  margin-left: 50px;
  margin-top: 10px;
  background-color: coral;
  border-radius: 100px;
  width: 50px;
  height: 50px;
  text-align: center;
}

#user-avatar h1{
  margin: 0 auto;
  padding: 0;
  margin-top: 5px;
  color: #db492c;
}

#user-baner{
  float: left;
  margin-left: 10px;
  position: relative;
}

#user-baner h2{ /*znajdź lepszy sposób!!!*/
  margin: 0 auto;
  padding: 0;
  margin-top: 15px;
  color: whitesmoke;
}

#user-baner p{
  margin: 0 auto;
  padding: 0;
  color: whitesmoke;
}

#menu-option{
  float: right;
}

#menu-option li{
  list-style-type: none;
  clear: both;
  display: inline-block;
  overflow: hidden;
  white-space: nowrap;
  padding-right: 20px;
  padding-top: 10px;
  color: whitesmoke;
  user-select: none;
}

#menu-option li:active{
  color: darkorange;
}

#menu-option li:hover{
  color: darkorange;
}

#menu-option img{
  height: 20px;
  width: 20px;
}

</style>