---
permalink: /members/
title: "The Members of the Lab"
author_profile: true
redirect_from: 
---

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Research Group Members</title>
<style>
  .team-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
  }
  .advisor-box {
    width: 300px;
    border: 1px solid #ccc;
    padding: 20px;
    text-align: center;
  }
  .member-box {
    width: 200px;
    border: 1px solid #ccc;
    padding: 10px;
    text-align: center;
  }
  .member-photo {
    width: 150px; /* Larger size for advisor */
    height: 150px;
    border-radius: 50%; /* Circular image */
    margin: 10px auto;
  }
  .member-photo.small {
    width: 100px; /* Smaller size for students */
    height: 100px;
  }
  .member-name {
    margin-top: 10px;
    font-weight: bold;
  }
  .member-position, .member-interests {
    margin-top: 5px;
  }
  .advisor-row {
    width: 100%;
  }
</style>
</head>
<body>

<div class="advisor-row">
  <!-- Principle Investigator -->
  <div class="advisor-box">
    <img src="/images/xiaoyue.png" alt="Dr. Guanghui Yue" class="member-photo" >
    <div class="member-name">Dr. Guanghui Yue</div>
    <div class="member-position">Associate Professor at Shenzhen University</div>
    <div class="member-interests">Research Field: Biomedical Image Processing</div>
  </div>
</div>

<div class="team-container">
  <!-- PhD Student -->
  <div class="member-box">
    <img src="/images/yaoxizhang_jianshen.png" alt="Xizhang Yao" class="member-photo small">
    <div class="member-name">Xizhang Yao</div>
    <div class="member-position">PhD Student, Enrolled in 2024</div>
    <div class="member-interests">Research Field: Image Quality Assessment</div>
  </div>

  <!-- Master Students -->
  <div class="member-box">
    <img src="/images/tansongbai.png" alt="Songbai Tan" class="member-photo small">
    <div class="member-name">Songbai Tan</div>
    <div class="member-position">Master Student, Enrolled in 2022</div>
    <div class="member-interests">Research Field: Image Quality Assessment</div>
  </div>
  <div class="member-box">
    <img src="/images/songlongqi.png" alt="Longqi Song" class="member-photo small">
    <div class="member-name">Longqi Song</div>
    <div class="member-position">Master Student, Enrolled in 2023</div>
    <div class="member-interests">Research Field: Image Quality Assessment</div>
  </div>
  <!-- Add more members as needed -->
</div>

</body>
</html>
