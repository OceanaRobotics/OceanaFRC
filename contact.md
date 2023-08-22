---
layout: page
title:  Contact Us
permalink: /contact/
# date:   2023-08-20 14:37:36 -0400
# author: Nicholas Rombach
---

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 400px;
      margin: 0 auto;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.1);
    }
    .fs-frm {
      margin: 0;
    }
    .form-field {
      margin-bottom: 20px;
      width: 95%;
    }
    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    input[type="text"],
    input[type="email"],
    textarea {
      width: 100%;
      max-width: 100%; /* This adjustment ensures the fields don't exceed the container */
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    textarea {
      resize: vertical;
    }
    .submit-button {
      background-color: #007bff;
      color: #fff;
      border: none;
      border-radius: 5px;
      padding: 10px 20px;
      cursor: pointer;
    }
    .submit-button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Email Us</h1>
    <p>Please use the form below to get in touch with us.</p>
    <form class="fs-frm" id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/xwkdovwy" method="post">
      <div class="form-field">
        <label for="full-name">Full Name</label>
        <input type="text" name="name" id="full-name" placeholder="First and Last" required>
      </div>
      <div class="form-field">
        <label for="email-address">Your Email Address</label>
        <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required>
      </div>
      <div class="form-field">
        <label for="school">School</label>
        <input type="text" name="school" id="school" placeholder="Your School Name" required>
      </div>
      <div class="form-field">
        <label for="message">Message</label>
        <textarea rows="5" name="message" id="message" placeholder="Please write us a message and we will get back to you ASAP!" required></textarea>
      </div>
      <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
      <button type="submit" class="submit-button">Submit</button>
    </form>
  </div>
</body>
</html>
<!-- <body>
  <div class="container">
    <h1>Email Us</h1>
    <p>Please use the form below to get in touch with us.</p>
    <form class="fs-frm" id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/xwkdovwy" method="post">
      <div class="form-field">
        <label for="full-name">Full Name</label>
        <input type="text" name="name" id="full-name" placeholder="First and Last" required>
      </div>
      <div class="form-field">
        <label for="email-address">Your Email Address</label>
        <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required>
      </div>
      <div class="form-field">
        <label for="message">Message</label>
        <textarea rows="5" name="message" id="message" placeholder="Please write us a message and we will get back to you ASAP!" required></textarea>
      </div>
      <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
      <button type="submit" class="submit-button">Submit</button>
    </form>
  </div>
</body>
</html> -->
