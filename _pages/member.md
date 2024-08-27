---
permalink: /members/
title: "The Album of the Lab"
author_profile: true
redirect_from: 
---
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Research Group Members</title>
<style>
  .team-container {
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
    padding: 20px;
    text-align: center;
  }
  .advisor {
    width: 100%;
    display: flex;
    justify-content: center;
    flex-direction: column;
    margin-bottom: 20px;
  }
  .advisor img {
    width: 150px;
    height: auto;
    border-radius: 50%; /* Circular image */
    margin-bottom: 10px;
  }
  .students {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
  }
  .member {
    display: flex;
    align-items: center;
    flex-wrap: wrap;
  }
  .member img {
    width: 100px;
    height: auto;
    border-radius: 50%; /* Circular image */
    margin-right: 20px;
    flex-shrink: 0;
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
  <!-- Advisor -->
  <div class="advisor">
    <img src="/images/xiaoyue.png" alt="Dr. Guanghui Yue">
    <div class="member-title">Dr. Guanghui Yue</div>
    <div>Associate Professor at Shenzhen University</div>
    <div>Research Field: Biomedical Image Processing</div>
  </div>
  
  <!-- Students -->
  <div class="students">
    <!-- PhD Student -->
    <div class="member">
      <img src="/images/yaoxizhang_jianshen.png" alt="Xizhang Yao">
      <div class="member-info">
        <div class="member-title">Xizhang Yao</div>
        <div>PhD Student, Enrolled in 2024</div>
        <div>Research Field: Image Quality Assessment</div>
      </div>
    </div>
    <!-- Master Students -->
    <div class="member">
      <img src="/images/tansongbai.png" alt="Songbai Tan">
      <div class="member-info">
        <div class="member-title">Songbai Tan</div>
        <div>Master Student, Enrolled in 2022</div>
        <div>Research Field: Image Quality Assessment</div>
      </div>
    </div>
    <div class="member">
      <img src="/images/songlongqi.png" alt="Longqi Song">
      <div class="member-info">
        <div class="member-title">Longqi Song</div>
        <div>Master Student, Enrolled in 2023</div>
        <div>Research Field: Image Quality Assessment</div>
      </div>
    </div>
    <!-- More Master Students... -->
  </div>
</div>

</body>
</html>
<!--
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
