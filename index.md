---
layout: default
title: Home
---

{% assign homepage_hero = site.static_files | where: "path", "/assets/illustrations/homepage-hero.png" | first %}

<section class="home-hero" aria-labelledby="home-hero-title">
  <div class="home-hero-copy">
    <p class="eyebrow">Sienna Skeeters · Fall 2026</p>
    <h1 id="home-hero-title">Welcome to the Sienna Skeeters!</h1>
    <p class="hero">⚾ Fueling passion, teamwork &amp; character</p>
  </div>

  {% if homepage_hero %}
    <div class="home-hero-art">
      <img src="{{ "/assets/illustrations/homepage-hero.png" | relative_url }}" alt="The Sienna Skeeters mascot celebrating youth baseball and teamwork">
    </div>
  {% else %}
    <div class="home-hero-art home-hero-art-fallback">
      <img src="{{ "/assets/skeeters-logo.png" | relative_url }}" alt="Sienna Skeeters baseball logo">
    </div>
  {% endif %}
</section>

## About the Team
We are a 10U youth travel baseball team from the Sienna community in Missouri City, Texas focused on developing great players—and even better kids. Whether it’s game day or practice, we bring hustle, heart, and grit! We prioritize fundamentals, teamwork, sportsmanship, and, above all, having fun!
{: .section-card }

## What We Value
- **Skill Development:** Helping players improve in all aspects of the game
- **Teamwork:** Teaching players how to work together
- **Character:** Building respectful, hard-working athletes
- **Family:** Creating memories and traditions for players and families
{: .section-card }

## Quick Facts
  
  - **Team Name:** Sienna Skeeters  
  - **Mascot:** The Mosquito 🦟  
  - **Age Group:** Fall 2026 10U
  - **Colors:** Navy, Gold, Sky Blue  
  - **Based In:** Missouri City, TX
{: .section-card }

---

## Team Store

Want to stock up on Skeeters swag? Check out our Team Store. Fall 2026 store details and deadlines will be posted here when confirmed.

[Visit the Team Store](https://siennaskeetersmerch.itemorder.com/shop/home/)

---

## Sponsorship

Please reach out via email if you're interested in sponsoring!

<div class="sponsorship-grid">
  <article class="sponsorship-card sponsorship-card-featured">
    <h3><img class="sponsor-tier-icon-image" data-sponsor-icon="grand-slam" src="{{ "/assets/icons/sponsor-grand-slam.svg" | relative_url }}" alt="" aria-hidden="true"><span class="sponsor-tier-name">Grand Slam Sponsor</span> <span class="sponsor-tier-price">$1,000</span></h3>
    <ul>
      <li>BBQ dinner (brisket, beans, potato salad)</li>
      <li>Logo or name on dugout banner</li>
      <li>Recognition on social media posts</li>
      <li>Two team hats and two team shirts</li>
    </ul>
  </article>

  <article class="sponsorship-card">
    <h3><img class="sponsor-tier-icon-image" data-sponsor-icon="no-hitter" src="{{ "/assets/icons/sponsor-no-hitter.svg" | relative_url }}" alt="" aria-hidden="true"><span class="sponsor-tier-name">No-Hitter Sponsor</span> <span class="sponsor-tier-price">$750</span></h3>
    <ul>
      <li>Logo or name on dugout banner</li>
      <li>Recognition on social media posts</li>
      <li>Two team hats and two team shirts</li>
    </ul>
  </article>

  <article class="sponsorship-card">
    <h3><img class="sponsor-tier-icon-image" data-sponsor-icon="golden-glove" src="{{ "/assets/icons/sponsor-golden-glove.svg" | relative_url }}" alt="" aria-hidden="true"><span class="sponsor-tier-name">Golden Glove Sponsor</span> <span class="sponsor-tier-price">$500</span></h3>
    <ul>
      <li>Recognition on social media posts</li>
      <li>One team hat and one team shirt</li>
    </ul>
  </article>

  <article class="sponsorship-card">
    <h3><img class="sponsor-tier-icon-image" data-sponsor-icon="home-run" src="{{ "/assets/icons/sponsor-home-run.svg" | relative_url }}" alt="" aria-hidden="true"><span class="sponsor-tier-name">Home Run Sponsor</span> <span class="sponsor-tier-price">$250</span></h3>
    <ul>
      <li>Recognition on social media posts</li>
      <li>One team hat and one team shirt</li>
    </ul>
  </article>

  <article class="sponsorship-card">
    <h3><img class="sponsor-tier-icon-image" data-sponsor-icon="double-play" src="{{ "/assets/icons/sponsor-double-play.svg" | relative_url }}" alt="" aria-hidden="true"><span class="sponsor-tier-name">Double Play Sponsor</span> <span class="sponsor-tier-price">$100</span></h3>
    <ul>
      <li>Recognition on social media posts</li>
    </ul>
  </article>
</div>

See the [Contact Us](#contact-us) section below to learn more.

---

## Contact Us

Interested in joining the team or have questions?  
**Email:** [info@sotxcreations.com](mailto:info@sotxcreations.com)  
**Coaches:** David Knudsen, Scott Moore, Derek Yelinek

---

## Follow Us

Stay up to date on games, events, and more:  
[Facebook](https://www.facebook.com/siennaskeeters) | [Twitter/X](https://twitter.com/siennaskeeters)
