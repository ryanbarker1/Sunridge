<template>
  <div>
    <div class="container text-center">
      <h2>Sunridge Classifieds:</h2>
      <img class="hr" src="../assets/photos/vines2.png" width="600" alt="">
    </div>


    <div class="container text-center ads">
      <div class="row">
        <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >
          <ul>
            <router-link to="/Home/Classifieds/ForSale" active-class="active" tag="li"><img class="forsale" src="../assets/photos/land.png" width="150px" alt="Land For Sale"></router-link>
          </ul>
        </div>

        <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >
          <ul>
            <router-link to="/Home/Classifieds/Misc" active-class="active" tag="li"><img class="cabin" src="../assets/photos/cabinforsale.png" width="150px" alt="Cabins for sale"></router-link>
          </ul>
        </div>

        <div class="col-xs-12 col-sm-4 col-md-4 col-lg-4 col-xl-4" >
          <ul>
            <router-link to="/Home/Classifieds/Service" active-class="active" tag="li"><img class="misc" src="../assets/photos/ad.png" width="150px" alt="Misc & Service"></router-link>
          </ul>
        </div>

      </div>
    </div>

    <div class="add">
    <div class="container text-center">
      <div class="row">

        <div class="col-xs-12 col-sm-12 col-md-12 col-lg-12 col-xl-12" >

              <p>
             If you would like to place a free ad on the Sunridge. <br>
                Classified's page, send your ad, along with your name <br>
                and Sunridge Lot number to <br>
                <a href="mailto:webmaster@sunridge.info">Web Master</a>
              </p>
        </div>

      </div>
      </div>
    </div>

  </div>
</template>

<style>
  .ads{
    margin: 50px 0 0 160px;
  }

  li{
    list-style-type: none;
  }

  .add{
    margin-top: 50px;
  }

  @media screen and (max-width: 400px) {

    .ads{
      margin: 50px 0 0 0;
    }
    .hr{
      width: 300px;
    }
    .forsale{

      margin: 20px 0 0 0;
      width: 150px;
    }
    .cabin{
      width: 150px;
      margin-right: 20px;
    }
    .misc{
      width: 150px;
      margin-right: 20px;
    }

  }

</style>
