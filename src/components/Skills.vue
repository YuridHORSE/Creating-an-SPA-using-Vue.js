<template>
    <div class="skills-card">
      <h2 class="skills-title">Skills</h2>
      <p class="skills-details">
        Great at making all sorts of dishes! I love being creative in the kitchen and paying attention to the little things. Friends and family often enjoy my tasty meals, and I can whip up something for everyone’s tastes.
      </p>
    </div>
  </template>
  
  <script>
  export default {
    name: "SkillsComponent",
  };
  </script>
  
  <style scoped>
  /* Skills Card Container */
  .skills-card {
      max-width: 300px;
      margin: 20px auto;
      padding: 20px;
      background-color: #ffb6c1;
      color: #ffffff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      text-align: center;
      font-family: Arial, sans-serif;
      margin-right: 550px;
      margin-top: -200px;
  }
  
  /* Skills Title */
  .skills-title {
      font-size: 20px;
      margin: 10px 0;
      color: #ffd700;
  }
  
  /* Skills Details */
  .skills-details {
      font-size: 14px;
      line-height: 1.5;
      color: #000;
  }
  </style>
  