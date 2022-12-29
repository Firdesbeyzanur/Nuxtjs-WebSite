<template> 
  <v-container>
      <div id="component-profile" class="d-flex flex-column justify-center align-center">
          <img src="~assets/images/stackoverflow.jpg">
          <h1>{{ name }}</h1>
          <p>{{ description }}</p>
          <div class="d-flex justify-spaced-around">
              <a href="https://stackoverflow.com/" target="_blank" title="Stack OverFlow"><i class="fab fa-stack-overflow mx-2"></i></a>
          </div>
          
      </div>
  </v-container>
</template>

<script>
export default {
data(){
  return{
      name: 'Firdes Beyzanur Senocak',
      description: 'Hello again, this is the page with the link of my Stack OverFlow account. :)'
  }
},
}
</script>

<style scoped lang="scss">
#component-profile{
 height: 100vh;
 img {
  max-height: 100px;
  border-radius: 100px;
 }
 i {
  font-size: 44px;
  color: rgb(216, 200, 112);
 }
}

</style>