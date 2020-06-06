<template>

  <div class="portfolio color-theme pb-4">
    <hr class="separator">
    <h4 class="font-weight-bold py-2">My Portfolio</h4>
    <b-container>
       <b-card-group deck class="pb-3 py-3">
        <b-card
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top 
          tag="article"
          style="max-width: 30rem;"
          class="mb-2"
        >
          <b-card-body class="text-center">
            <b-card-title class="font-weight-bold">additional content</b-card-title>

            <b-card-text>
              With supporting text below as a natural lead-in to additional content.
            </b-card-text>
            
          </b-card-body>
           <template v-slot:footer>
        <small class="text-muted">Last updated 3 mins ago</small>
      </template>
        </b-card>
         <b-card
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 30rem;"
          class="mb-2"
        >
           <b-card-body class="text-center">
            <b-card-title class="font-weight-bold">below as a natural</b-card-title>

            <b-card-text>
              With supporting text below as a natural lead-in to additional content.
            </b-card-text>
          </b-card-body>
           <template v-slot:footer>
        <small class="text-muted">Last updated 3 mins ago</small>
      </template>
        </b-card>
         <b-card
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Image"
          img-top
          tag="article"
          style="max-width: 30rem;"
          class="mb-2"
        > 
          <b-card-body class="text-center">
            <b-card-title class="font-weight-bold">Card Title</b-card-title>

            <b-card-text>
              With supporting text below as a natural lead-in to additional content.
            </b-card-text>
           
          </b-card-body>
           <template v-slot:footer>
        <small class="text-muted">Last updated 3 mins ago</small>
      </template>
        </b-card>
        
       </b-card-group>
 <b-button size="lg" class="py-2 my-2" variant="danger"> <h2 class="font-weight-bold">Learn more</h2> </b-button>
    </b-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
.color-theme{
  background-color: #F7F7F7;
}
</style>
