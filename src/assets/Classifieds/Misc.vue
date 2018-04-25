<template>
  <div>
    <router-link to="/Home/Classifies" class="navbar-brand text-black">Back</router-link>
    <div class="container text-center">
      <h2>Cabins For Sale</h2>
      <img class="hr" src="../photos/vines2.png" width="600" alt="">
    </div>


      <div class="container text-center cabins">
        <div class="row">

          <div class="col-xs-12 col-sm-6">
            <img src="http://via.placeholder.com/150x150" alt="Land">
          </div>

          <div class="col-xs-12 col-sm-2">
            <p class="card-text"> Cabins For Sale
            </p>

          </div>

        </div>

    </div>

  </div>
</template>

<style>
  .cabins{
    margin-top: 20px;
  }
  @media screen and (max-width: 400px) {
    .hr {
      width: 300px;
    }
  }
</style>
