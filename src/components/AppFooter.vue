<template>
  <div id = "footer">
      <p class="left-p">Polityka prywatności</p>
      <br>
      <p class="right-p">Polityka plików cookie</p>
      <br>
      <p class="center-p">&copy;2022 Jarosław Witkowski</p>
  </div>
</template>

<script>
export default {
  name: "AppFooter"
}
</script>

<style scoped>
    #footer{
      width: 100%;
      height: 100px;
      background-color: #444554;
      text-align: center;
      color: white;
    }

    p{
      margin: 0;
      padding: 0;
    }

</style>