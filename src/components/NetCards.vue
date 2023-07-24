<template>
    <div class="cards">
         <CardNet v-for="filme in filmes" :key="filme.id" :fotolink="`http://127.0.0.1:8000/storage/${filme.imagem}`"></CardNet>
    </div>
</template>

<script>
    import CardNet from './CardNet.vue';
    
    export default {

        name:'CardsNet',
        components:{
            CardNet
        },
        props:{
          filmes:{
            type:Array,
          }
        }

   
    }


</script>

<style scoped>
.cards{
    display: flex;
    align-items: center;
    
}


</style>


  /*   data(){
        return {
           filmes: [
                {
                  "id":"0001",
                  "linkfoto":"https://occ-0-1123-1740.1.nflxso.net/dnm/api/v6/X194eJsgWBDE2aQbaNdmCXGUP-Y/AAAABWKiR9Q85utpIWjVohEXaVS4bzq4IM53xV8Ai2v7fExeQbCftSmvN25rrqKMCjKTzvwUQeCkGUxuy_iVMXioriGxM_B_cqLftscH9WjshTIFwGPBq4frmS_zG3aHtxBZuK2qP1k7meO1CwDH9zM6_yBSZMoLp4dibjX-75BOeCqawrcQvXP3yM9SmMNeJmE.jpg?r=4c9" 
                },
                {
                  "id":"0002",
                  "linkfoto":"https://occ-0-1123-1740.1.nflxso.net/dnm/api/v6/X194eJsgWBDE2aQbaNdmCXGUP-Y/AAAABWKiR9Q85utpIWjVohEXaVS4bzq4IM53xV8Ai2v7fExeQbCftSmvN25rrqKMCjKTzvwUQeCkGUxuy_iVMXioriGxM_B_cqLftscH9WjshTIFwGPBq4frmS_zG3aHtxBZuK2qP1k7meO1CwDH9zM6_yBSZMoLp4dibjX-75BOeCqawrcQvXP3yM9SmMNeJmE.jpg?r=4c9" 
                },
                {
                  "id": "0003",
                  "linkfoto":"https://occ-0-1123-1740.1.nflxso.net/dnm/api/v6/X194eJsgWBDE2aQbaNdmCXGUP-Y/AAAABWKiR9Q85utpIWjVohEXaVS4bzq4IM53xV8Ai2v7fExeQbCftSmvN25rrqKMCjKTzvwUQeCkGUxuy_iVMXioriGxM_B_cqLftscH9WjshTIFwGPBq4frmS_zG3aHtxBZuK2qP1k7meO1CwDH9zM6_yBSZMoLp4dibjX-75BOeCqawrcQvXP3yM9SmMNeJmE.jpg?r=4c9"   
                },
           ]
        }
    },*/