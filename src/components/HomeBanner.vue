<template>
    <div class="banner">
        <div class="container h-100">
            <div class="row p-6 h-100 justify-content-center align-items-center">
            <!--banner畫面左區-->
            <div class="col-sm-12 col-md-5">
                <img src="https://lh3.googleusercontent.com/pw/AIL4fc-pMJnD4Q5bBOh-2ixE6ZhiQtE0MIZpObiL20Tqg0YRj8pSyWlDI-wNgJRmgRdkvYw4rieN8LmuoZuofoIXKUdT3636EVsox8dCq4Ltq3FvyoCQKxVwwNNpzS8JwPtYeRwMLlAnMcTvuAgptIpR_9uuUA=w1000-h750-s-no" alt="" width="300">
            </div>
            <!--banner畫面右區-->
            <div class="col-sm-12 col-md-5 m-3">
                <h3>廚房設施</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <button @click="gonews" class="btn custom-btn btn-outline-primary mr-4">
                  More News
                </button>

            </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "HomeBanner",
  props: {
    msg: String
  },
  methods:{
    gonews(){
      this.$router.replace('news');
    },
  }
};
</script>

<style >
  .banner{
    padding-top: 7rem;
    width: 100%;
    min-height: 500px;
    text-align: left;
    background-color: burlywood;
  }
</style>