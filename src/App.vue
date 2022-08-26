<template>
  <div>
    <BaseHeader :items="items"/>
    <TheMain/>
    <BaseFooter/>
  </div>
</template>

<script>
import BaseHeader from './components/BaseHeader.vue';
import TheMain from './components/TheMain.vue';
import BaseFooter from './components/BaseFooter.vue';


export default {
  name: 'App',
  components: {
    BaseHeader,
    TheMain,
    BaseFooter
  },
   data(){
        return{
           items:[
             {"id": "1", "url": "/icons/home.png", "text": "Home"},
             {"id": "2", "url": "/icons/document.png", "text": "Pages"},
             {"id": "3", "url": "/icons/printer.png", "text": "Blog"},
             {"id": "4", "url": "/icons/cart.png", "text": "Shop"},
             {"id": "5", "url": "/icons/lab.png", "text": "Shortcode"},
             {"id": "6", "url": "/icons/chat.png", "text": "Support"},
             {"id": "7", "url": "/icons/envelope.png", "text": "Contact"}
             
           ],
        }
    },

}
</script>

<style lang="scss">
@import './assets/sass/style.scss';
@import'./assets/sass/_vars.scss';
</style>
