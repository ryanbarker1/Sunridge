<template>
  <div>
    <router-link to="/Home/docs" class="navbar-brand text-black">Back</router-link>
    <div class="container text-center">
      <h2>Maps</h2>
      <img class="hr" src="../assets/photos/vines2.png" width="600" alt="">
    </div>



    <div class="container text-center icon">
      <div class="row">
        <div class="col-xs-12 col-sm-4">
          <a href="http://sunridge.info/docs/SunridgeMapMay2008.pdf" target="_blank"><i class="far fa-map fa-10x"></i>
            <br> Printable Map</a>
        </div>

        <div class="col-xs-12 col-sm-4">
          <a href="http://sunridge.info/docs/SUNRIDGE-LOTS-MAP.pdf" target="_blank"><i class="fas fa-map-signs fa-10x"></i>
            <br> Printable LOT Map</a>
        </div>

        <div class="col-xs-12 col-sm-4">
          <a href="http://sunridge.info/docs/SunridgeHuntingMapAug2015.pdf" target="_blank"><i class="far fa-compass fa-10x"></i>
            <br> Hunting Map</a>
        </div>

      </div>
    </div>

    <!--<div class="container-fluid maps">-->
      <!--<div class="row">-->

      <!--<div class="col-xs-12 col-sm-2">-->
        <!--<div class="thumbnail resize">-->
          <!--<img v-img:group="{title: 'Map'}"  src="../assets/photos/map.jpg" alt="">-->
          <!--<div class="card-block p-3">-->
            <!--<div class="card-text">-->

            <!--</div>-->
      <!--</div>-->
        <!--</div>-->
      <!--</div>-->

      <!--<div class="col-xs-12 col-sm-2">-->
          <!--<div class="thumbnail resize">-->
              <!--<img v-img:group="{title: 'GPS Map'}"  src="../assets/photos/map2.jpg" alt="">-->
            <!--</div>-->
          <!--</div>-->


    <!--</div>-->
  <!--</div>-->

  </div>
</template>

<style>
  .resize{
    width: 100px;
    margin-left: 200px;
  }
  .icon{
    margin-top: 30px;
  }
  .maps{
    margin-top: 50px;
  }
</style>
