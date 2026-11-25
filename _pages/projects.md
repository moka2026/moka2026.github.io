---
permalink: /projects/
title: "Projects"
layout: splash
author_profile: false
classes: wide
---
<style>
  .projects-masthead {
    position: relative;
    width: 100vw;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
    margin-bottom: 5em;
    height: 40vh;
    min-height: 225px;
    max-height: 450px;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #fff;
  }
.projects-masthead img {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: 1;
}
.projects-masthead::after {
  content: "";
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.45);
  z-index: 2;
}
  
  /* Masthead header "h1" and subheader "p" */
  .projects-masthead-content {
  position: relative;
    z-index: 3;
    max-width: 800px;
    padding: 0 20px;
  }
  .projects-masthead-content h1 {
    font-size: 2.5em;
    margin-bottom: 0.3em;
    color: #ffffff;
  }
  .projects-masthead-content p {
    font-size: 1.2em;
    margin-bottom: 1em;
  }


  
  /* TWO-COLUMN PROJECT ROW COMPONENT */
  .projects-project-row {
    display: flex;
    align-items: center;
    gap: 2.5em;
    max-width: 1000px;
    margin: 3.5em auto;
    padding-bottom: 3.5em;
    border-bottom: 1px solid #eaeaea;
      }
  .projects-project-row:last-of-type {
    border-bottom: none;
    padding-bottom: 0;
  }
  /* Photo column */
  .projects-project-row-image { 
    flex: 0 0 380px;
    max-width: 100%; 
  }
  .projects-project-row-image img {
  width: 100%;
    height: auto;
    aspect-ratio: 16 / 10;
    object-fit: cover;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
    display: block;
  }
  /* Content column */
  .projects-project-row-content {
  flex: 1;
    text-align: left;
      }
  .projects-project-row-content h2 {
    margin-top: 0;
    margin-bottom: 0.4em;
    border-bottom: none;
    }
  .projects-project-row-content h2 a {
    color: inherit;
    text-decoration: none;
}
  .projects-project-row-content p {
    margin-bottom: 1.2em;
    }

  /* Mobile compatibility */
  @media (max-width: 768px) {
    .projects-project-row {
      flex-direction: column;
      gap: 1.5em;
      margin: 2.5em auto;
      padding-bottom: 2.5em;
    }
    .projects-project-row-image {
      flex: none;
      width: 100%;
    }
</style>


<div class="projects-masthead">
  <img src="/assets/images/balloon-group.jpg" alt="Weather balloon group prepared for launch.">
  <div class="projects-masthead-content">
    <h1>Projects</h1>
    </div>
  </div> 

<!-- Project rows -->
<div class="projects-project-row">
  <div class="projects-project-row-image">
  <a href="/projects/uv-ir-sensors/">
  <img src="/assets/images/eclipse.jpg" alt="Eclipse thumbnail">
  </a>
  </div>
  <div class="projects-project-row-content">
  <h2><a href="/projects/uv-ir-sensors/">Low-cost eclipse UV/IR telemetry</a></h2>
    
  <p>Developed and deployed payload telemetry to measure high-altitude changes in UV and IR radiation during a total solar eclipse.</p>      </div>
</div>
