<template>
  <div class="ImagemPrincipal">
    <div class="header">
      <div class="back">
        <div class="header-content">
          <h1 class="principal">Espaço Cerâmica</h1>
          <h3 class="sub-titulo">Cerâmica artesanal</h3>
          <div class="btn">
            <button class="botao">Compre agora</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.ImagemPrincipal {
  font-family: "Montserrat", sans-serif;
}
.header {
  background: no-repeat center/cover url("../assets/header.jpeg");
  width: 100%;
  height: calc(100vh - 150px);
  font-family: "Montserrat", sans-serif;
  z-index:1;
  position: relative;
}
.back {
  background-color: rgba(9, 9, 9, 0.454);
  width: 100%;
  height: calc(100vh - 150px);
  z-index:1;
  position: relative;
}
.header-content {
  text-align: center;
  z-index:-2 ;
  position: relative;
  top: 25vh;
}

@media screen and (min-width: 320px) and (max-width: 768px) {
  .header,
  .back {
    height: 70vh;
  }
  .principal {
    font-size: 2.7rem;
  }
  .header-content {
    z-index: 2;
    position: relative;
    top: 17vh;
  }
}
@media screen and (min-width: 769px) and (max-width: 1200px) {
  .principal {
    font-size: 4.7rem;
  }
}

@media screen and (min-width: 1201px) {
  .principal {
    font-size: 5.3rem;
  }
}
.principal {
  text-transform: uppercase;
  color: rgb(255, 255, 255);

  text-align: center;
}
.sub-titulo {
  padding-top: 30px;
  font-size: 25px;
  color: white;
}
.btn {
  padding-top: 50px;
}
.botao {
  background-color: black;
  color: white;
  font-weight: bold;
  font-size: 14px;
  height: 50px;
  width: 220px;

  border: none;
}
.botao:hover {
  background-color: rgb(123, 101, 73);
  color: white;
  font-weight: bold;
  font-size: 16px;
  height: 50px;
  width: 220px;
}
</style>