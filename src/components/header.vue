<template>
  <div>
    <nav class="navbar navbar-default  navbar-fixed-top navbar-custom">

        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
        <div class="home">
          <router-link to="/" class="navbar-brand text-black" ><img src="../assets/photos/cabin2.png" width="30px" alt=""></router-link>
        </div>
        </div>

        <div class="collapse navbar-collapse" id="myNavbar">
          <div>


            <ul class="widgets">
              <li><h6 class="dates" style="margin-top: 25px;" >{{moment(date).format('MM/DD/YYYY')}}</h6></li>
              <li class="temp">
                <a class="weatherwidget-io" href="https://forecast7.com/en/41d33n111d81/84310/?unit=us"
                   data-label_1="EDEN" data-label_2="WEATHER" data-font="Roboto Slab" data-icons="Climacons" data-mode="Current"
                   data-days="3" data-theme="pure" >EDEN WEATHER</a></li>
            </ul>

          </div>
          <ul class="nav navbar-nav navbar-right drop" style="margin-right: 20px;">

            <router-link  to="/Member" active-class="active" tag="li"><a style="color: black">Board Members</a></router-link>
            <router-link to="/Home/Classifies" active-class="active" tag="li"><a style="color: black">Classified &amp; Ad's</a></router-link>
            <router-link to="/Home/docs" active-class="active" tag="li"><a style="color: black">Docs &amp; Forms</a></router-link>
            <li class="dropdown" :class="{open: isDropdownOpen}" @click="isDropdownOpen !=false">

              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false" style="color: black">News &amp; Events <span class="caret"></span></a>
              <ul class="dropdown-menu">
                <router-link to="/Home/News/2018" active-class="active" tag="li"><a style="color: black">2018 Season</a></router-link>
                <router-link to="/Home/News/2017" active-class="active" tag="li"><a style="color: black">2017 Season</a></router-link>
                <router-link to="/Home/News/2016" active-class="active" tag="li"><a style="color: black">2016 Season</a></router-link>
                <router-link to="/Home/Calender" active-class="active" tag="li"><a>Calender</a></router-link>
              </ul>
            </li>
            <router-link  to="/Gallery" active-class="active" tag="li"><a style="color: black">Photo Gallery</a></router-link>


          </ul>
        </div>

    </nav>

      <div class="banner ">
        <div class="hero">
          <div class="hero-text text-center">
            <h1>SunRidge Property Owners Association</h1>
          </div>
        </div>
      </div>
    </div>

</template>

<script>
  export default{
    data() {
      return{
        isDropdownOpen: false
      },

        !function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src='https://weatherwidget.io/js/widget.min.js';fjs.parentNode.insertBefore(js,fjs);}}(document,'script','weatherwidget-io-js');
    }
  }
</script>

<style>

  .navbar-custom {
    font-family: 'Oldenburg', sans-serif;

  }
.drop{
  margin-top: -50px;
}
  .dates{
    font-size: larger;
    padding-right: 10px;
    font-weight: bold;
  }

  .home{
    margin-top: 25px;
  }

  .widgets {
    list-style-type: none;
    margin: 0;
    padding-right: 10px;
    overflow: hidden;
    margin-left: 10px;
  }
.temp{
  width: 350px;
}
  li {
    float: left;
  }

  li a {
    display: block;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  .banner {

    background-image:  url('../assets/banner2.jpg');
    background-size: cover;
    background-attachment: fixed;
    overflow-x: hidden;
    margin: 0; padding: 0; box-sizing: border-box;
    width: 100%;
    height: 350px;

  }

  .hero {

    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: Tahoma, Geneva, sans-serif;
    margin-top: 100px;
  }
  .hero .banner{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-size: cover;
    background-color: #2196F3;
    z-index: -1;
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
  }

  .hero .banner:after{
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: #414a4f;
    opacity: 0.75;
  }

  @media screen and (max-width: 420px) {
.home{
  margin: 0;
}
.drop{
  margin-top: 20px;
}
    .hero-text{
      color: white;
      margin: 0 20px 0 20px;
      background-color: rgba(146, 149, 153, .6);
      width: 100%;
      padding: 5px;
    }

    .navbar-toggle{
      margin-right: 20px;
    }
.temp{
  width: 350px;
  padding-right: 100px;
}
  }

  @media screen and (max-width: 800px) {
    .home{
      margin: 0;
    }
    .drop{
      margin-top: 20px;
    }

    .head{
      padding: 0;
      margin-left: 100px;
    }

    .hero-text{
      color: white;
      margin: 0 20px 0 20px;
      background-color: rgba(146, 149, 153, .6);
      width: 100%;

    }

    .navbar-toggle{
      margin-right: 20px;
    }

  }


</style>
