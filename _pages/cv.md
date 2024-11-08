---
layout: cv
permalink: /cv/
title: Curriculum Vitae
nav: true
nav_order: 2
cv_pdf: /assets/pdf/CV.pdf
---

# {{ page.title }}

{% if page.cv_pdf %}
  <a href="{{ page.cv_pdf | relative_url }}" target="_blank" rel="noopener noreferrer">
    <i class="fas fa-file-pdf"></i> Download PDF
  </a>
{% endif %}