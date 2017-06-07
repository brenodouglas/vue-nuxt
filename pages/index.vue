<template>
    <section>
        <slick ref="slick" :options="slickOptions">
          <a href="http://placehold.it/2000x800"><img src="http://placehold.it/2000x800" alt=""></a>
          <a href="http://placehold.it/2000x800"><img src="http://placehold.it/2000x800" alt=""></a>
          <a href="http://placehold.it/2000x800"><img src="http://placehold.it/2000x800" alt=""></a>
          <a href="http://placehold.it/2000x800"><img src="http://placehold.it/2000x800" alt=""></a>
          <a href="http://placehold.it/2000x800"><img src="http://placehold.it/2000x800" alt=""></a>
        </slick>

        <div class="columns secao padding-top">
           <div class="column">
             <p class="text-center">
               <i class="fa fa-recycle"></i>
             </p>
             <h1 class="text-center title">Welcome to GoGreen</h1>
             <h2 class="text-center subtitle">More about us</h2>
             <br>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. 
                Nesciunt exercitationem accusamus ducimus velit fugit hic totam, omnis earum non odit quod, 
                dolor eaque tempore odio quos vitae, debitis placeat deserunt!
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum sapiente, eaque, quisquam hic, laudantium, 
                tenetur quia rem sint amet magnam velit cum optio id placeat autem ratione libero nihil recusandae.
              </p>
           </div>
        </div>

        <br>

        <div class="columns secao">
            <div class="column">
                <div class="box">
                    <span class="icon-top-box">
                      <i class="fa fa-leaf"></i>
                    </span>

                    <h2 class="text-center subtitle">
                      Corporate Services
                    </h2>
                    <p class="text-center">
                      Guaranteed that all of your universal waste maangement is perfomed safely and responsibly
                    </p>
                </div>
            </div>
            
            <div class="column">
               <div class="box">
                    <span class="icon-top-box">
                      <i class="fa fa-inbox"></i>
                    </span>

                    <h2 class="text-center subtitle">
                      Convenient Pickup
                    </h2>
                    <p class="text-center">
                      We offer business pickup services to safaly recycle your eletronics in a safe manner
                    </p>
                </div>
            </div>

            <div class="column">
               <div class="box">
                    <span class="icon-top-box">
                      <i class="fa fa-calendar"></i>
                    </span>
                    <h2 class="text-center subtitle">
                      E-wat Events
                    </h2>

                    <p class="text-center">
                      We work with no-profits, businesses, and other organization to host
                      community e-waste events.
                    </p>
                </div>
            </div>
        </div>

        <br><br>

        <div class="columns secao secao-form">
            <form action="" class="column">
                
                <div class="column">
                    <p class="text-center">
                      <i class="fa fa-recycle"></i>
                    </p>
                    <h1 class="text-center title is-withe">Schedule Pickup</h1>
                    <h2 class="text-center subtitle is-withe">For old equipment</h2>
                </div>

                <br><br>

                <div class="field is-horizontal">
                  <div class="field-body">
                    <div class="field is-grouped">
                      <p class="control is-expanded has-icons-left">
                        <input class="input" type="text" placeholder="Name">
                        <span class="icon is-small is-left">
                          <i class="fa fa-user"></i>
                        </span>
                      </p>
                    </div>
                    
                    <div class="field">
                      <p class="control is-expanded has-icons-left has-icons-right">
                        <input class="input" type="email" placeholder="Email" value="" />
                        <span class="icon is-small is-left">
                          <i class="fa fa-envelope"></i>
                        </span>
                      </p>
                    </div>
                  </div>
                </div>

                <div class="field is-horizontal">
                  <div class="field-body">
                    <div class="field">
                      <div class="control">
                        <textarea class="textarea" placeholder="Explain how we can help you"></textarea>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="field is-center">
                  <div class="field-body">
                    <div class="field">
                      <div class="control">
                        <button class="button is-primary">
                          Send message
                        </button>
                      </div>
                    </div>
                  </div>
                </div>
            </form>
        </div>
    </section>
</template>

<script>
import Slick from 'vue-slick/slickCarousel.vue'

export default {
  components: {
    Slick
  },
  data () {
    return {
      slickOptions: {
        slidesToShow: 1,
        slidesToScroll: 1,
        infinite: true,
        arrows: false
      }
    }
  }
}
</script>

<style scoped>
  .secao {
    padding: 0rem  0.75rem;
  }

  .padding-top {
    padding-top: 4rem;
  }
  
  .text-center {
    text-align: center;
  }

  .fa-recycle {
    color: green;
    font-size: 20px;
  }

  .icon-top-box i.fa {
    border-radius: 30px;
    padding: 1rem 1rem 0.7rem;
    background-color: #00d1b2;
    color: #fff;
    width: 45px;
    position: relative;
    top: -40px;
    text-align: center;
    display: block;
    margin: 0 auto;
  }

  .secao-form {
    background: #292b30;
    padding: 5rem;
    margin-bottom: 2rem;
  }

  .button.is-primary {
    display: block;
    margin: 0 auto;
  }
  
  .is-withe {
    color: #fff;
  }
</style> 
