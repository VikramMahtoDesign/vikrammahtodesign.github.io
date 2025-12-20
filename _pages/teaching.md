---
layout: page
title: Learning
permalink: /learning/
nav: true
nav_order: 5
description: Technologies and tools I am currently exploring.
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

  /* --- Learning Card Styles --- */
  .learning-card {
    background-color: #ffffff;
    border: 2px solid #007bff; /* Signature Blue Border */
    border-radius: 12px;
    overflow: hidden;
    height: 100%;
    transition: transform 0.2s, box-shadow 0.2s;
    display: flex;
    flex-direction: column;
    text-decoration: none; /* Removes underline from links */
  }
  
  .learning-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 25px rgba(0, 123, 255, 0.15);
    text-decoration: none;
  }

  /* Image Area */
  .learning-img-container {
    height: 160px;
    background-color: #f1f3f5;
    overflow: hidden;
    position: relative;
    border-bottom: 1px solid #eaeaea;
  }
  .learning-img-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* Content Area */
  .learning-body {
    padding: 18px;
    display: flex;
    flex-direction: column;
    flex-grow: 1;
  }

  /* Status Badge (e.g., "In Progress") */
  .status-badge {
    background-color: #fff3cd;
    color: #856404;
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

  .learning-title {
    font-size: 18px;
    font-weight: 700;
    color: #333;
    margin-bottom: 8px;
  }
  
  .learning-text {
    font-size: 14px;
    color: #666;
    line-height: 1.5;
    margin-bottom: 15px;
  }
</style>

<div class="row">

  <div class="col-md-4 mb-4">
    <a href="{{ '/learning/nx-open/' | relative_url }}" class="learning-card">
      <div class="learning-img-container">
         <img src="https://images.unsplash.com/photo-1555949963-ff9fe0c870eb?auto=format&fit=crop&w=600&q=80" alt="NX Open">
      </div>
      <div class="learning-body">
        <span class="status-badge">In Progress</span>
        <h3 class="learning-title">NX Open Automation</h3>
        <p class="learning-text">
          Learning to automate Siemens NX using C# and the NX Open API. Building custom journals and plugins.
        </p>
      </div>
    </a>
  </div>

  <div class="col-md-4 mb-4">
    <a href="#" class="learning-card" style="opacity: 0.6; cursor: default;">
      <div class="learning-img-container">
         <img src="https://images.unsplash.com/photo-1515879218367-8466d910aaa4?auto=format&fit=crop&w=600&q=80" alt="Python">
      </div>
      <div class="learning-body">
        <span class="status-badge" style="background-color: #e2e3e5; color: #383d41;">Planned</span>
        <h3 class="learning-title">Advanced Python</h3>
        <p class="learning-text">
          Future plans to dive deeper into data analysis libraries.
        </p>
      </div>
    </a>
  </div>

</div>
