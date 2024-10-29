<template>
    <div class="profile-card">
      <h2 class="profile-name">Profile</h2>
      <p class="profile-info">John Yuri B. De Guzman</p>
      <p class="profile-bio">
        Dedicated student with a passion for learning and a love for gaming. I thrive on challenges, whether it’s acing exams or leveling up in my favorite games. Balancing academics and gaming fuels my creativity and problem-solving skills, and I’m always eager to connect with fellow gamers and students alike!
      </p>
    </div>
  </template>
  
  <script>
  export default {
    name: "ProfileComponent",
  };
  </script>
  
  <style scoped>
  /* Profile Card Container */
  .profile-card {
      max-width: 300px;
      margin: 20px auto;
      padding: 20px;
      background-color: #FFB6C1;
      color: blanchedalmond;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      text-align: center;
      font-family: Arial, sans-serif;
  }
  
  /* Profile Name */
  .profile-name {
      font-size: 24px;
      margin: 10px 0;
      color: #fff;
  }
  
  /* Profile Info */
  .profile-info {
      font-size: 16px;
      font-weight: bold;
  }
  
  /* Profile Bio */
  .profile-bio {
      font-size: 14px;
      line-height: 1.5;
      color: #000;
  }
  </style>
  