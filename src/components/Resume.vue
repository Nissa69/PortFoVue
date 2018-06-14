<template lang="html">

  <section>
      <div class="container description">
          <div>
              <h2>Petite déscription</h2>
              <hr>
          </div>
          <p>
              Issu une longue expérience dans la <strong>photographie</strong> pro en tant que reporter.<br/>

              Attiré par le goût de l'image, le design, j'aime réfléchir à l'ergonomie et désire maintenant passer derrière le rideau pour pouvoir m'occuper de tout ce que l'on ne voit pas.<br/>

              Curieux de nature me lancer et aboutir sur des expériences concrètes est une priorité dans chaque domaine que j'entreprends.<br/>
              Après une formation developpeur web à la <strong>Wild Code School</strong> de LYON en 2017, j'ai fais mes premieres armes dans le php et Symfony avec un premier stage suivi d'un CDD chez Geolid.<br/>

              Vous pouvez me <strong>contacter</strong> via mon adresse pro : yann.chanteloup.pro@gmail.com<br/>
              Suivez mon évolution au sein de l'école en regardant mes projets sur <strong>github</strong>  ; https://github.com/Nissa69
          </p>
      </div>
  </section>

</template>

<script>
export default {
  name: 'Veille'
}
</script>

<style>

/** Css Description **/

.description {
    background-color: #222222;
    border-radius: 20px;
    text-align: center;
    padding: 30px;
    color: white;
    margin-top: 20px;
    margin-bottom: 20px;
    font-size: 1.5em;
    line-height: 40px;
}
.description strong {
    color: #0088CC;
}

@media screen and (max-width: 480px){
    .description {
        font-size: 1em;
    }
}
</style>
