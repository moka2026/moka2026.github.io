---
permalink: /projects/
title: "Projects"
layout: splash
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
</style>

<div class="projects-masthead">
  <img src="/assets/images/balloon-group.jpg" alt="Weather balloon group prepared for launch.">
  <div class="projects-masthead-content">
    <h1>Projects</h1>
    </div>
  </div> 
