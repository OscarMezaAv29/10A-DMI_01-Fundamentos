<script>
  export default {
    data: () => ({
      contador: 10,
    }),
    methods: {
      saludar(){
        console.log("Hola 10A");
      },
      incrementar(){
        this.contador++;
      },
      decrementar(){
        this.contador--;
      },
      resetear(){
        this.contador = 10;
      },
    }
  };
</script>

<template>
  <div class="alert alert-primary" role="alert">
    Oscar Alejandro Meza Avendaño | 10° A
  </div>
  <br>
  <img class="logo" src="./assets/logo.svg" alt="Logo VUe" width="125" height="125">
  <div class="container">
    <small><h1>Hola desde VueJS 3</h1></small>
    <hr>
    <h2>Contador {{ contador }}</h2>
    <button @click="incrementar()">+1</button>
    <button @click="decrementar()">-1</button>
    <button @click="resetear()">Reset</button>
  </div>
</template>

<style scoped>
  .container {
    text-align: center;
  }

  small {
    color: #666;
  }

  h1 {
    font-weight: bolder;
  }

  h2 {
    font-size: 2.5rem;
  }

  button {
    cursor: pointer;
    font-size: 1.5rem;
    margin: 0px 8px;
  }
  /*
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
  }*/
</style>