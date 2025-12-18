---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Mechanical Design Engineer</a>. 

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
 
---

I work on power transformer tank and external design (up to 765 kV), 

focusing on CAD automation, standardization, and technical drawings & documentation.

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
      <div class="card h-100 shadow-sm" style="border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_projects.jpg' | relative_url }}" class="card-img-top" alt="Projects" style="height: 150px; object-fit: cover;">
        <div class="card-body text-center p-3">
          <h4 class="card-title font-weight-bold mb-0">Projects</h4>
          <p class="card-text text-muted small mt-1">Design Automation & CAD</p>
        </div>
      </div>
    </a>
  </div>

  <div class="col-sm-4 mb-3">
    <a href="{{ '/blog/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_blog.jpg' | relative_url }}" class="card-img-top" alt="Blog" style="height: 150px; object-fit: cover;">
        <div class="card-body text-center p-3">
          <h4 class="card-title font-weight-bold mb-0">Blog</h4>
          <p class="card-text text-muted small mt-1">Updates & Thoughts</p>
        </div>
      </div>
    </a>
  </div>

  <div class="col-sm-4 mb-3">
    <a href="{{ '/teaching/' | relative_url }}" style="text-decoration: none; color: inherit;">
      <div class="card h-100 shadow-sm" style="border-radius: 15px; overflow: hidden; transition: transform 0.2s;">
        <img src="{{ '/assets/img/card_teaching.jpg' | relative_url }}" class="card-img-top" alt="Teaching" style="height: 150px; object-fit: cover;">
        <div class="card-body text-center p-3">
          <h4 class="card-title font-weight-bold mb-0">Learning</h4>
          <p class="card-text text-muted small mt-1">Tutorials & Guides</p>
        </div>
      </div>
    </a>
  </div>

</div>

<style>
  /* 1. Make the background slightly grey to make cards pop */
  body {
    background-color: #f8f9fa !important;
  }


  /* 3. Dark Mode fix */
  body.dark-mode {
    background-color: #121212 !important;
  }

  /* 4. ADD THIS: "Hey there, I am" above your name */
  h1.post-title::before {
    content: "Hey there, I am";  /* The text you want to add */
    display: block;              /* Forces it to be on its own line above the name */
    font-size: 20px;             /* Size of the small text */
    font-weight: 400;            /* Normal font weight (not bold) */
    color: #6c757d;              /* Grey color */
    margin-bottom: 5px;          /* Space between this text and your name */
    line-height: 1.2;
  }
  /* 5. Move Profile Picture Up (Desktop Only) */
  @media (min-width: 1200px) {
    .profile {
      margin-top: -240px !important; /* Pulls the image up. Increase/Decrease this number to fit. */
      margin-right: 20px;            /* Adds a little space so it doesn't hit the scrollbar */
    }
  }
</style>
