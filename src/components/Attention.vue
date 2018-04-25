<template>
  <div>
  <div class="container text-center">
    <h2 id="top">Sunridge News</h2>
    <img class="hr" src="../assets/photos/vines2.png" width="600" alt="">
  </div>
    <nav class="navbar">
      <div class="container-fluid">
        <ul class="nav navbar-nav">
          <router-link  to="/Home/News/2018" active-class="active" tag="li"><a style="color: black">2018 Season</a></router-link>
          <router-link  to="/Home/News/2017" active-class="active" tag="li"><a style="color: black">2017 Season</a></router-link>
          <router-link  to="/Home/News/2016" active-class="active" tag="li"><a style="color: black">2016 Season</a></router-link>
        </ul>
      </div>
    </nav>
  </div>

</template>

<style>
  .scroll {
    width: 100%;
    height: 350px;
    overflow: scroll;
  }

  li{
    list-style-type: none;
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
