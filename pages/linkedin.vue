<template> 
  <v-container>
      <div id="component-profile" class="d-flex flex-column justify-center align-center">
          <img src="~assets/images/linkedin.jpg">
          <h1>{{ name }}</h1>
          <p>{{ description }}</p>
          <div class="d-flex justify-spaced-around">
              <a href="https://www.linkedin.com/in/firdesbeyzanursenocak/" target="_blank" title="Linkedin"><i class="fab fa-linkedin mx-2"></i></a>
          </div>
          
      </div>
  </v-container>
</template>

<script>
export default {
data(){
  return{
      name: 'Firdes Beyzanur Senocak',
      description: 'Hello again, this is the page with the link of my Linkedin account. :)'
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
  color: rgb(255, 255, 255);
 }
}

</style>