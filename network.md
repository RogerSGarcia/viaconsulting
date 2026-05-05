---
layout: default
title: Our Network
permalink: /network/
---

# Our Network

We work with a trusted network of specialists to give you access to services beyond what one office can provide.

---

<div class="network-list">

{% assign sorted_network = site.network | sort: "order" %}

{% for person in sorted_network %}
  {% if person.published != false %}
    <div class="network-item">
      {% if person.pic %}
        {% if person.website %}
          <a href="{{ person.website }}" target="_blank">
            <img src="{{ person.pic | relative_url }}" alt="{{ person.name }}">
          </a>
        {% else %}
          <img src="{{ person.pic | relative_url }}" alt="{{ person.name }}">
        {% endif %}
      {% endif %}
      <h3>
        {% if person.website %}
          <a href="{{ person.website }}" target="_blank">
            {{ person.name }}
          </a>
        {% else %}
          {{ person.name }}
        {% endif %}
      </h3>
      <p><strong>{{ person.role }}</strong></p>
      <p>{{ person.description }}</p>
      {% if person.resume %}
        <p class="network-action">
          <a href="{{ person.resume }}" target="_blank">
            View Resume
          </a>
        </p>
      {% endif %}
      {% if person.portfolio %}
        <p class="network-action">
          <a href="{{ person.portfolio }}" target="_blank">
            View Portfolio
          </a>
        </p>
      {% endif %}
      <div class="socials">
        {% if person.instagram %}
          <a href="{{ person.instagram }}" target="_blank"
            onclick="gtag('event','instagram_click', {
              'event_category':'engagement',
              'event_label':'{{ person.name }}'
            });">
            Instagram
          </a>
        {% endif %}
        {% if person.facebook %}
          <a href="{{ person.facebook }}" target="_blank">Facebook</a>
        {% endif %}
        {% if person.tiktok %}
          <a href="{{ person.tiktok }}" target="_blank">TikTok</a>
        {% endif %}
      </div>
    </div>
  {% endif %}
{% endfor %}

</div>