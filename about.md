---
layout: page
title: About
permalink: /about/
---

<script>
function toggleVisibility(elementId) {
  var element = document.getElementById(elementId);
  element.classList.toggle('visible'); // Toggle the 'visible' class
}
</script>

<style>
  .coach-tap {
    text-align: center;
    background-color: rgba(64, 200, 64, 0.25);
    padding: 5px;
    border-radius: 50px;
    margin-bottom 10px;
    font-size: 36px;
  }

  .about-wrap {
    text-align: center;
    background-color: #f4f4f4;
    padding: 10px;
    border-radius: 50px;
    margin-bottom: 40px;
  }
  .about-title {
    font-size: 44px;
    font-weight: bold;
    text-align: center;
    /* margin-top: 5px; */
  }
  .about-subtitle {
    font-size: 24px;
    font-family: monospace;
    text-align: center;
    margin-bottom: 10px;
  }
  .about-content {
    font-size: 16px;
    line-height: 1.5;
    color: #333;
    text-align: justify;}
</style>

<div class="about-wrap">
  <div class="about-title">Oceana Robotics</div>
  <div class="about-subtitle">FRC Team 6128</div>
  <p class="about-content">
    Oceana Robotics is an organization based out of Hart, MI that provides an exemplary FIRST Robotics Competition experience. Our after-school program teaches students design, programming, and building, along with other valuable skills such as public speaking and marketing. Our program is fun! It simulates real-life situations and prepares students for their future careers. Our team is mentored by volunteers, both of which are professionals in the fields that they prepare the students for. If you are looking for a fun after-school activity, Oceana Robotics could be for you!
  </p>
</div>

<div class="coach-tap">
Tap to learn more about our Coaches!
</div>

<div style="display: flex; justify-content: space-evenly;">
  <div class="coach-container">
    <img src="{{ site.baseurl }}/assets/images/CoachMW.png" alt="Coach Matt" class="coach-image" onclick="toggleVisibility('mattContent');">
    <div class="coach-name" style="font-weight: bold; font-size: 36px;">Matt</div>
    <div id="mattContent" class="coach-content">
      <p>Matt is the Lead Coach for Team 6128. He is a retired Electrical Engineer with 40 years of experience. His hobbies include 3D printing, networking, machining, fabricating, fixing utilities, designing 3D models, computing, managing projects, administrating teams, boats, trains, reading and physics.</p>
    </div>
  </div>
  <div class="coach-container">
    <img src="{{ site.baseurl }}/assets/images/CoachMentorNR.jpg" alt="Coach Nick" class="coach-image" onclick="toggleVisibility('nickContent');">
    <div class="coach-name" style="font-weight: bold; font-size: 36px;">Nicholas</div>
    <div id="nickContent" class="coach-content">
      <p>Nicholas is a Coach and Mentor for Team 6128. He has a B.S.E. in Product Design & Manufacturing Engineering from GVSU. He is an experienced Design Engineer. His hobbies include running, reading, kayaking, snowboarding, programming, fabricating, making smart contracts, building websites, hacking, gardening, and botany.</p>
    </div>
  </div>
</div>

<div class="about-wrap">Please get permission from your parent or guardian to register. They will help you complete the forms at the <a href="{{ site.baseurl }}/jekyll/update/2023/08/11/register-FIRST-account.html">Registration Portal</a> that FIRST needs to allow you to join the team. 😜</div>

<div style="text-align: center; margin-top: 20px; margin-bottom: 50px;">
  <img src="{{ site.baseurl }}/assets/images/OUCH.gif" alt="OUCH">
</div>

<div style="color: navy; font-size: 36px; font-weight: bold; margin-bottom: 5px; text-align: center;">Meet here!📍</div>
<div style="display: flex; justify-content: center; margin-bottom: 20px;">
  <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d11530.621704532181!2d-86.37018675933841!3d43.73848451891624!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x881c0784c753ce87%3A0x119a6d0133cc6700!2sMichigan%20State%20University%20AgBioResearch%20West%20Central%20Michigan%20Research%20and%20Extension%20Center!5e0!3m2!1sen!2sus!4v1691718293562!5m2!1sen!2sus" width="600" height="450" style="border: 1px black" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>
