---
layout: default
title: Fall 2026 Schedule
---

# Fall 2026 Schedule of Events

{% assign schedule_empty = site.static_files | where: "path", "/assets/illustrations/schedule-empty.png" | first %}

<div class="schedule-status" role="status">
  <div class="schedule-status-copy">
    <p class="eyebrow">Fall 2026</p>
    <h2>Schedule coming soon</h2>
    <p>The 10U schedule is being finalized. Practices, game dates, locations, and start times will be posted here as soon as they are confirmed.</p>
  </div>
  {% if schedule_empty %}
    <img class="schedule-status-art" src="{{ "/assets/illustrations/schedule-empty.png" | relative_url }}" alt="" aria-hidden="true">
  {% endif %}
</div>

## Details to Confirm

- <img class="schedule-detail-icon-image" data-icon="practice" src="{{ "/assets/icons/schedule-practice.svg" | relative_url }}" alt="" aria-hidden="true"><span>Practice start date and recurring days/times</span>
- <img class="schedule-detail-icon-image" data-icon="game" src="{{ "/assets/icons/schedule-game.svg" | relative_url }}" alt="" aria-hidden="true"><span>League, opponents, and game dates</span>
- <img class="schedule-detail-icon-image" data-icon="field" src="{{ "/assets/icons/schedule-field.svg" | relative_url }}" alt="" aria-hidden="true"><span>Field locations and game times</span>
- <img class="schedule-detail-icon-image" data-icon="tournament" src="{{ "/assets/icons/schedule-tournament.svg" | relative_url }}" alt="" aria-hidden="true"><span>Tournament or playoff format</span>
- <img class="schedule-detail-icon-image" data-icon="clock" src="{{ "/assets/icons/schedule-clock.svg" | relative_url }}" alt="" aria-hidden="true"><span>Registration fees, gate fees, and team responsibilities</span>
- <img class="schedule-detail-icon-image" data-icon="calendar" src="{{ "/assets/icons/schedule-calendar.svg" | relative_url }}" alt="" aria-hidden="true"><span>Applicable governing-body rules, age requirements, and bat regulations</span>
