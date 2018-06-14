<template>



  <section id="topsection">
      <div class="container presentation">
          <div class="col-xs-12 col-md-6 name">
              <h1 class="intro">
                  <span class="bleu"> {{ name }} </span><br/>
                  <span class="blanc">{{ age }} ans </span> <br/>
                  <span class="blanc">{{ town }}</span><br/>
                  <span class="gris">{{ work }}</span>
              </h1>
          </div>
          <div class="col-xs-12 col-md-6 img-prez">
              <img src="../assets/yann-chanteloup.jpg">
          </div>
      </div>
  </section>


</template>

<script>
export default {
  name: 'TopSection',
  data(){
    return{
      name:'Yann Chanteloup',
      age: 30,
      town: 'Lyon',
      work: 'Web developpeur'
    }
  }
}
</script>

<style>
/** Css Nom + img prez **/

.presentation {
    background-color: #222222;
    margin-bottom: 20px;
    border-radius: 20px;
    clear: both;

}
.name {
    margin-top: 50px;
    display: inline-block;
    padding: 10px;
}

.img-prez {
    margin-top: 23px;
}

.img-prez img {
    display: block;
    margin: 0 auto;
    padding-top: -22px;
    padding-bottom: -17px;
    border: solid white;
}

.intro {
    font-size: 5em;
    line-height: 0.8em;
    text-transform: uppercase;
    margin-bottom: 50px;
    margin-top: -10px;
    letter-spacing: -2px;
}

@media screen and (max-width: 480px){

    .intro {
        font-size: 3em;
    }
}

.bleu {
    color: #0088CC;
}
.gris {
    color: #444444;
}
.blanc {
    color: white;
}
</style>
