---
layout: page
title: FAQ
permalink: /faq/
---

<div style="text-align: center; font-weight: bold;">
  <h2>Frequently Asked Questions</h2>
</div>
--- 
<div class="faq-container">
{% for faq_item in site.data.faq %}
  <div class="faq-item">
    <div class="question">{{ faq_item.question }}</div>
    <div class="answer">{{ faq_item.answer }}</div>
  </div>
{% endfor %}
</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
  const faqItems = document.querySelectorAll(".faq-item");

  faqItems.forEach(function(item) {
    const question = item.querySelector(".question");
    const answer = item.querySelector(".answer");

    question.addEventListener("click", function() {
      question.classList.toggle("clicked"); // Toggle the "clicked" class on the question
      answer.classList.toggle("show");
    });
  });
});
</script>
