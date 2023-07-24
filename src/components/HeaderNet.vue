<template>
<header  class="mynav">

        <div class="menu_navegacao">

            <div class="nav_l">
                <a href="/" id="logo"><img src="../assets/netflix.svg" alt=""></a>

                <ul class="navegacao_p">
                    <li><a href="/">Início</a></li>
                    <li><a href="/">Series</a></li>
                    <li><a href="/">Filmes</a></li>
                    <li><a href="">Bombando</a></li>
                    <li><a href="/">Minha Lista</a></li>
                </ul>
            </div>
        
            <div class="nav_r">

                <div class="navegacao_s">
                    <span class="search_button">
                        <img src="../assets/icons/search_button.png" alt="">
                    </span> 
        
                    <a href="/">Infantil</a>
        
                    <div class="user_profile">

                        <img src="../assets/profile_img.png" alt="">
                        <span class="triangle"></span>
                    </div>
        
                </div>

            </div>

        
        </div>
        

    </header>


    
</template>

<script>



export default {
    //name:'HeaderNet',
    
}
</script>

<style scoped>
header {

    width: 100%;
    height: 11vh;
    display: flex;
    background-color: #141414;
    
    position: fixed;
    z-index:99;;


}

.menu_navegacao{
    /*background-color: var(--NRed);*/

    width: 92%;
    margin: 0 auto;

    display: flex;
    align-items: center;
    justify-content: space-between;

}


.menu_navegacao a{

    text-decoration: none;

    color: white;
    font-size: 14px;

}

.menu_navegacao .nav_l {

    display: flex;
    align-items: center;
    width:50%;
}


.menu_navegacao .nav_r{

    width: 50%;

    display: flex;
    align-items: center;
    justify-content: flex-end;
}

.menu_navegacao .nav_r .navegacao_s {

    max-width: 50%;
    display: flex;
    
}

.menu_navegacao .nav_r a, 
.menu_navegacao .nav_r img,
.menu_navegacao .nav_r user_profile {

    margin:auto 15px;
}

.menu_navegacao .nav_r .search_button{
    display: flex;
}

.menu_navegacao .nav_r .search_button img{
    width: 20px;
   
}

.menu_navegacao .nav_r .navegacao_s .triangle {
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 5px 5px 0 5px;
    border-color: #fff transparent transparent transparent;
}




#logo {

    display: flex;
    flex-direction: row;
    align-content: center;
    justify-content: center;
    align-items: center;

}

#logo img {

    width: 7vw;
}


.menu_navegacao .nav_l ul{
    margin-left: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    list-style: none;
}

.menu_navegacao .nav_l ul li{

    margin-left: 20px;
    display: flex;
    align-content: center;
    align-items: center;
    justify-content: center;
   
}

.menu_navegacao .nav_l ul li a:hover{

    transition: 2ms;
    color: rgba(0.0.0,0.0);
}


</style>











