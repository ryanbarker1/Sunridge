<template>
  <div>

    <footer>
      <div class="container" >
        <div class="row">
          <nav class="navbar text-center footer">


          <div class="foot">
                 <div class="col-xs-12 col-sm-3 col-md-4 col-lg-6">
                  <p>For information regarding this website and to place
                    a classified ad or publish a Calendar event, contact
                    <a href="mailto:webmaster@sunridge.info">the Webmaster</a></p>
                </div>

            <div class="col-xs-4 col-sm-3 col-md-4 col-lg-2">
            <div class="vl"></div>
            </div>
                <div  class="book">
                  <div class="col-xs-12 col-sm-3 col-md-4 col-lg-2">
                    Follow us on Facebook <br>

                  <a  href="https://www.facebook.com/SunridgePropertyOwnersAssociation?hc_location=stream" target="_blank">
                  <i class="fab fa-facebook-square fa-2x face"></i></a>
                </div></div>
          </div>
          </nav>

        </div>
      </div>
    </footer>
  </div>
</template>

<style>


footer{
  background-color: lightgray;
  margin-top: 50px;
}

.book{
  padding-left: 300px;
}
  .face{
    color: white;
  }
.face:hover{
  color: #072d6b;
}
  .footer{
    margin-top: 50px;
  }

.vl {
  border-left: 2px solid black;
  height: 100px;
}

  @media screen and (max-width: 400px) {
    .book{
      padding: 0;
    }
    footer{
      width: 100%;
    }
    .vl {

      height: 0;
    }

  }


@media screen and (max-width: 800px) {
  .book{
    padding: 0;
  }
  footer{
    width: 100%;

  }
  .foot{
    width: 100%;

  }


}



</style>
