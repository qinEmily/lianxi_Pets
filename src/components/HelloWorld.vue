<template>
  <div class="hello">
    <div class="nav">
      <div class="left">
        <span style="cursor:pointer">MeowGO</span>
      </div>
      <div class="right">
        <ul>
          <li>
            <span>Home</span>
          </li>
          <li>
            <span>Services</span>
          </li>
          <li>
            <span>Contact Us</span>
          </li>
          <li>
            <span class="unic" style="cursor:pointer">Sign Up</span>
          </li>
        </ul>
      </div>
    </div>
    <div class="ad">
      <div class="left">
        <p class="one">bundle of happiness</p>
        <p class="two">bundle of happiness</p>
        <p class="three">bundle of happinessbundle of <br/> happiness</p>
        <p class="four">Get started</p>
      </div>
      <div class="right">
        <img src="~@/assets/imgs/cats-eyes.png" alt="">
      </div>
    </div>
    <div class="team">
      <div class="top">
        <p>Meet Our Team</p>
      </div>
      <div class="main">
        <div>
          <img src="~@/assets/imgs/image1.png" alt="">
          <p>Founder And CEO</p>
          <p>Sir Meowingtones</p>
        </div>
        <div>
          <img src="~@/assets/imgs/image2.png" alt="">
          <p>Founder And CEO</p>
          <p>Sir Meowingtones</p>
        </div>
        <div>
          <img src="~@/assets/imgs/image3.png" alt="">
          <p>Founder And CEO</p>
          <p>Sir Meowingtones</p>
        </div>
      </div>
    </div>
    <div class="signUp">
      <div class="wrapper">
        <p>Signup for our exclusive deals!</p>
      <div class="input">
        <input type="text">
        <span>Sign Up!</span>
      </div>
      </div>
    </div>
    <div class="cate">
      <div class="wrapper">
        <div>
        <p>Shop</p>
        <p>Toys</p>
        <p>Treats</p>
        <p>Sale</p>
      </div>
      <div>
        <p>Shop</p>
        <p>Toys</p>
        <p>Treats</p>
        <p>Sale</p>
      </div>
      <div>
        <p>Shop</p>
        <p>Toys</p>
        <p>Treats</p>
        <p>Sale</p>
      </div>
      <div>
        <p>Shop</p>
        <p>Toys</p>
        <p>Treats</p>
        <p>Sale</p>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.hello{
  background-color: black;
  width: 1440px;
  .nav{
    // background-color: black;
    height: 150px;
    .left{
      width: 720px;
      float: left;
      span{
        color:#FEF297;
        position: absolute;
        left: 100px;
        top: 80px;
      }
    }
    .right{
      width: 720px;
      float: left;
      ul{
        position: absolute;
        right: 0;
        top: 80px;
      }
      ul li{
      color:#fff;
      list-style: none;
      float: left;
      margin-right: 90px;
      }
      ul .unic{
        width: 160px;
        height: 65px;
        background-color:#FEF297;
        color: black;
        display: block;
        text-align: center;
        line-height: 65px;
        position: relative;
        top: -16px
      }
    }
  }
  .ad{
    position: relative;
    .left{
      z-index: 2;
      width: 720px;
      color: #FEF297;
      position: absolute;
      left: 100px;
      top: 250px;
      .one{
        font-size: 48px;
      }
      .two{
        font-size: 48px;
      }
      .four{
        margin-top: 40px;
        width: 223px;
        height: 65px;
        background-color:#FEF297;
        color: black;
        display: block;
        text-align: center;
        line-height: 65px;
      }
    }
    height: 800px;
    .right{
      position: absolute;
      top: 0;
      right: 0;
      img{
        width: 1440px;
        height: 800px;
        // height: 700px;
      }
    }
  }
  .team{
    color: #FEF297;
    .top{
      height: 150px;
      text-align: center;
      p{
        line-height: 150px;
        font-size: 48px;
      }
    }
    .main{
      height: 650px;
      display: flex;
      text-align: center;
      div{
        flex: 1;
        img{
          width: 300px;
          margin-bottom: 80px;
        }
        p{
          font-size: 32px;
          margin-bottom: 20px;
        }
        p:last-child{
           font-size: 24px;
        }
      }
    }
  }
  .signUp{
    display: flex;
    height: 240px;
    background-color: #FEF297;
    justify-content: center; /* 水平居中 */
    align-items: center;     /* 垂直居中 */
    .wrapper{
      flex: 1;
      text-align: center;
      p{
      font-size: 32px;
      font-weight: bold;
      margin-bottom: 30px;
    }
    input{
      width: 370px;
      height: 40px;
      border: none;
    }
    .input{
      text-align: center;
      span{
        background-color: black;
        display: inline-block;
        color: #FEF297;
        font-size: 24px;
        width: 130px;
        height: 40px;
      }
    }
    }
  }
  .cate{
    height: 260px;
    display: flex;
    justify-content: center; /* 水平居中 */
    align-items: center;     /* 垂直居中 */
    .wrapper{
      width: 750px;
      margin: 0 auto;
    display: flex;
    text-align: center;
    color: #FEF297;
    div{
      flex: 1;
      p{
        font-size: 24px;
        margin-bottom: 10px;
      }
      p:first-child{
        font-size: 32px;
      }
    }
    }
  }
}
</style>
