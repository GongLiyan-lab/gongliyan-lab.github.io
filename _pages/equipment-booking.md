---
layout: page
title: Equipment Booking
permalink: /equipment-booking/
nav: true
nav_order: 8
---

<style>
  .equipment-intro {
    margin-bottom: 32px;
    line-height: 1.7;
  }

  .equipment-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 24px;
    margin-top: 28px;
  }

  .equipment-card {
    border: 1px solid #e5e5e5;
    border-radius: 16px;
    padding: 26px;
    background: var(--global-bg-color);
    box-shadow: 0 4px 14px rgba(0, 0, 0, 0.06);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .equipment-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 22px rgba(0, 0, 0, 0.10);
  }

  .equipment-type {
    font-size: 14px;
    color: var(--global-text-color-light);
    margin-bottom: 8px;
  }

  .equipment-name {
    font-size: 21px;
    font-weight: 600;
    margin-bottom: 10px;
  }

  .equipment-description {
    font-size: 15px;
    line-height: 1.6;
    margin-bottom: 22px;
    min-height: 48px;
  }

  .equipment-button {
    display: inline-block;
    padding: 9px 18px;
    border-radius: 8px;
    background: var(--global-theme-color);
    color: white !important;
    text-decoration: none !important;
    font-weight: 500;
    transition: opacity 0.2s ease;
  }

  .equipment-button:hover {
    opacity: 0.85;
  }

  .booking-note {
    margin-top: 36px;
    padding: 18px 20px;
    border-left: 4px solid var(--global-theme-color);
    background: rgba(128, 128, 128, 0.06);
    border-radius: 6px;
    line-height: 1.7;
  }

  @media (max-width: 768px) {
    .equipment-grid {
      grid-template-columns: 1fr;
    }

    .equipment-description {
      min-height: auto;
    }
  }
</style>

<div class="equipment-intro">
Please check the current schedule before using shared laboratory equipment and make a reservation in advance.
</div>

<div class="equipment-grid">

  <!-- HFsafe1200LC Left -->
  <div class="equipment-card">
    <div class="equipment-type">Biological Safety Cabinet</div>
    <div class="equipment-name">HFsafe1200LC (A2) - Left</div>

    <div class="equipment-description">
      Shared biological safety cabinet for routine sterile cell culture operations.
    </div>

    <a
      class="equipment-button"
      href="#"
    >
      Book Now
    </a>
  </div>

  <!-- HFsafe1200LC Right -->
  <div class="equipment-card">
    <div class="equipment-type">Biological Safety Cabinet</div>
    <div class="equipment-name">HFsafe1200LC (A2) - Right</div>

    <div class="equipment-description">
      Shared biological safety cabinet for routine sterile cell culture operations.
    </div>

    <a
      class="equipment-button"
      href="#"
    >
      Book Now
    </a>
  </div>

  <!-- ABI QuantStudio 3 -->
  <div class="equipment-card">
    <div class="equipment-type">Real-Time PCR System</div>
    <div class="equipment-name">ABI QuantStudio™ 3</div>

    <div class="equipment-description">
      Shared real-time PCR system for quantitative PCR experiments.
    </div>

    <a
      class="equipment-button"
      href="#"
    >
      Book Now
    </a>
  </div>

  <!-- MIX60-FL -->
  <div class="equipment-card">
    <div class="equipment-type">Fluorescence Microscope</div>
    <div class="equipment-name">MIX60-FL</div>

    <div class="equipment-description">
      Shared fluorescence microscope for routine bright-field and fluorescence imaging.
    </div>

    <a
      class="equipment-button"
      href="#"
    >
      Book Now
    </a>
  </div>

</div>

<div class="booking-note">
<strong>Booking policy:</strong>
Please reserve equipment before use, avoid overlapping reservations, and cancel your booking promptly if the instrument is no longer needed.
</div>
