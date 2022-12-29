<template> 
    <v-container>
        <div id="component-profile" class="d-flex flex-column justify-center align-center">
            <img src="~assets/images/images.jpg">
            <h1>{{ name }}</h1>
            <p>{{ description }}</p>
            <div class="d-flex justify-spaced-around">
                <a href="https://stackoverflow.com/" target="_blank" title="Stack OverFlow"><i class="fab fa-stack-overflow mx-2"></i></a>
                <a href="https://github.com/Firdesbeyzanur?tab=repositories" target="_blank" title="GitHub"><i class="fab fa-github mx-2"></i></a>
                <a href="https://medium.com/@FirdesBeyzanurSenocak" target="_blank" title="Medium"><i class="fab fa-medium mx-2"></i></a>
                <a href="https://www.linkedin.com/in/firdesbeyzanursenocak/" target="_blank" title="Linkedin"><i class="fab fa-linkedin mx-2"></i></a>
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
        description: 'I am a Junior Frond-End Developer from Turkiye :)'
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
    color: palevioletred;
   }
}

</style>