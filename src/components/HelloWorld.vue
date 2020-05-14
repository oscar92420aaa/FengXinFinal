<template>
  <div class="hello">
    <div class="first">
      <div class="top-text">
        <span class="green">"</span>
        <span class="white">You are fired</span>
        <span class="green">"</span>
      </div>
      <div class="middle-text">
        <span>IMMJ - Story / Project A</span>
      </div>
      <div class="bottom-text">
        <span>Tutor: Tongfei & Sharron</span>
      </div>      
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
.hello {
  .first {
    height: 738px;
    background-image: url(../images/01.jpg);
    background-repeat: no-repeat;
    padding: 435px 305px 0 305px;
    font-family: fangzheng;
    .top-text {
      text-align: center;
      .green {
        color:aquamarine;
      }
      .white {
        color: white;
      }
    }
    .middle-text {
      text-align: center;
      color: white;
    }
    .bottom-text {
      text-align: center;
      color: white;
    }
  }
}
</style>
