<template>
  <footer class="card-footer bg-dark">
    <b-row class="py-3 text-white">
      <b-col md="5" class="ml-md-auto">
          <h6 class="font-weight-bold">Contactame</h6>
           <form >
            <div class="form-row">
              <div class="form-group col-md-6">
                <label class="sr-only" for="inputEmail4">Email</label>
                <input disabled type="email" class="form-control" id="inputEmail4" />
              </div>
              <div class="form-group col-md-6">
                <label class="sr-only" for="inputPassword4">Password</label>
                <input disabled type="password" class="form-control" id="inputPassword4" />
              </div>
            </div>
            <div class="form-group">
              <label class="sr-only" for="exampleFormControlTextarea1">Example textarea</label>
              <textarea disabled class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
            </div>
            <button class="btn btn-primary">Enviar</button>
          </form>
      </b-col>
     

      <b-col cols="6" class="align-self-center">
        <h6 class="font-weight-bold">¡Sigueme!</h6>
        <b-avatar class="mr-2" variant="primary"
          ><font-awesome-icon :icon="['fab', 'facebook']" size="2x"
        /></b-avatar>
        <b-avatar variant="danger"
          ><font-awesome-icon :icon="['fab', 'instagram']" size="2x"
        /></b-avatar>
      </b-col>
    </b-row>
    <b-row>
      <div class="text-white mx-auto ">
        <p class="align-middle mt-2">&copy; Untitled. All rights reserved.</p>
      </div>
    </b-row>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style></style>
