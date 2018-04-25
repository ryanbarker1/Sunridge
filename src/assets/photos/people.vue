<template>
  <div>
    <router-link to="/Gallery" class="navbar-brand text-black">Back</router-link>
    <div class="container text-center">
      <h2>People</h2>
      <img class="hr" src="../photos/vines2.png" width="600" alt="">
    </div>

    <div class="images">
      <div class="container ">
        <div class="row">

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group  src="./peopleimage/apr2003.jpg">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>


          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group  src="./peopleimage/bigfish.jpg"  alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>


          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group  src="./peopleimage/butch1.jpg"    alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group   src="./peopleimage/butch2.jpg"  alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group   src="./peopleimage/butch_goodbye.jpg"  alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group   src="./peopleimage/ginaRowe.jpg"  alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>

        </div>
      </div>


      <div class="container">
        <div class="row">
          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group   src="./peopleimage/grant_cabin.jpg"  alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group   src="./peopleimage/grants_up_2003.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>

          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group="{title: 'dddddd'}"   src="./peopleimage/LeftFork.jpg"   alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>

        </div>
      </div>

<div class="container">
  <div class="row">
    <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
      <div class="thumbnail resize">
        <img v-img:group   src="./peopleimage/lostDog.jpg"  alt="">
      </div>
    </div>

    <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
      Caption: <br> Date: <br> Photographer
    </div>

    <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
      <div class="thumbnail resize">
        <img v-img:group   src="./peopleimage/mechamcabin600w.jpg" alt="">
      </div>
    </div>

    <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
      Caption: <br> Date: <br> Photographer
    </div>

    <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
      <div class="thumbnail resize">
        <img v-img:group   src="./peopleimage/RTbeaut_day.jpg"  alt="">
      </div>
    </div>

    <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
      Caption: <br> Date: <br> Photographer
    </div>

  </div>
</div>

      <div class="container">
        <div class="row">
          <div class="col-xs-8 col-sm-2 col-md-2 col-lg-2 col-xl-2">
            <div class="thumbnail resize">
              <img v-img:group   src="./peopleimage/TamsSecretCase.jpg" alt="">
            </div>
          </div>

          <div class="col-xs-4 col-sm-2 col-md-2 col-lg-2 col-xl-2 text">
            Caption: <br> Date: <br> Photographer
          </div>

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
  .images{
    padding-top: 20px;

  }

  @media screen and (max-width: 420px) {
    .hr {
      width: 300px;
    }
    .text{
      margin: 0 50px;
  }
    .resize{
      margin: 0 120px;
    }
  }

  @media screen and (max-width: 1200px) {
    .text{
      padding: 0 10px 0 40px;
    }
  }

  @media screen and (max-width: 1000px) {
    .text{
      padding: 0 10px 0 80px;
    }
  }

</style>
