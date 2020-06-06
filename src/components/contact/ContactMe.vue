<template>
  <div>
    <b-row>
      <b-col md="5" class="ml-md-auto">
        <h6 class="font-weight-bold">Contactame</h6>
        <form>
          <div class="form-row">
            <div class="form-group col-md-6">
              <label class="sr-only" for="inputEmail4">Email</label>
              <input
                disabled
                type="email"
                class="form-control"
                id="inputEmail4"
              />
            </div>
            <div class="form-group col-md-6">
              <label class="sr-only" for="inputPassword4">Password</label>
              <input
                disabled
                type="password"
                class="form-control"
                id="inputPassword4"
              />
            </div>
          </div>
          <div class="form-group">
            <label class="sr-only" for="exampleFormControlTextarea1"
              >Example textarea</label
            >
            <textarea
              disabled
              class="form-control"
              id="exampleFormControlTextarea1"
              rows="3"
            ></textarea>
          </div>
          <button class="btn btn-primary">Enviar</button>
        </form>
      </b-col>
      <b-col>
          <h2>Acerca de mi </h2>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
