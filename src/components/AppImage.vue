<template>
<div id = content>
  <div class="parallax"></div>
  <div id = "container" class="centre-container">
    <h1>Wirtualny asystent</h1>
    <h1>dla Twojej firmy</h1>
    <button type="submit">Zobacz usługi</button>
  </div>
  <div id="container-box">
    <div id="box-about-me" class="centre-box">
      <img src="../assets/cheerful-young-caucasian-businessman.jpg" alt="bissnesman">
      <div id="container-text-about">
        <h1>Mam na imię Jarosław,<br>jestem profesjonalnym<br>asystentem biurowym</h1>
        <p>Lorem ipsum dolor sit amet. Est galisum aspernatur aut quam dolorem qui laborum temporibus aut natus quia qui nobis atque!
          Qui dolorem eius 33 laborum eius nam autem distinctio hic itaque rerum ad nobis aliquam.
          A facere odio et omnis ipsum aut tempore autem non fugit nesciunt.
          Qui architecto minima a enim iste qui excepturi mollitia.</p>
        <p>Et nihil asperiores At obcaecati tempore et debitis provident hic tenetur excepturi rem distinctio dignissimos.
          Non placeat possimus id voluptatem facilis sed enim tempore est architecto odit sit placeat expedita.
          Qui expedita dignissimos et nihil alias sed dolorem saepe non explicabo dignissimos ut veniam placeat id optio totam et omnis minima.</p>
      </div>
    <button type="submit">Czytaj dalej</button>
    </div>
  </div>
    <div id="container-services">
      <h1>Jak mogę Ci pomóc?</h1>
      <div id="container-list">
        <ul>
          <li class="border-right">
            <img src="../assets/folder-solid.svg" alt="folder">
            Obsułga administracyjna
          </li>
          <li class="border-right">
            <img src="../assets/comments-solid.svg" alt="client">
            Obsługa klienta
          </li>
          <li>
            <img src="../assets/calendar-days-regular.svg" alt="calendar">
            Zarządzanie projektami
          </li>
          <li class="border-right">
            <img src="../assets/hashtag-solid.svg" alt="social_media">
            Zarządzanie social mediami
          </li>
          <li class="border-right">
            <img src="../assets/file-contract-solid.svg" alt="contract">
            Dane i badania
          </li>
          <li>
            <img src="../assets/user-solid.svg" alt="avatar">
            Osobisty asystent
          </li>
        </ul>
      </div>
      <button type="submit">Zobacz plan</button>
    </div>
</div>
</template>

<script>
export default {
  name: "AppContent"
}
</script>

<style scoped>



#container{
  position: absolute;
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

#container-box{
  width: 100%;
  height: 200px;
  background-color: white;
}

#container-box button{
  margin-top: 100px;
  margin-left: 100px;
}

#box-about-me{
  width: 1000px;
  height: 500px;
  background-color: white;
  border: outset;
}

#box-about-me img{
  width: 350px;
  height: 400px;
  margin-top: 50px;
  margin-left: 50px;
  float: left;
}

#container-text-about{
  margin-top: 20px;
  width: 500px;
  height: 300px;
  float: right;
}

#container-services{
  width: 100%;
  height: 700px;
  text-align: center;
  margin-top: 300px;
}

#container-services button{
  margin-top: 100px;
}


#container-list ul{
  margin-left: 23%;
  list-style-type: none;
  display: grid;
  grid-template-columns: 250px 250px 250px;
  grid-template-rows: 200px 200px;
}

#container-list li:nth-child(0){
  grid-column-start:1;
  grid-column-end: 2;
  grid-row-start: 1;
  grid-row-end: 1;
}

#container-list li{
  margin-top: 50px;

}

#container-list li img{
  width: 35px;
  height: 35px;
  margin-right: 10px;
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

.centre-box{
  position: absolute;
  top: 110%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.border-right{
  border-right: 2px solid #444554;
}

</style>