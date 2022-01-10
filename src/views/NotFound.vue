<template>

<div>

   <div class="section  bg-white border-b-2 border-black px-0 lg:px-1">

     <div class=" ">
        <Navbar 
        v-bind:web3Plug="web3Plug"
       />
     </div>


   </div>

   


      <div class=" section  mb-4">
        <div class="autospacing w-container">
          <div> File not found! </div>
          <router-link to="/"> -> Go Home</router-link>

          </div>
      </div>

  <Footer/>

    

 

</div>
</template>


<script>

  




export default {
  name: 'NotFound',
  props: [],
  components: { },
  data() {
    return {
       
    }
  },
  created: function () {
   
  }, 
  methods: {
      
  }
}
</script>
