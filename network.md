---
layout: default
title: Our Network
permalink: /network/
---

# Our Network

Via Consulting collaborates with a network of trusted professionals to provide clients with access to specialized services.

From design and branding to administrative and business support, our network allows us to deliver solutions tailored to each client’s needs.

---

<div class="network-list">

  {% assign sorted_network = site.network | sort: "order" %}

  {% for person in sorted_network %}
    {% if person.published != false %}
      <div class="network-item">
        {% if person.pic %}
          <img src="{{ person.pic | relative_url }}" alt="{{ person.name }}">
        {% endif %}
        <h3>{{ person.name }}</h3>
        <p><strong>{{ person.role }}</strong></p>
        <p>{{ person.description }}</p>
        {% if person.portfolio %}
          <p class="network-action">
            <a href="{{ person.portfolio | relative_url }}" target="_blank">
              See Portfolio
            </a>
          </p>
        {% endif %}
        <div class="socials">
          {% if person.instagram %}
            <a href="{{ person.instagram }}" target="_blank">Instagram</a>
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