---
permalink: /members/
title: "The Members of the Lab"
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
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
  }
  .advisor-container {
    width: 100%;
    text-align: center;
  }
  .advisor-box {
    width: 70%; /* 70% width for the advisor */
    border: 1px solid #ccc;
    padding: 20px;
    margin: 20px auto; /* Center the advisor box */
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .advisor-photo {
    width: 150px; /* Fixed size for advisor photo */
    height: 150px;
    border-radius: 50%; /* Circular image */
    margin-right: 20px;
  }
  .advisor-info {
    flex-grow: 1;
  }
  .member-box {
    width: calc(33.33% - 20px); /* Adjust the width for 3 columns */
    border: 1px solid #ccc;
    padding: 20px;
    margin-bottom: 20px; /* Space below each member box */
    box-sizing: border-box;
    text-align: center;
  }
  .member-photo {
    width: 150px; /* Fixed size for member photo */
    height: 150px;
    border-radius: 50%; /* Circular image */
    margin: 10px auto 20px; /* Center the photo and add space below */
  }
  .member-info {
    margin-top: 10px;
  }
  .member-name {
    font-weight: bold;
  }
  .member-position, .member-interests {
    margin-top: 5px;
  }
  .team-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
  }
</style>
</head>
<body>

<div class="advisor-container">
  <!-- Principle Investigator -->
  <div class="advisor-box">
    <img src="/images/xiaoyue.png" alt="Dr. Guanghui Yue" class="advisor-photo">
    <div class="advisor-info">
      <div class="member-name">Dr. Guanghui Yue</div>
      <div class="member-position">Associate Professor at Shenzhen University</div>
      <div class="member-interests">Research Field: Biomedical Image Processing</div>
    </div>
  </div>
</div>

<div class="team-container">
  <!-- PhD Student -->
  <div class="member-box">
    <img src="/images/yaoxizhang_jianshen.png" alt="Xizhang Yao" class="member-photo">
    <div class="member-info">
      <div class="member-name">Xizhang Yao</div>
      <div class="member-position">PhD Student, Enrolled in 2024</div>
      <div class="member-interests">Research Field: Image Quality Assessment</div>
    </div>
  </div>

  <!-- Master Students -->
  <div class="member-box">
    <img src="/images/tansongbai.png" alt="Songbai Tan" class="member-photo">
    <div class="member-info">
      <div class="member-name">Songbai Tan</div>
      <div class="member-position">Master Student, Enrolled in 2022</div>
      <div class="member-interests">Research Field: Image Quality Assessment</div>
    </div>
  </div>
  <div class="member-box">
    <img src="/images/songlongqi.png" alt="Longqi Song" class="member-photo">
    <div class="member-info">
      <div class="member-name">Longqi Song</div>
      <div class="member-position">Master Student, Enrolled in 2023</div>
      <div class="member-interests">Research Field: Image Quality Assessment</div>
    </div>
  </div>
  <!-- Add more members as needed -->
</div>

</body>
</html>
