---
layout: page
title: Calender
permalink: /calender/
---

<div style="color: navy; font-size: 36px; font-weight: bold; margin-bottom: 0px;">What's happening? 🗓️</div>

<style>
  .calendar-container {
    width: 100%;
    max-width: 600px; /* Adjust this value to your preference */
    margin: 0 auto;
    overflow: hidden;
  }

  /* Adjust the Google Calendar navigation elements for mobile */
  @media (max-width: 650px) {
    .calendar-container iframe {
      transform: scale(0.8);
      transform-origin: top left;
      width: 125%; /* Adjust the width for mobile */
      height: 725px; /* Adjust the height for mobile */
    }
  }

  /* Adjust the Google Calendar navigation elements for desktop */
  @media (min-width: 651px) {
    .calendar-container iframe {
      width: 100%; /* Adjust the width to fit the desktop screen */
      height: 600px; /* Adjust the height as needed for desktop */
      transform: none;
      transform-origin: unset;
    }
  }
</style>

<div style="text-align: center; margin-top: 50px;">
  <div class="calendar-container">
    <iframe src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23ffffff&ctz=America%2FNew_York&mode=MONTH&src=ZWFkMWJkMmNiNWY1MTAwYzk0ZDNjMzMwYjVmYjFkZjcwNjk3YzkwODExOGM1MjNlNWY0MTI5YjE5ZjJjMmJhYkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&src=ZW4udXNhI2hvbGlkYXlAZ3JvdXAudi5jYWxlbmRhci5nb29nbGUuY29t&color=%23D50000&color=%230B8043" style="border-width: 0;" frameborder="0" scrolling="no"></iframe>
  </div>
</div>
