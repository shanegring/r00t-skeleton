---
title: Quote Slider
visible: true
---


<style>

.carousel-indicators li{
  background-color: #656565;
}

.carousel-indicators .active {
	background-color: #429DB5;
}


.carousel-control-prev-icon, .carousel-control-next-icon {
  background: #000;
}

.vertical-center {
  min-height: 100%;  /* Fallback for browsers do NOT support vh unit */
  min-height: 100vh; /* These two lines are counted as one :-)       */

  display: flex;
  align-items: center;
}

	</style>



<div class="bd-example">
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1" class=""></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2" class=""></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active" style="min-height: 400px">
      <div class="d-block w-100 align-self-center">

        <blockquote style="width: 70%; margin: 0 auto">
          
          <h5 class="pl-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</h5>
          <footer class="pl-3 blockquote-footer">Someone famous in Source Title</footer>

        </blockquote>


      </div>
    </div>
    <div class="carousel-item"  style="min-height: 400px">
      <div class="d-block w-100 align-self-center">

        <blockquote style="width: 70%; margin: 0 auto">
          
          <h5 class="pl-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in</h5>
          <footer class="pl-3 blockquote-footer">Someone famous in Source Title</footer>

        </blockquote>


      </div>
    </div>
    <div class="carousel-item"  style="min-height: 400px">
      <div class="d-block w-100 align-self-center">

        <blockquote style="width: 70%; margin: 0 auto">
          
          <h5 class="pl-3 align-items-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</h5>
          <footer class="pl-3 blockquote-footer">Someone famous in Source Title</footer>

        </blockquote>


      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <svg class="lingo--Arrow_Left icon-gray-dark img-fluid" style="width:25px">
    <use xlink:href="../../user/themes/r00t/build/svg/symbol/styleguide.svg#lingo--Arrow_Left"></use>
    <svg>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <svg class="lingo--Arrow_Right img-fluid" style="width:25px">
    <use xlink:href="../../user/themes/r00t/build/svg/symbol/styleguide.svg#lingo--Arrow_Right"></use>
    <svg>
    <span class="sr-only">Next</span>
  </a>
</div>
</div>