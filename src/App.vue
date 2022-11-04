<template>
  <div>
    <AppMenu/>
    <AppImage/>
    <AppContentBottom/>
    <AppFooter/>
  </div>
</template>

<script>

import AppMenu from "@/components/AppMenu";
import AppImage from "@/components/AppImage";
import AppContentBottom from "@/components/AppContentBottom";
import AppFooter from "@/components/AppFooter";



export default {
  name: 'App',
  components: {
    AppMenu,
    AppImage,
    AppContentBottom,
    AppFooter
  },
}

</script>

<style>
body{
  margin: 0 auto;
  padding: 0;
}

button{
  width: 150px;
  height: 40px;
  background-color: coral;
  border: none;
  color: #444554;
}



</style>
