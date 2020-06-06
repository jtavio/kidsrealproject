<template>
  <div id="intro">
    <b-container class="py-5">
      <div class="card-deck">
        <div class="card shadow-sm rounded">
          <img src="../../assets/matematicas.svg" class="icon-math mx-auto icons-kids" alt=""> 
          <div class="card-body">
            <h5 class="card-title font-weight-bolder">Pre-calculo</h5>
            <p class="card-text">
              This is a longer card with supporting text below as a natural
              lead-in to additional content. This content is a little bit longer.
            </p>
            <p class="card-text">
              <a href="#" class="btn btn-primary">Saber más...</a>
            </p>
          </div>
        </div>
        <div class="card shadow-sm rounded">
          <font-awesome-icon :icon="['fas', 'book-reader']" size="5x" class="icons-kids mx-auto color-pink-icons"
        />
         
          <div class="card-body">
            <h5 class="card-title font-weight-bolder">Pre-lectura</h5>
            <p class="card-text">
              La lectura es una herramienta importante y que los niños la puedan adquirir, mediante la estimación en la cual se inicia al niño en el reconocimiento de las vocales...
            </p>
            <p class="card-text">
             <router-link to="/readme" class="btn btn-primary">Saber más...</router-link>
            </p>
          </div>
        </div>
        <div class="card shadow-sm rounded">
          <div class="d-flex mx-auto color-blue-icons">
            <font-awesome-icon :icon="['fas', 'signature']" size="2x" class="icons-kids m-top-8"/>
            <font-awesome-icon :icon="['fas', 'pencil-alt']" size="5x" class="icons-kids "/>
          </div>
        
          <div class="card-body">
            <h5 class="card-title font-weight-bolder">Pre-escritura</h5>
            <p class="card-text">
              This is a wider card with supporting text below as a natural lead-in
              to additional content. This card has even longer content than the
              first to show that equal height action.
            </p>
            <p class="card-text">
              <a href="#" class="btn btn-primary">Saber más...</a>
            </p>
          </div>
        </div>
      </div>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "intropage"
};
</script>

<style>
.color-blue-icons{
  color:#32B1CC ;
}
.color-pink-icons{
  color:#E9686A;
}
.icons-kids{
    
    margin-top: 30px;
}
.separator{
    background-color: #cccccc;
}
.m-top-8{
  margin-top: 80px!important;
}
.icon-math{
  width:23%
}
/* .card{
    -moz-box-shadow: -2px 1px 17px #242424;
    -webkit-box-shadow: -2px 1px 17px #242424;
    box-shadow: -2px 1px 17px #242424;
} */
</style>
