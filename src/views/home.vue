<template>
<div>
    <!-- 头部导航 -->
    <div class="header"> 
       <img  src="https://web-data.zmlearn.com/image/mwJcTQFqR8eWmcTXTiDg4U/index_revision_headerlogo.png" alt="掌门优课logo" class="hederimg" style="height: 16px;">
       <img  src="https://web-data.zmlearn.com/image/macr6aVf5rHWHEqDQqM6Kr/index_revision_headeropen.png" alt=""  style="height: 15px;padding-right: 20px;">
    </div>
   <!-- 第一张图 -->
    <div class="content">
    <img  src="https://web-data.zmlearn.com/image/soYqbvd4Bz4vKku2DgfPrB/index_revision_topbanner.png" alt="banner" class="content-banner-img">
    </div>
    <!-- 输入框 -->
    <div class="form-item-input">
        <input  placeholder="请输入您的手机号码" :maxlength="11" placeholderclass="input-placeholder" type="text" class="tel">
     </div>
     <div class="form-item-submit">
         <img  src="https://web-data.zmlearn.com/image/5ZixaCC7FxfGHAs8gGmoP5/button%402x.png" class="lesson-btn-img">
        <div  class="text-agree"> 
         <span>点击按钮即表示同意我们的 </span>
         <a  href="https://www.zhangmen.com/protocol.html">《用户协议》</a>
         </div>
     </div>
     

     <!-- <img data-v-052ef41a="" src="https://web-data.zmlearn.com/image/4fjs5dQ5oiQ6C2r1HqDPx7/index_revision_whychoose.png" alt="" srcset="" class="why-img"> -->
</div>
</template>
    
<script>
export default {
}
</script>

<style>
*{
    margin: 0px;
    padding: 0px;
}

.header{
    height: 50px;
    position: relative;
    width: 100%;
    position: fixed;
    background-color: #fff;
    top: 0;
    left: 0;
    z-index: 9999;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.hederimg {
    padding: 17.5px 20px;

}
.content-banner-img{
    width: 100%;
}
.content{
    margin-top: 30px;
    width: 100%;
    display: block;
}
.form-item-input
{    font-size: 14px;
    height: 60px;
    width: 80%;
    padding-right: 20px;
    border-radius: 10px;
    padding-left: 20px;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    margin-bottom: 10px;
    background: #eee;
    margin-top: 10px;
    margin-left: 40px;
}
.form-item-input input{
    border: none;
    background: transparent;
    font-size: 14px;
    padding-top: 15px;
}
.form-item-input input:focus{
 outline: 0;

}
.form-item-submit{

    width: 260px;
    margin: 0 auto;
    position: relative;
}
.lesson-btn-img
{
    width: 100%;
}
.text-agree
{
        width: 100%;
        text-align: center;
        position: relative;
        margin-top: -20px;
}

.text-agree  span{
    text-align: center;
    font-size: 12px;
    color: #636363;
    margin-top: 10px;
    bottom: 12px;
}
 .text-agree a {
    text-decoration: none;
    color: #4a90e2;
    font-size: 12px;
}
</style>
