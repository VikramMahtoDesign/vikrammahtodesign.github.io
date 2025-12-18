---
layout: about
title: About
permalink: /
subtitle: "<span style='color: #0056b3; font-weight: bold;'>Mechanical Design Engineer</span>"

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
 
---

I work on Power Transformer Tank and External Design (up to 765 kV), focusing on CAD automation, standardization, and technical drawings.

<div class="mt-5">
  <h3 style="border-bottom: 2px solid #007bff;; display: inline-block; padding-bottom: 5px;">Tech Stack</h3>
  
 <div class="row">
    <div class="col-sm-4">
      <h5 class="font-weight-bold">CAD & Design</h5>
      <ul style="list-style-type: none; padding-left: 0;">
        <li>• Siemens NX</li>
        <li>• Creo Parametric</li>
        <li>• AutoCAD</li>
      </ul>
    </div>

    <div class="col-sm-4">
      <h5 class="font-weight-bold">Simulation</h5>
      <ul style="list-style-type: none; padding-left: 0;">
        <li>• ANSYS Workbench</li>
        <li>• Creo Simulate</li>
        <li>• Hypermesh</li>
      </ul>
    </div>

    <div class="col-sm-4">
      <h5 class="font-weight-bold">Automation</h5>
      <ul style="list-style-type: none; padding-left: 0;">
        <li>• C# (NX Open)</li>
        <li>• Creo Toolkit (C++)</li>
        <li>• Pro/PROGRAM</li>
      </ul>
    </div>
  </div>

  
</div>

<div class="row mt-5 justify-content-center">

  <div class="col-md-3 mb-3">
    <a href="{{ '/experience/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="background-color: #eaf6ff; border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_experience.jpg' | relative_url }}" class="card-img-top p-3" alt="Experience" style="height: 150px; object-fit: contain;">
        <div class="card-body text-center p-2">
          <h4 class="card-title font-weight-bold mb-0">Experience</h4>
          <p class="card-text text-muted small mt-1">Work History & CV</p>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-3 mb-3">
    <a href="{{ '/projects/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="background-color: #eaf6ff; border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_projects.jpg' | relative_url }}" class="card-img-top p-3" alt="Projects" style="height: 150px; object-fit: contain;">
        <div class="card-body text-center p-2">
          <h4 class="card-title font-weight-bold mb-0">Projects</h4>
          <p class="card-text text-muted small mt-1">Design Automation & CAD</p>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-3 mb-3">
    <a href="{{ '/blog/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="background-color: #eaf6ff; border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_blog.jpg' | relative_url }}" class="card-img-top p-3" alt="Blog" style="height: 150px; object-fit: contain;">
        <div class="card-body text-center p-2">
          <h4 class="card-title font-weight-bold mb-0">Blog</h4>
          <p class="card-text text-muted small mt-1">Updates & Thoughts</p>
        </div>
      </div>
    </a>
  </div>

  <div class="col-md-3 mb-3">
    <a href="{{ '/teaching/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="background-color: #eaf6ff; border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_teaching.jpg' | relative_url }}" class="card-img-top p-3" alt="Teaching" style="height: 150px; object-fit: contain;">
        <div class="card-body text-center p-2">
          <h4 class="card-title font-weight-bold mb-0">Teaching</h4>
          <p class="card-text text-muted small mt-1">Tutorials & Guides</p>
        </div>
      </div>
    </a>
  </div>

</div>

<div class="mt-5 mb-5 p-4 text-center" style="background-color: white; border-radius: 15px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
  <h3 class="font-weight-bold">Let's Connect</h3>
  <p class="text-muted">Open to opportunities in Mechanical Design & Automation.</p>
  
  <div class="mt-3">
    <a href="mailto:vikrammahto129@gmail.com" class="btn btn-outline-primary mr-2" style="border-radius: 50px; padding: 10px 25px;">
      <i class="fas fa-envelope"></i> Email Me
    </a>
    <a href="https://linkedin.com/in/vikram-mahto" class="btn btn-primary" style="border-radius: 50px; padding: 10px 25px;">
      <i class="fab fa-linkedin"></i> LinkedIn
    </a>
  </div>
</div>

<style>
  <style>
  /* 1. Background Colors */
  body {
    background-color: #f8f9fa !important;
  }
  body.dark-mode {
    background-color: #121212 !important;
  }

  /* 2. FORCE FULL WIDTH (The Fix for Empty Space) */
  @media (min-width: 900px) { 
    .container {
      max-width: 85% !important;  /* Stretches content to the edges */
      width: 85% !important;
    }
    
    /* Adjusts the main content wrapper to allow full width */
    article.post {
      max-width: 85% !important;
    }
  }

  /* 3. Intro Text */
  h1.post-title::before {
    content: "Hey there, I am";
    display: block;
    font-size: 20px;
    font-weight: 400;
    color: #0056b3;
    margin-bottom: 5px;
    line-height: 1.2;
  }

  /* 4. Profile Picture Position */
  @media (min-width: 1200px) {
    .profile {
      float: right;
      margin-top: -150px !important; 
      margin-right: 10px;
      z-index: 10;
    }
  }
  /* 6. Navigation Bar Improvements */
  
  /* Make the bar taller */
  .navbar {
    padding-top: 20px !important;
    padding-bottom: 20px !important;
  }

  /* Style the links */
  .navbar-nav .nav-item .nav-link {
    font-size: 18px !important;       /* Bigger, easier to read */
    font-weight: 500 !important;      /* Slightly thicker font */
    margin-left: 15px !important;     /* Space between items */
    margin-right: 15px !important;
    color: #4a4a4a !important;        /* Dark Grey text (Professional) */
    text-transform: capitalize !important; /* Forces "blog" -> "Blog" */
  }

  /* Color change on Hover */
  .navbar-nav .nav-item .nav-link:hover {
    color: #007bff !important;        /* Turns Blue when you touch it */
  }
  
  /* Highlight the "Active" page (Current Page) */
  .navbar-nav .nav-item.active .nav-link {
    color: #007bff !important;
    font-weight: bold !important;
  }
</style>
