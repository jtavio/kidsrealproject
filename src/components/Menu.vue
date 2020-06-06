<template>
  <div class="my-4">
      <h1 class="font-weight-bold"> <router-link to="/">PSICOKIDS</router-link> </h1>
        <div>
          <b-navbar toggleable="md">
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
              <!-- Right aligned nav items -->
              <b-navbar-nav class="mx-auto">
                <!-- <b-nav-form>
                  <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
                  <b-button size="sm" class="my-2 my-sm-0" type="submit">Search</b-button>
                </b-nav-form> -->
                
                  <b-nav-item-dropdown>
                    <!-- Using 'button-content' slot -->
                    <template v-slot:button-content>
                      <em>Motricidad fina</em>
                    </template>
                    <b-dropdown-item href="#">Rasgado Libre</b-dropdown-item>
                    <b-dropdown-item href="#">Rasgado en tira</b-dropdown-item>
                    <b-dropdown-item href="#">Ensartar</b-dropdown-item>
                    <b-dropdown-item href="#">Colorear respetando limites</b-dropdown-item>
                    <b-dropdown-item href="#">Trazado de figuras geometricas</b-dropdown-item>
                    <b-dropdown-item href="#">Encajar</b-dropdown-item>
                    <b-dropdown-item href="#">Armar rompe cabeza</b-dropdown-item>
                  </b-nav-item-dropdown>
                <b-nav-item href="#">Motrocidad gruesa</b-nav-item>
                <b-nav-item href="#">Memoria</b-nav-item>
                <b-nav-item href="#">Habilidades de la vida diaria</b-nav-item>
                <b-nav-item href="#">Lenguaje y Comunicación</b-nav-item>
              

              </b-navbar-nav>
            </b-collapse>
          </b-navbar>
        </div>
    </div>
</template>

<script>
export default {
    name:'menu'

}
</script>

<style>

</style>