<script setup>

</script>

<template>
<header>
  <nav>
    <div>
        <a href="index.html">IFbooks</a>
        <hr>
        <p>Apreço a leitura</p>
    </div>
    <div>
      <input type="text" placeholder="Pesquisar"><i class="fa-solid fa-magnifying-glass"></i>
    </div>
    <div>
      <ul class="nav">
        <li><a href="#">Termos</a></li>
        <li><a href="#">Equipe</a></li>
        <li><a href="#">Envio</a></li>
        <li><a href="#">Devolução</a></li>
      </ul>
    </div>
    <div>
      <ul class="icons">
        <li><a href="#"><span class="fa-solid fa-bag-shopping"></span></a></li>
        <hr>
        <li><a href="#"><span class="fa-solid fa-heart"></span></a></li>
        <hr>
        <li><a href="#"><span class="fa-solid fa-user"></span></a></li>
      </ul>
    </div>
  </nav>
</header>
</template>

<style scoped>
/*=======================================================
                    Header
=======================================================*/
header{
  width: 75%;
  margin: 30px auto;
}
nav, ul{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
div:first-child{
  display: flex;
}
div:first-child a{
  font-size: 20px;
  color: black;
  text-decoration: none;
  margin: 0 10px 0 0;
}
div:first-child p{
  color: #27AE60;
  margin: 0 0 0 10px;
  width: 50%;
  text-align: left;
  line-height: 18px;
}

div input{
  padding: 10px 7vw 10px 7px;
  background-color: #F1F1F1;
  color: #B8B8B8;
  margin: 0 10px 0 0;
  border: none;
}
span{
  font-size: 20px;
  align-items: center;
}
div ul li{
  margin: 0 2vw 0 0;
  list-style-type: none;
}
ul.nav li a{
  font-size: 15px;
}
ul.nav li:not(:last-child) a{
  margin: 0 2vw 0 0;
}


ul.icons li{
  margin: 0 15px 0 20px;
}

ul.icons li a span{
  font-size: 20px;
}





</style>
