---
layout: single
title: "Applications"
permalink: /applications/
author_profile: true
---

This page highlights software demonstrations and applications developed by the Smart Mobility Lab for smart mobility systems.

<style>
.application-card {
  border: 1px solid var(--global-border-color);
  border-radius: 8px;
  padding: 1.1rem;
  margin: 1.25rem 0 1.75rem;
  background: var(--global-bg-color);
  color: var(--global-text-color);
}
.application-card h2 {
  margin-top: 0;
  color: var(--global-text-color);
}
.application-card p {
  color: var(--global-text-color);
}
.application-card img {
  display: block;
  max-width: 100%;
  height: auto;
  border-radius: 6px;
  margin-top: 0.75rem;
}
.application-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: 0.85rem;
}
.application-card details {
  margin-top: 0.85rem;
}
.application-card summary.btn {
  display: inline-block;
  cursor: pointer;
  list-style: none;
}
.application-card summary.btn::-webkit-details-marker {
  display: none;
}
.application-card iframe {
  width: 100%;
  aspect-ratio: 16 / 9;
  height: auto;
  min-height: 360px;
  border: 0;
  border-radius: 6px;
  background: #000;
  margin-top: 0.75rem;
}
@media (max-width: 640px) {
  .application-card iframe {
    min-height: 220px;
  }
}
</style>

<div class="application-card">
  <h2>Featured Applications</h2>
  <p>This page highlights software demonstrations and applications developed by the Smart Mobility Lab for smart mobility systems.</p>
  <div class="application-actions">
    <a class="btn btn--primary" href="#charge-express">Charge Express</a>
    <a class="btn btn--primary" href="#charging-station-optimization-tool">Charging Station Optimization Tool</a>
    <a class="btn btn--primary" href="#large-scale-taxi-simulation-platform">Large-scale Taxi Simulation Platform</a>
    <a class="btn btn--primary" href="#taxi-idle-cruising-app">Taxi Idle Cruising App</a>
  </div>
</div>

<div class="application-card" id="charge-express">
  <h2>Charge Express</h2>
  <p>By 2025, HKG plans to expand the number of charging stations to 5,000, nearly doubling the current amount. This app allows users to easily find the locations and details of both charging stations and taxi stands. It provides navigation and guides users on the best routes to these sites, helping them avoid wasting time.</p>
  <details>
    <summary class="btn btn--primary">View Poster</summary>
    <img src="/images/charge-express-poster.png" alt="Charge Express poster">
  </details>
</div>

<div class="application-card" id="charging-station-optimization-tool">
  <h2>Charging Station Optimization Tool</h2>
  <p>This tool is specially designed for charging pile operators. It can calculate the optimal location, number, capacity and cost of charging piles based on real traffic data in Hong Kong. The tool also supports optimization based on user-defined budgets, optimized focus on electricity, layout size and other elements.</p>
  <div class="application-actions">
    <a class="btn btn--primary" href="https://chargingonlinetool-9bbf69ab2832.herokuapp.com">Go to Toolbox</a>
  </div>
  <img src="/images/charging-station-optimization-tool.png" alt="Charging Station Optimization Tool screenshot">
</div>

<div class="application-card" id="large-scale-taxi-simulation-platform">
  <h2>Large-scale Taxi Simulation Platform</h2>
  <p>The large-scale simulation platform supports model training and evaluation for ride-sourcing operations on real transportation networks. It can simulate agent behaviours and vehicle movements, and provides portals for testing optimization and reinforcement learning algorithms for on-demand matching, idle vehicle repositioning, and dynamic pricing.</p>
  <iframe src="https://www.youtube.com/embed/SuLIKpV2_F4?start=1" title="Large-scale Taxi Simulation Platform" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen loading="lazy"></iframe>
</div>

<div class="application-card" id="taxi-idle-cruising-app">
  <h2>Taxi Idle Cruising App</h2>
  <p>A substantial share of taxi operating time is spent on idle cruising while searching for passengers. This app recommends idle searching and cruising routes for taxi drivers in Hong Kong to mitigate supply-demand imbalance and improve operating efficiency. The recommendation algorithm is supported by tailored reinforcement learning methods.</p>
  <iframe src="https://www.youtube.com/embed/1B7JK_JBoL0" title="Taxi Idle Cruising App" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen loading="lazy"></iframe>
  <details>
    <summary class="btn btn--primary">Download App</summary>
    <img src="/images/idle-cruising-download-qr.png" alt="Taxi Idle Cruising App download QR codes">
  </details>
</div>
