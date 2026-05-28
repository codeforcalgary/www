---
layout: default
title: Home
description: We build civic tech projects to make Calgary better for everyone.
---

<section id="mission" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Our Mission</h2>
    <p class="lead text-center">
      Code for Calgary empowers technologists, designers, and engaged citizens to build digital tools that improve life in {{ site.location | default: "Calgary" }}.
      We focus on transparent, accessible, and inclusive civic technology that supports collaboration between residents and local government.
    </p>
  </div>
</section>

<section id="projects" class="py-5 bg-light">
  <div class="container">
    <h2 class="text-center mb-5">Current Projects</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">CTrain Companion</h5>
            <p class="card-text">Real-time train arrival data, service alerts, and platform accessibility info for Calgary's transit users.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">City Budget Visualizer</h5>
            <p class="card-text">Making Calgary’s annual budget transparent and interactive to help residents understand where funding goes.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow-sm">
          <div class="card-body">
            <h5 class="card-title">Calgary Service Map</h5>
            <p class="card-text">Mapping out essential community services — including housing, food access, and mental health resources.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="join" class="py-5">
  <div class="container text-center">
    <h2 class="mb-4">Join the Movement</h2>
    <p class="lead mb-4">
      Whether you're a developer, designer, data nerd, or community advocate — there's a place for you in building a better {{ site.location | default: "Calgary" }}.
    </p>
    <a href="#" class="btn btn-primary btn-lg">Join Our Discord</a>
  </div>
</section>
