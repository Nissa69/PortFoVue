<template>

<div>
    <section>
        <div class="container veille">
            <div class="col-xs-12">
                <h2>Ma veille de la semaine !</h2>
                <hr>
            </div>
            <div class="col-xs-12 col-md-6">
                <img src="">
            </div>
            <div class="col-xs-12 col-md-6">
                <p>Lorem ipsum dolor sit amet, <strong>consectetur</strong> adipiscing elit. Vestibulum efficitur convallis lacus. Praesent in sagittis dolor.</p>
            </div>
        </div>
    </section>
  </div>

</template>

<script>
export default {
  name: 'Veille',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/** Css Veille **/

.veille {
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
.veille p {
    margin: 0 auto;
}
</style>
