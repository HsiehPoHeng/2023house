<template>
    <div class="header">
     <div class="container h-100">
          <div class="row h-100 justify-content-center align-items-center">
       <!--header畫面左區-->
            <div class="col-sm-12 col-md-6">
              <div class="header-content">
                <h1 class="header-title">
                  房屋特價：３２５０萬（含車位）
                  前院有５大車位，建材優質，地點方便
                </h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <div class="header-btn mt-3">
                    <button @click="goabout" class="btn custom-btn btn-info mr-4">
                        About
                    </button>
                    <button @click="goproducts" class="btn custom-btn btn-outline-secondary">
                      Products
                    </button>
                </div>
              </div>
            </div>
       <!--header畫面右區-->
            <div class="col-sm-12 col-md-5 m-3">
                <div class="graphic">
                    <img src="https://lh3.googleusercontent.com/pw/AIL4fc-SOLHlJMhqWs8efKkJMVf-12lkpB0SGmjwhPacZ3ZzV97-g2KiPW_UYHe88q69FbK3IsBB61d3oMyDegNLoLnZ60f-P_MHdW-monJ8keg0jhjoObT2R9O9kSqpnEspudkx84-dBoqKs1eolXd4K-XR0A=w1000-h750-s-no" alt="" width="400">
                </div>
            </div>
          </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "HomeHeader",
  props: {
    msg: String
  },
  methods:{
    goabout(){
      this.$router.replace('about');
    },
    goproducts(){
      this.$router.replace('products');
    },
  }
};
</script>

<style >
  .header{
    padding-top: 7rem;
    width: 100%;
    min-height: 500px;
    text-align: left;
    background-color:darkgoldenrod;
  }
</style>