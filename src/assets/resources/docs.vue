<template>
<div>
  <div class="container text-center">
    <h2>Docs &amp; Forms</h2>
    <img class="hr" src="../photos/vines2.png"width="600" alt="">
  </div>

  <div class="container link text-center">
    <div class="row">
      <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >
            <ul class="map">
              <router-link to="/Home/Resources" active-class="active" tag="li"><img class="info4" src="../photos/rules.png" width="350px" alt=""></router-link>
            </ul>
      </div>

      <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >
            <ul class="map" style="margin-left: 125px;">
              <router-link to="/Home/docs/forms" active-class="active" tag="li"><i class="far fa-file fa-8x "></i><br>Forms</router-link>
            </ul>
      </div>

      <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >
            <ul class="map">
              <router-link to="/Map" active-class="active" tag="li"><img class="info5" src="../photos/map.png" width="180px" alt=""></router-link>
            </ul>

      </div>



    </div>
  </div>

</div>
</template>


<style>
  .map{
  list-style: none;
    font-size: larger;
    margin-left: 50px;
  }

  .link{
    margin-top: 50px;
  }

  @media screen and (max-width: 400px) {
    .map{
      margin: 0;
    }
      .hr{
        width: 300px;
      }

      .far{
      margin-right: 20px;
      }

    .info4{
      margin-top: 20px;
      margin-left: 20px;
      width: 250px;
    }
    .far{
      width: 50px;
      margin-right: 20px;
    }
    .info5{
      width: 150px;
      margin-left: 50px;
    }

  }
</style>
