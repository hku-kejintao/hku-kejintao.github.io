---
layout: single
title: "Applications"
permalink: /applications/
author_profile: true
---

This page highlights software demonstrations and applications developed by the Smart Mobility Lab for smart mobility systems.

<style>
.application-card {
  border: 1px solid #e6e6e6;
  border-radius: 8px;
  padding: 1.1rem;
  margin: 1.25rem 0 1.75rem;
  background: #fff;
}
.application-card h2 {
  margin-top: 0;
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
  <h2>Large-scale Taxi Simulation Platform</h2>
  <p>The large-scale simulation platform supports model training and evaluation for ride-sourcing operations on real transportation networks. It can simulate agent behaviours and vehicle movements, and provides portals for testing optimization and reinforcement learning algorithms for on-demand matching, idle vehicle repositioning, and dynamic pricing.</p>
  <iframe src="https://www.youtube.com/embed/_9vbkoNTXJg" title="Driver Order Matching Simulation" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen loading="lazy"></iframe>
</div>

<div class="application-card">
  <h2>Taxi Idle Cruising App</h2>
  <p>A substantial share of taxi operating time is spent on idle cruising while searching for passengers. This app recommends idle searching and cruising routes for taxi drivers in Hong Kong to mitigate supply-demand imbalance and improve operating efficiency. The recommendation algorithm is supported by tailored reinforcement learning methods.</p>
  <iframe src="https://www.youtube.com/embed/TPHBZbt8B4A" title="Urban Navigation for Ride-Hailing Drivers in Hong Kong" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen loading="lazy"></iframe>
</div>
