<template>
<AppMenu/>
  <AppContent/>
</template>

<script>

import AppMenu from "@/components/AppMenu";
import AppContent from "@/components/AppContent";

export default {
  name: 'App',
  components: {
    AppMenu,
    AppContent
  },
}

</script>

<style>

body{
  margin: 0;
  padding: 0;
}

</style>
