<template>
    <div class="footer">
        <div class="container h-100">
            <div class="row p-5 h-100 justify-content-center align-items-center">
            <!--footer畫面左區-->
            <div class="col-sm-12 col-md-7">
                <h3>衛浴設備</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <button @click="gostores" class="btn custom-btn btn-outline-primary mr-4">
                  Stores Information
                </button>
            </div>
            <!--footer畫面右區-->
            <div class="col-sm-12 col-md-4 m-3">
                <img src="https://lh3.googleusercontent.com/pw/AIL4fc8V5t9qICByRquEJxIZrJHmzKRrkHw-rk-a8vyaMtzOhsakH7CB86IGnjUEr02Q2-d3pZpjMA9fbq4WNvF3PTCKj4_Pq-u9fCCHH5AbcOmvMUYz1NcPOLZxDDcHzQXfZlmIXQOKkwUAxdHYT6wxSXio3g=w1000-h750-s-no" alt="" width="300">
            </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "HomeFooter",
  props: {
    msg: String
  },
  methods:{
    gostores(){
      this.$router.replace('stores');
    },
  }
};
</script>

<style >
  .footer{
    padding-top: 7rem;
    width: 100%;
    min-height: 500px;
    text-align: left;
    color: #ffffff;
    background-color:darkslategray;
  }
</style>