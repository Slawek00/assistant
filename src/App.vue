<template>
<AppMenu/>
  <AppContent/>
</template>

<script>

import AppMenu from "@/components/AppMenu";
import AppContent from "@/components/AppContent";
//import AppFooter from "@/components/AppFooter";

export default {
  name: 'App',
  components: {
    AppMenu,
    AppContent,
    //AppFooter
  },
}

</script>

<style>

body{
  margin: 0;
  padding: 0;
}

</style>
