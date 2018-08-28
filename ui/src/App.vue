<template lang="pug">
  #app
    .container-fluid 
      .row  
        <Sidebar />
        <ListArea />
        <DetailsArea />
</template>


<style src="./assets/sass/style.scss" lang="scss"></style>

<script>
import Sidebar from './components/Sidebar.vue'
import ListArea from './components/ListArea.vue'
import DetailsArea from './components/DetailsArea.vue'

export default {
  name: 'app',
  components: {
    Sidebar,
    ListArea,
    DetailsArea
  }
}
</script>
