---
layout: page
title: Blog
permalink: /blog/
nav: true
nav_order: 4
description: Thoughts on Engineering, Automation, and Life.
---

<style>
  /* --- Navigation Bar Consistency --- */
  .navbar {
    padding-top: 20px !important;
    padding-bottom: 20px !important;
  }
  .navbar-nav .nav-item .nav-link {
    font-size: 18px !important;
    font-weight: 500 !important;
    margin-left: 15px !important;
    margin-right: 15px !important;
    color: #4a4a4a !important;
    text-transform: capitalize !important;
  }
  .navbar-nav .nav-item .nav-link:hover {
    color: #007bff !important;
  }
  .navbar-nav .nav-item.active .nav-link {
    color: #007bff !important;
    font-weight: bold !important;
  }

  /* --- Header Tweaks (Left Aligned & Non-Bold) --- */
  header.post-header {
    margin-bottom: 40px !important;
    text-align: left !important;
  }
  header.post-header h1.post-title {
    font-weight: 400 !important;
    color: #333;
    margin-bottom: 5px;
  }
  header.post-header p.post-description {
    font-size: 16px !important;
    color: #666 !important;
    font-weight: 400;
    font-style: italic;
    display: block !important;
    margin-top: 0px;
  }

  /* --- Blog Card Styles --- */
  .blog-card {
    background-color: #ffffff;
    border: 2px solid #007bff;
    border-radius: 12px;
    overflow: hidden;
    height: 100%;
    transition: transform 0.2s, box-shadow 0.2s;
    display: flex;
    flex-direction: column;
    text-decoration: none; /* Removes underline */
  }
  
  .blog-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0, 123, 255, 0.15);
  }

  /* Image Area */
  .blog-img-container {
    height: 160px;
    background-color: #f1f3f5;
    overflow: hidden;
    position: relative;
  }
  .blog-img-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* Content Area */
  .blog-body {
    padding: 18px;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
  }

  /* Category Badge */
  .blog-category {
    background-color: #eaf6ff;
    color: #0056b3;
    font-size: 10px;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 1px;
    padding: 3px 8px;
    border-radius: 4px;
    display: inline-block;
    margin-bottom: 8px;
    width: fit-content;
  }

  /* Title & Date */
  .blog-title {
    font-size: 16px;
    font-weight: 700;
    color: #333;
    margin-bottom: 5px;
    line-height: 1.4;
  }
  .blog-date {
    font-size: 11px;
    color: #999;
    margin-bottom: 10px;
    display: block;
  }

  /* Read More Link */
  .blog-link {
    font-size: 13px;
    font-weight: 600;
    color: #007bff;
    text-decoration: none;
    display: flex;
    align-items: center;
    margin-top: auto;
  }
  .blog-link i {
    margin-left: 5px;
    transition: margin-left 0.2s;
  }
  .blog-link:hover i {
    margin-left: 8px;
  }
</style>


<div class="row">

  <div class="col-md-4 mb-4">
    <a href="{% post_url 2024-01-15-lifting-analysis %}" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1581092160562-40aa08e78837?auto=format&fit=crop&w=600&q=80" alt="FEA">
        </div>
        <div class="blog-body">
          <span class="blog-category">ANSYS / FEA</span>
          <h3 class="blog-title">Lifting Analysis of Transformer Tank Using Remote Points in ANSYS</h3>
          <span class="blog-date">Archive</span>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="{% post_url 2023-11-20-austenitic-steel %}" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1535970793551-3b56795453b3?auto=format&fit=crop&w=600&q=80" alt="Steel">
        </div>
        <div class="blog-body">
          <span class="blog-category">Materials</span>
          <h3 class="blog-title">Why Isn't Austenitic Stainless Steel Magnetic?</h3>
          <span class="blog-date">Archive</span>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="{% post_url 2023-09-10-charpy-test %}" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1576400806041-b93a0447a12b?auto=format&fit=crop&w=600&q=80" alt="Testing">
        </div>
        <div class="blog-body">
          <span class="blog-category">Testing</span>
          <h3 class="blog-title">Impact Test – Charpy V-Notch Test</h3>
          <span class="blog-date">Archive</span>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="{% post_url 2023-07-05-roarks-formulas %}" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1635070041078-e363dbe005cb?auto=format&fit=crop&w=600&q=80" alt="Formulas">
        </div>
        <div class="blog-body">
          <span class="blog-category">Validation</span>
          <h3 class="blog-title">Validating Roark’s Formulas for Stress and Strain: Fixed Rectangular Plate vs. ANSYS</h3>
          <span class="blog-date">Archive</span>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="{% post_url 2023-05-12-conservator-design %}" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1473642306788-b27b5003c267?auto=format&fit=crop&w=600&q=80" alt="Transformers">
        </div>
        <div class="blog-body">
          <span class="blog-category">Standards</span>
          <h3 class="blog-title">Conservator for Transformers: Standards & Calculations</h3>
          <span class="blog-date">Archive</span>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="{% post_url 2023-03-28-iso-12944 %}" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1618761714954-0b8cd0026356?auto=format&fit=crop&w=600&q=80" alt="Paint">
        </div>
        <div class="blog-body">
          <span class="blog-category">ISO Standards</span>
          <h3 class="blog-title">ISO 12944-1 & 2: Corrosion Protection for Steel Structure</h3>
          <span class="blog-date">Archive</span>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="{% post_url 2025-12-18-creo-toolkit %}" style="text-decoration: none;">
      <div class="blog-card">
        <div class="blog-img-container">
           <img src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=600&q=80" alt="Coding">
        </div>
        <div class="blog-body">
          <span class="blog-category">Automation</span>
          <h3 class="blog-title">Getting Started with Creo Toolkit</h3>
          <span class="blog-date">Recent Post</span>
          <span class="blog-link">Read Article <i class="fas fa-arrow-right"></i></span>
        </div>
      </div>
    </a>
  </div>

</div>
