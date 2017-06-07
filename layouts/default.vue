<template>
  <div>
    <header>
      <div class="columns is-gapless box-without-bottom">
        <div class="column">
          <div class="box box-without-radius box-top box-left">
              Welcome to Eletronics Recycling | How to Find Us | Give Feedback
          </div>
        </div>
        <div class="column">
            <div class="box box-without-radius box-top box-right">
              Search Keyword <i class="fa fa-search"></i>
            </div>
        </div>
      </div>

      <br>

      <navigation />

      <br>

    </header>
    <section class="section">
        <nuxt/>
    </section>
  </div>
</template>

<script>
  import Navigation from '~components/Nav'
  export default {
    components: {
      Navigation
    }
  }
</script>

<style scoped>
.section {
  /*border: 2px solid #000;*/
  padding: 0px;
}

.box-without-bottom {
  margin-bottom: 0px !important;
}

.box-top {
  font-size: 13px;
}

.box-without-radius {
  border-radius: 0px;
  color: #fff;
  padding: 0.1rem 0.7rem;
}

.box-left {
  background-color: #9ac23c;
}

.box-right {
  background-color: #56bf78;
  text-align: right;
}

.box-menu {
  color: #000;
}

.column-logo {
  text-align: center;
}

.social-icon {
  margin-top: 20px;
  font-size: 30px;
}

.social-icon .fa {
  margin-top: 10px;
}
</style>
