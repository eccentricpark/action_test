<template>
  <div class="inner">
    <div class="void-area"></div>
    <h2>지금 문해력 강화의 첫 걸음을 뗄 때입니다.</h2>
    <div>
      <img class="literacy-image" alt="literacy" src="../assets/child_literacy.jpg">
    </div>
    <div class="text-article">
      <p>
        우리 아이의 문해력을 향상시키기 위한 첫걸음을 내디뎌보세요.<br>
        아이들이 자신감과 사회성을 키울 수 있도록 도와주세요.<br>
      </p>
    </div>
    <div class="void-area"></div>
  </div>
</template>

<script setup>
</script>

<style scoped>
@media (max-width:600px){
  .div-row{
    display: flex;
    flex-direction: row;
  }

  .div-column{
    display: flex;
    flex-direction: column;
  }

  .inner{
    width:inherit;
  }

  .void-area{
    height: 150px;
  }

  .text-article{
    margin: 10px;
  }

  .literacy-image{
    width:300px;
    height: 200px;
  }

  h2{
    font-size: 20pt;
  }

  p{
    font-size: 14pt;
  }


}

@media (min-width:600px){
  .div-row{
    display: flex;
    flex-direction: row;
  }

  .div-column{
    display: flex;
    flex-direction: column;
  }

  .inner{
    width:inherit;
  }

  .void-area{
    height: 150px;
  }
  .literacy-image{
    width:800px;
    height:400px;
  }

  h2{
    font-size: 30pt;
  }

  p{
    font-size: 14pt;
  }
}
</style>