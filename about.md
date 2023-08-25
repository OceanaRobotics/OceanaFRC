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

<div style="text-align: center; background-color: #f4f4f4; padding: 10px; border-radius: 50px; margin-bottom: 40px;">
  <h2 style="font-size: 44px; font-weight: bold; text-align: center; margin-top: 5px">Oceana Robotics</h2>
  <h3 style="font-size: 36px; text-align: center; margin-top: 5px">FRC Team 6128</h3>
  <p style="font-size: 16px; line-height: 1.5; color: #333; text-align: justify;">
    Oceana Robotics is an organization based out of Hart, MI that provides an exemplary robotics experience. Our after-school program teaches students design, programming, and building, along with other valuable skills such as public speaking and marketing. Our program simulates real-life situations and prepares students for their future careers. Our team is mentored by volunteers, all of whom are professionals in the fields that our team prepares our students for. If you're looking for a fun after-school activity, Oceana Robotics could be for you!
  </p>
</div>

<div style="text-align: center; background-color: green; padding: 5px; border-radius: 50px; margin-bottom 10px; font-size: 36px;">
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

<h3 style="text-align: justify;">Please get permission from your parent or guardian to register. They will help you complete the forms that FIRST needs to allow you to join the team. 😜</h3>

<div style="text-align: center; margin-top: 20px;">
  <img src="{{ site.baseurl }}/assets/images/OUCH.gif" alt="OUCH">
</div>
