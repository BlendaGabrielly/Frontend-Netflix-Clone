<template>

   
        <div class="card">
            
            <img :src="fotolink" alt="">
            
               
            <div class="card-modal">

            </div>
        </div>
   
    
   


    
</template>

<script>


export default {

    props:{
        fotolink: String,   

    }, 
    
    methods:{
        

    }
}
</script>

<style scoped>
.card{

    margin: 5px;
    border-radius: 20px;
    width:300px ;
     transition: 400ms ease-out;
}

 .card img {
    
    border-radius: 5px;
    max-width: 100%;
   
}

.card:hover{
    transition: 300ms ease-out;
    width: 500px;
  
    
}

.card-Modal{
    position: fixed;
    background-color: rgba(0, 0, 0, 0.06);
    width: 90%;
    height: 90%;
}

</style>