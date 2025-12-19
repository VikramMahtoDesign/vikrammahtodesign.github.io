---
layout: page
title: Projects
permalink: /projects/
description: Key engineering and automation projects.
nav: true
nav_order: 3
---

<style>
  /* --- Navigation Bar Fix --- */
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

  /* --- Project Card Styles --- */
  .project-card {
    background-color: #ffffff;
    border: 1px solid #e0e0e0;
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    border-color: #007bff; /* Hover Blue Border */
  }
  
  /* Tech Stack Badges */
  .tech-badge {
    background-color: #eaf6ff;
    color: #0056b3;
    font-size: 12px;
    font-weight: 600;
    padding: 5px 10px;
    border-radius: 15px;
    margin-right: 5px;
    display: inline-block;
    margin-bottom: 5px;
  }

  /* Video Container (Responsive) */
  .video-container {
    position: relative;
    width: 100%;
    padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
    height: 0;
    overflow: hidden;
    background: #000;
  }
  .video-container iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }
</style>

<div class="card project-card mb-5 shadow-sm">
  <div class="row no-gutters">
    
    <div class="col-md-7 p-4 d-flex flex-column justify-content-center">
      
      <h3 style="color: #333; font-weight: 800;">Automated Tank Design System</h3>
      
      <div class="mb-3 mt-2">
        <span class="tech-badge">Creo Toolkit</span>
        <span class="tech-badge">C++</span>
        <span class="tech-badge">Automation</span>
      </div>

      <p style="color: #555; font-size: 15px; line-height: 1.6;">
        Developed a custom plugin for Creo Parametric that automates the generation of 3D tank models. 
        This tool reduced the design cycle time by <strong>40%</strong> and minimized human error in BOM generation.
        It features a custom UI built with OTK.
      </p>

     /* <div class="mt-3">
        <a href="#" class="btn btn-sm btn-outline-primary mr-2"><i class="fab fa-github"></i> View Code</a>
        <a href="#" class="btn btn-sm btn-outline-secondary"><i class="fas fa-file-alt"></i> Case Study</a>
      </div> */
    </div>

    <div class="col-md-5">
      <div class="video-container">
        <iframe 
          src="https://youtu.be/OXruP7GIyoQ" 
          title="Project Video" 
          allowfullscreen>
        </iframe>
      </div>
    </div>

  </div>
</div>

<div class="card project-card mb-5 shadow-sm">
  <div class="row no-gutters">
    
    <div class="col-md-7 p-4 d-flex flex-column justify-content-center">
      
      <h3 style="color: #333; font-weight: 800;">FEA Simulation Dashboard</h3>
      
      <div class="mb-3 mt-2">
        <span class="tech-badge">Python</span>
        <span class="tech-badge">Ansys API</span>
        <span class="tech-badge">Flask</span>
      </div>

      <p style="color: #555; font-size: 15px; line-height: 1.6;">
        Created a web-based dashboard to visualize stress analysis results for power transformers. 
        The system automatically pulls data from Ansys Workbench and generates compliance reports 
        according to IEEE standards.
      </p>

      <div class="mt-3">
        <a href="#" class="btn btn-sm btn-outline-primary mr-2"><i class="fab fa-github"></i> View Code</a>
      </div>
    </div>

    <div class="col-md-5">
      <div class="video-container">
        <iframe 
          src="https://www.youtube.com/embed/YOUR_VIDEO_ID_2" 
          title="Project Video" 
          allowfullscreen>
        </iframe>
      </div>
    </div>

  </div>
</div>
