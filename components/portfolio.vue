<template>
  <v-container>
    <div id="profile-container">
      <img src="~/assets/img/dhanya3prifile.jpg" alt="my picture" />
      <h1>{{name}}</h1>

     <h3> {{description}}</h3>
    </div>

  </v-container>
</template>

<script>
export default {
  data() {
    return {
      name: "Dhanya Kunhikrishnnan",
      description: "I am a full stack developer from Australia"
    }
  }

}
</script>

<style  scoped lang ="scss">
   #profile-container{
     height: 100vh;
     img{
       max-height: 100px;
       border-radius: 100px;
     }
   }
</style>>

</style>
