---
layout: archive
title: "Research Team"
permalink: /research_team/
author_profile: true
---

{% for group in site.data.research_team %}
<div class="kar-people-section">
  <h2>{{ group.section }}</h2>

  <div class="kar-people-grid">
    {% for person in group.members %}
    <div class="kar-person-card">
      {% if person.image %}
      <img src="{{ person.image }}" class="kar-person-card__img">
      {% else %}
      <div class="kar-person-card__img kar-person-card__img--placeholder">{{ person.name | slice: 0 }}</div>
      {% endif %}
      <div class="kar-person-card__info">
        <div class="kar-person-card__name">
          {% if person.url %}
          <a href="{{ person.url }}" target="_blank">{{ person.name }}</a>
          {% else %}
          {{ person.name }}
          {% endif %}
        </div>
        <div class="kar-person-card__role">
          {{ person.role }}
        </div>
      </div>
    </div>
    {% endfor %}
  </div>
</div>
{% endfor %}
