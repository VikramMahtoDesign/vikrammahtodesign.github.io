---
layout: about
title: about
permalink: /
subtitle: <a>Mechanical Design Engineer</a>. 

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
 
---

I work on power transformer tank and external design (up to 765 kV),focusing on CAD automation, standardization, and technical drawings & documentation.

<div class="mt-5">
  <h3 style="border-bottom: 2px solid #5cb85c; display: inline-block; padding-bottom: 5px;">Tech Stack</h3>
  
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
  
</div>

<div class="row mt-5">

  <div class="col-sm-4 mb-3">
    <a href="{{ '/projects/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="background-color: #f6ddfb; border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_projects.jpg' | relative_url }}" class="card-img-top p-3" alt="Projects" style="height: 150px; object-fit: contain;">
        <div class="card-body text-center p-2">
          <h4 class="card-title font-weight-bold mb-0">Projects</h4>
          <p class="card-text text-muted small mt-1">Design Automation & CAD</p>
        </div>
      </div>
    </a>
  </div>

  <div class="col-sm-4 mb-3">
    <a href="{{ '/blog/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="background-color: #f6ddfb; border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_blog.jpg' | relative_url }}" class="card-img-top p-3" alt="Blog" style="height: 150px; object-fit: contain;">
        <div class="card-body text-center p-2">
          <h4 class="card-title font-weight-bold mb-0">Blog</h4>
          <p class="card-text text-muted small mt-1">Updates & Thoughts</p>
        </div>
      </div>
    </a>
  </div>

  <div class="col-sm-4 mb-3">
    <a href="{{ '/teaching/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="background-color: #f6ddfb; border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_teaching.jpg' | relative_url }}" class="card-img-top p-3" alt="Teaching" style="height: 150px; object-fit: contain;">
        <div class="card-body text-center p-2">
          <h4 class="card-title font-weight-bold mb-0">Teaching</h4>
          <p class="card-text text-muted small mt-1">Tutorials & Guides</p>
        </div>
      </div>
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
      max-width: 95% !important;  /* Stretches content to the edges */
      width: 95% !important;
    }
    
    /* Adjusts the main content wrapper to allow full width */
    article.post {
      max-width: 100% !important;
    }
  }

  /* 3. Intro Text */
  h1.post-title::before {
    content: "Hey there, I am";
    display: block;
    font-size: 20px;
    font-weight: 400;
    color: #6c757d;
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
</style>
