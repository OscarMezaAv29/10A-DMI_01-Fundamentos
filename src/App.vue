<template>
  <div class="alert alert-primary" role="alert">
    Oscar Alejandro Meza Avendaño | 10° A
  </div>
  <br>
  <img class="logo" src="./assets/logo.svg" alt="Logo VUe" >
  <h1>Hola desde VueJS 3</h1>
  <hr>
  <h2 class="alert alert-success">Contador 0</h2>
  <button class="btn btn-success">+1</button>
  <button class="btn btn-success" variant="info">-1</button>
  <button class="reset btn btn-danger">Reset</button>
</template>

<style scoped>
  h1 {
    color: red;
    font-family: 'Montserrat', sans-serif;
  }

  #app .alert  {
    width: 100%;
    grid-column-start: 1;
    grid-column-end: 3;
    text-align: center;
    color: rgb(34, 117, 194);
    font-weight: 900;
  }

 .logo {
    width: 130px;
    height: 130px;
  }

  #app h1, h2 {
    width: 60vw;
    grid-column-start: 1;
    grid-column-end: 3;
    text-align: center;
  }

  #app .reset {
    grid-column-start: 1;
    grid-column-end: 3;
    text-align: center;
  }
</style>