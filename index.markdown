---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---

<section class="hero">

  <h1>Via Consulting</h1>

  <p class="hero-subtitle">
    Helping individuals and businesses move forward with clarity and confidence.
  </p>

  <p class="hero-tagline">
    Mindset. Become Better. Great People
  </p>

  <div class="hero-buttons">
    <a href="/contact" class="btn secondary">
      Ask a Question
    </a>
    <a href="https://viaconsulting.youcanbook.me/" target="_blank" class="btn primary">
      Book Consultation
    </a>
  </div>

</section>


<section id="services" class="services">
  <h2>Our Services</h2>
  <p>Practical support across taxes, business, and everyday processes—all in one place.</p>

  <div class="service-group">
    <h3><i data-lucide="calculator"></i> Financial & Business</h3>
    <p>Tax preparation, bookkeeping, and business formation services.</p>
  </div>

  <div class="service-group">
    <h3><i data-lucide="file-text"></i> Administrative & Document Services</h3>
    <p>Notary services, immigration document assistance, and in-person USCIS interpreter support</p>
    <p class="disclaimer">
  ⚠️ Administrative assistance only. We are not attorneys and do not provide legal advice.
    </p>
  </div>

  <div class="service-group">
    <h3><i data-lucide="car"></i> DMV & Government Services</h3>
    <p>Registration renewals, REAL ID assistance, and DMV-related processes.</p>
  </div>

  <div class="service-group">
    <h3><i data-lucide="languages"></i> Translation Services</h3>
    <p>Document translation and notarized translations.</p>
  </div>

  <div class="service-group">
    <h3><i data-lucide="palette"></i> Creative & Branding</h3>
    <p>Graphic design, branding, and marketing materials through our network.</p>
  </div>

</section>

<section style="padding:40px 20px; background:#f9f9f9;">
  <h2>Built From Real Community Needs</h2>
  <p>
    Via Consulting was built from real, hands-on experience helping people navigate complex systems.
    What began inside a family-owned storefront in Elizabeth, New Jersey grew into a trusted resource
    for individuals seeking guidance, support, and solutions.
  </p>
  <p>
    Today, Via Consulting helps individuals and small businesses move forward with clarity—offering
    practical services across taxes, business formation, and administrative processes.
  </p>
</section>


<section id="contact" class="contact">
  <h2>Get in Touch</h2>

  <p class="contact-intro">
    Tell us your situation—we’ll help you find the right solution.
  </p>

  <p><strong>Bilingual support available (English & Spanish)</strong></p>

  <div class="contact-info">
    <p>
      <strong>Phone:</strong>
      <a href="tel:19082421884">(908) 242-1884</a>
    </p>
    <p>
      <strong>WhatsApp:</strong>
      <a href="https://wa.me/19082421884" target="_blank">Message us</a>
    </p>
    <p>
      <strong>Email:</strong>
      <a href="mailto:vimroger@gmail.com">vimroger@gmail.com</a>
    </p>
    <p>
      <strong>Instagram:</strong>
      <a href="https://www.instagram.com/viaconsultingusa/" target="_blank">
        @viaconsultingusa
      </a>
    </p>
  </div>

  <div class="contact-actions">
    <a href="https://viaconsulting.youcanbook.me/" target="_blank" class="btn primary">
      Book Consultation
    </a>
  </div>
</section>


<!-- <section id="network" class="network">
  <h2>Our Network</h2>
  <p>
    Via Consulting collaborates with a network of independent professionals
    to provide clients with access to specialized services.
  </p>

  <div class="network-list">
    {% for person in site.network %}
      <div class="network-item">

        {% if person.pic %}
          <img src="{{ person.pic | relative_url }}" alt="{{ person.name }}">
        {% endif %}

        <h3>{{ person.name }}</h3>
        <p><strong>{{ person.role }}</strong></p>
        <p>{{ person.description }}</p>

        <div class="socials">
          {% if person.instagram %}
            <a href="{{ person.instagram }}" target="_blank">Instagram</a>
          {% endif %}

          {% if person.tiktok %}
            <a href="{{ person.tiktok }}" target="_blank">TikTok</a>
          {% endif %}

          {% if person.facebook %}
            <a href="{{ person.facebook }}" target="_blank">Facebook</a>
          {% endif %}
        </div>

      </div>
    {% endfor %}
  </div>
</section> -->
