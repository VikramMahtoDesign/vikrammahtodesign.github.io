---
layout: page
title: Projects
permalink: /projects/
description: Automation projects.
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
    /* CHANGED: Updated border to match Experience page (Blue, 2px) */
    border: 2px solid #007bff;
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.2s, box-shadow 0.2s;
  }
  .project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    /* Border is already blue, but we keep the shadow */
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
      
      <h3 style="color: #333; font-weight: 800;">CAD Library</h3>
      
      <div class="mb-3 mt-2">
        <span class="tech-badge">Creo Toolkit</span>
        <span class="tech-badge">C++</span>
        <span class="tech-badge">Library</span>
        <span class="tech-badge">Automation</span>
      </div>

      <p style="color: #555; font-size: 15px; line-height: 1.6;">
This video showcases a Creo Toolkit-based automation tool designed to centralize the CAD model library and streamline the design process. The tool enables automatic component assembly from a designated directory, eliminating manual navigation. It also allows users to move and delete components, ensuring design consistency.
A key feature demonstrated is the automatic creation and removal of cutouts when assembling and deleting a component. While the demo uses a simple assembly, the tool is especially beneficial for larger, complex models.
      </p>

    </div>

    <div class="col-md-5">
      <div class="video-container">
        <iframe 
          src="https://www.youtube.com/embed/OXruP7GIyoQ" 
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
      
      <h3 style="color: #333; font-weight: 800;">AutoUnbend Using Creo Toolkit With Drawing Creation</h3>
      
      <div class="mb-3 mt-2">
        <span class="tech-badge">Creo Toolkit</span>
        <span class="tech-badge">C++</span>
        <span class="tech-badge">Sheetmetals</span>
        <span class="tech-badge">Drawing</span>
      </div>

      <p style="color: #555; font-size: 15px; line-height: 1.6;">
        This tool, built using the Creo Toolkit API, automates the process of unbending bent plates and cylindrical turrets for manufacturing. It converts solid parts into sheet metal, unbends them.The tool also automates drawing creation and generates views of both the original and unbent parts, streamlining the workflow.
      </p>

    </div>

    <div class="col-md-5">
      <div class="video-container">
        <iframe 
          src="https://www.youtube.com/embed/b2cDPgZ1oqc" 
          title="Project Video" 
          allowfullscreen>
        </iframe>
      </div>
    </div>

  </div>
</div>
