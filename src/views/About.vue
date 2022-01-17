<template>
  <div>
    <div>
        <HeaderComponent />
    </div>
    <div>
        Sobre nos
    </div>
    <div>
        <FooterComponent />
    </div>
  </div>
  
</template>

<script>
import FooterComponent from '../components/FooterComponent.vue'
import HeaderComponent from '../components/HeaderComponent.vue'
/* import BodyComponent from '../components/BodyComponent.vue'
 */
export default {
    name: 'About',
    components: {
        FooterComponent,
        HeaderComponent,
       /*  BodyComponent */
    }

}
</script>

<style scoped>

.home-body {
  display: flex;
  flex-direction: row;
  text-align: center;
}

</style>