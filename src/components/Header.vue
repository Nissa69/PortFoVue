<template>


  <!--<section>
      <div class="container" id="topnav">
      <nav class="navbar navbar-default" id="navbarBg">
          <div>
              <div class="col-xs-12 col-md-10 col-md-offset-1">
                  <div class="navbar-header">
                      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#myNavbar" aria-expanded="false">
                          <span class="sr-only">Toggle navigation</span>
                          <span class="icon-bar"></span>
                          <span class="icon-bar"></span>
                          <span class="icon-bar"></span>
                      </button>
                  </div>
                  <ul class="collapse navbar-collapse" id="myNavbar">
                      <ul class="nav navbar-nav navbar-right">
                          <li class="border-white"><a href="#">Projets</a></li>
                          <li class="border-white"><a href="#">Veille</a></li>
                          <li class="border-white"><a href="#">Photo</a></li>
                          <li class="border-white"><a href="#">Contact</a></li>
                      </ul>
                  </ul>
              </div>
          </div>
      </nav>
      </div>
  </section>
-->

<div id="topnav">
  <b-nav-item-dropdown class="navbarBg" text="Menu" right>
       <b-dropdown-item href="#">Présentation</b-dropdown-item>
       <b-dropdown-item href="#">Veille</b-dropdown-item>
       <b-dropdown-item href="#">Projets</b-dropdown-item>
     </b-nav-item-dropdown>
</div>



</template>

<script>
export default {
  name: 'Header'
}
</script>

<style>
/**NavBar**/


#topnav {
    padding: 0;

}

#navbarBg {
    background-color: #222222;
    border-radius: 20px;
    border: none;
    padding-top: 50px;
    margin-top: 50px;
    margin-bottom: 20px;
}
</style>
