<template>
  <div>
  <div class="container text-center">
    <h2>Welcome to Sunridge</h2>
    <p>Located in Weber County, Utah, Sunridge is a home away
      from home <br> for owners seeking the solitude and scenery  of
      the Wasatch mountains.</p>
    <p>Tucked away behind Powder Mountain Ski Resort,
       Sunridge is just the place <br> for those hoping to
      "get away from it all" and get close to nature!</p>
    <img class="hr" src="../assets/photos/vines2.png" width="600" alt="">
  </div>

    <div class="container link ">
      <div class="row">
        <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >

            <ul >
              <router-link to="/Home/Resources" active-class="active" tag="li"><img class="info" src="../assets/photos/rules.png" width="380px" alt=""></router-link>
            </ul>

        </div>

        <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >

              <ul>
                <router-link to="/Home/Classifies" active-class="active" tag="li"><img class="info3" src="../assets/photos/ads.png" width="280px" alt=""> </router-link>
              </ul>


        </div>

        <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >

              <ul >
                <router-link to="/Home/Calender" active-class="active" tag="li"><img class="info2" src="../assets/photos/calendar.png" width="180px" alt=""></router-link>
              </ul>


        </div>

      </div>
    </div>
  </div>
</template>

<style>

  .link{
  padding-top: 50px;
  }

  .dates{
    padding-top: 20px;
  }
  li{
    list-style-type: none;
    cursor: pointer;
  }

  @media screen and (max-width: 411px) {
    .hr{
      width: 300px;
    }
    .info{
      margin-top: 20px;
      margin-left: 10px;
      width: 250px;
    }
    .info2{
      width: 150px;
      margin-left: 10px;
    }
    .info3{
      width: 200px;
      margin-left: 10px;
    }
  }

  @media screen and (max-width: 800px) {
    .hr{
      width: 300px;
    }
    .info{
      margin-top: 20px;
      margin-left: 10px;
      width: 250px;
    }
    .info2{
      width: 150px;
      margin-left: 10px;
    }
    .info3{
      width: 200px;
      margin-left: 10px;
    }
  }

</style>
