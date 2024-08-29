<template>
  <div class="main_box">
    <div class="title_box">
      <p>Полезные свойства капусты</p>
    </div>
    <div class="box">
      <div class="str1">
        <img src="./assets/img/kapusta.png" alt="">
        <p>
          Капуста давно и прочно вошла в рацион
          нашего питания и принадлежит к числу
          важнейших овощных растений. Она
          также является неотъемлемой частью
          таких традиционных блюд, как: борщ,
          щи, солянка, тушеная капуста, голубцы,
          капустная запеканка и конечно
          квашеная капуста.
        </p>
      </div>
      <div class="str2">
        <p>   Капуста не только популярный, но и полезный продукт: она богата
          витаминами А, В1, Р, К, В6, U. Капуста является лидером среди овощей по
          содержанию витамина С, причем он сохраняется в капусте как при длительном
          хранении в сыром виде, так и при термической обработке. В ней также много
          минералов - сера, кальций, калий и фосфор, клетчатки и воды.
        </p>
      </div>
      <div class="str3">
        <div class="likes">
          <img src="./assets/img/like.svg" alt="">
          <p>0</p>
        </div>
        
      </div>
      <div class="str4">
        <button @click="">ПОДЕЛИТЬСЯ</button>
        <ul>
          <li>
            <img src="./assets/img/vk.svg" alt="">
            <img src="./assets/img/tg.svg" alt="">
            <img src="./assets/img/ok.svg" alt="">
          </li>
          <li>ПОДЕЛИТЬСЯ</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
  body {
    overflow-x: hidden;
  }

  .main_box {
    height: 800px;
    background-color: #FECFB0;
  }

  .title_box {
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .title_box p {
    color: #B54B62;
    font-size: 32px;
    
  }

  .box {
    height: 700px;
    background-color: #FEA896;
    border-radius: 60px 60px 0 0;
  }

  .str1 {
    color: #B54B62;
    font-size: 24px;
    margin: 0 auto;
    padding-top: 20px;
    margin-left: 20px;
    display: flex;
    align-items: center;
    gap: 20px;
  }

  .str1 img {
    width: 480px;
    height: 320px;
    border-radius: 40px;
    margin: 0 auto;
  }

  .str2 {
    margin-top: 40px;
    margin-left: 20px;
    height: 160px;
  }

  .str2 p {
    color: #B54B62;
    font-size: 24px;
  }

  .likes {
    margin-top: 30px;
    margin-left: 948px;
    display: flex;
    align-items: center;
    gap: 10px;
    & p {
      font-size: 28px;
      color: #E5847B;
    }
  }

  .str4 {
    margin-top: 57px;
  }

  .str4 button {
    width: 180px;
    height: 40px;
    border-radius: 10px 10px 0 0;
    color: #E5847B;
    background-color: #B54B62;
    margin-bottom: 0;
    margin-left: 80px;
  }

  ul {
    margin-left: 80px;
  }

  ul li {
    width: 180px;
    height: 40px;
    background-color: #B54B62;
    
  }

  ul li img {
    width: 60px;
    height: 40px;
  }

  ul li img:first-child {
    border-right: 1px solid rgba(0, 0, 0, 0.200);
  }

  ul li img:last-child {
    border-left: 1px solid rgba(0, 0, 0, 0.200);
  }

  ul li:last-child {
    color: #FECFB0;
    border-top: 1px solid rgba(0, 0, 0, 0.200);
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 0 0 10px 10px;
  }

</style>

<script setup>


    
</script>