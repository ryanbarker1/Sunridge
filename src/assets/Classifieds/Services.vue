<template>
  <div>

    <router-link to="/Home/Classifies" class="navbar-brand text-black">Back</router-link>
    <div class="container text-center">
      <h2> Misc &amp; Services</h2>
      <img class="hr" src="../photos/vines2.png" width="600" alt="">
    </div>


    <div class="container text-center">
      <div class="row">

        <div class="col-md-12">
          <div class="card">
            <div class="card-block p-3">
              <p class="card-text">
              <p>Looking for a Cargo Trailer?</p> Come to Young Wells Cargo in  <p>Layton Utah
              570 North Main <br>
              Mention you have a lot in Sunridge and receive a discount.
              Call Randy Taylor 801-807-8647 <br>
              <a href="mailto:randy.taylor@youngwellscargo.com">email randy.taylor@youngwellscargo.com</a>
            </p>
            </div>
          </div>
          <hr>
        </div>
      </div>
    </div>

      <div class="container">
        <div class="row">
          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group src="../photos/class6.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Roofing
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group src="../photos/class7.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Excavating
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group src="../photos/class8.jpg" alt="fffff" >
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
          Real Estate
          </div>

        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group src="../photos/class1.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
          Feeders
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img  v-img:group src="../photos/class2.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
           Red Rock Grill
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group src="../photos/class3.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Sunridge Swag
          </div>

        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group src="../photos/class4.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
           Trading Post
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group src="../photos/class5.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Aerial Superior Design
          </div>

        </div>
      </div>



  </div>
</template>


<style>
  .resize{
    width: 125px;
    margin-left: 50px;
  }


  @media screen and (max-width: 400px) {
    .hr {
      width: 300px;
    }
  }
</style>
