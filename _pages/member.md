---
permalink: /members/
title: "The Album of the Lab"
author_profile: true
redirect_from: 
---

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>课题组成员</title>
<style>
  .team-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }
  .member {
    width: 50%;
    margin: 20px;
    padding: 10px;
    box-sizing: border-box;
    display: flex;
    align-items: center;
  }
  .member img {
    width: 150px;
    height: auto;
    border-radius: 50%; /* 圆形图片 */
    margin-right: 20px;
  }
  .member-info {
    flex-grow: 1;
  }
  .member-title {
    font-weight: bold;
  }
</style>
</head>
<body>

<div class="team-container">
  <!-- 导师 -->
  <div class="member">
    <img src="/images/xiaoyue.png" alt="Dr. Xiao Yue">
    <div class="member-info">
      <div class="member-title">Dr. Guanghui Yue </div>
      <div>Associate Professor at Shenzhen University.</div>
      <div>Research interests include midecal image processing.</div>
    </div>
  </div>
  
  <!-- 博士生 -->
  <div class="member">
    <img src="/images/yaoxizhang_jianshen.png" alt="Xizhang Yao">
    <div class="member-info">
      <div class="member-title">Xizhang Yao 姚习章</div>
      <div>PhD student starting from 2024.</div>
      <div>Interested in image quality assessment.</div>
    </div>
  </div>
  <!-- 更多博士生... -->
  
  <!-- 硕士生 -->
  <div class="member">
    <img src="/images/tansongbai.png" alt="Songbai Tan">
    <div class="member-info">
      <div class="member-title">Songbai Tan 谭松柏</div>
      <div>Master student starting from 2022.</div>
      <div>Interested in image quality assessment.</div>
    </div>
  </div>
  <!-- 更多硕士生... -->
</div>

</body>
</html>
