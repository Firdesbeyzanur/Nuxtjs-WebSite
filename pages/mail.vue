<template> 
  <v-container>
      <div id="component-profile" class="d-flex flex-column justify-center align-center">
          <img src="~assets/images/mail.jpg">
          <h1>{{ name }}</h1>
          <p>{{ description }}</p>
          <div class="d-flex justify-spaced-around">
              <a href="mailto:beyzanursenocak@gmail.com" target="_blank" title="Mail"><i class="fas fa-envelope mx-2"></i></a>
          </div>
          
      </div>
  </v-container>
</template>

<script>
export default {
data(){
  return{
      name: 'Firdes Beyzanur Senocak',
      description: 'Hello again, this is the page with the link of my Mail account. :)'
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
  color: brown;
 }
}

</style>