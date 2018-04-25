<template>
  <div>
    <router-link to="/Home/Classifies" class="navbar-brand text-black">Back</router-link>
    <div class="container text-center">
      <h2>For Sale</h2>
      <img class="hr" src="../photos/vines2.png" width="600" alt="">
    </div>


    <div class="container-fluid text-center land">
      <div class="row">

        <div class="col-xs-12 col-sm-4 ">
          <img src="http://via.placeholder.com/150x150" alt="Land">
        </div>

        <div class="col-xs-12 col-sm-6">
              <p class="card-text">For Sale - $45,900 <br>
                Lot #51 Sunridge Highlands <br>
                2.23 Acres <br>
                7539 N. Jim Bridger Drive
              </p>
              <p>Beautiful acreage with mature aspen trees. Water hookup and cleared area for trailer/future cabin. <br>
                Contact Lisa Turner, Agent with Better Homes & Gardens Real <br> Estate-Franklin Group (385) 424-1222 or
                <a href="mailto:lisa@utahluxegroup.com">email: lisa@utahluxegroup.com</a></p>

        </div>

      </div>
      </div>

  </div>
</template>

<style>
  .land{
    margin-top: 40px;
  }
  @media screen and (max-width: 400px) {
    .hr{
      width: 300px;
    }
    .info{
      margin-top: 20px;
      margin-left: 20px;
      width: 180px;
    }
    .info2{
      width: 100px;
      margin-left: 20px;
    }
    .info3{
      width: 150px;
      margin-left: 20px;
    }
  }
</style>
