---
layout: home
title: "Home"
---

<div class="hero-section">
  <div class="hero-content">
    <h1 class="hero-title">Welcome to My Portfolio</h1>
    <h2 class="hero-subtitle">Bahar Lawter</h2>
    <p class="hero-description">
      Former Math Teacher | Aspiring Software Engineer | Lifelong Learner
    </p>
    <div class="hero-buttons">
      <a href="/about/" class="btn btn-primary">About Me</a>
      <a href="/projects/" class="btn btn-secondary">View Projects</a>
    </div>
  </div>
  <div class="hero-image">
    <img src="/assets/headshot.png" alt="Bahar Lawter" />
  </div>
</div>

<style>
  .hero-section {
    display: flex;
    align-items: center;
    padding: 4rem 0;
    min-height: 60vh;
    flex-wrap: wrap;
  }
  
  .hero-content {
    flex: 1;
    min-width: 300px;
    padding-right: 2rem;
  }
  
  .hero-image {
    flex: 1;
    text-align: center;
    min-width: 300px;
  }
  
  .hero-image img {
    max-width: 350px;
    width: 100%;
    border-radius: 50%;
    box-shadow: 0 4px 20px rgba(0,0,0,0.1);
  }
  
  .hero-title {
    font-size: 2.5rem;
    font-weight: 700;
    color: #1a7f8e;
    margin-bottom: 0.5rem;
  }
  
  .hero-subtitle {
    font-size: 2rem;
    font-weight: 400;
    color: #2d3e50;
    margin-bottom: 1rem;
  }
  
  .hero-description {
    font-size: 1.2rem;
    color: #666;
    margin-bottom: 2rem;
    line-height: 1.6;
  }
  
  .hero-buttons {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
  }
  
  .btn {
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 500;
    transition: all 0.3s ease;
    display: inline-block;
  }
  
  .btn-primary {
    background-color: #1a7f8e;
    color: white;
  }
  
  .btn-primary:hover {
    background-color: #156b77;
    color: white;
  }
  
  .btn-secondary {
    background-color: transparent;
    color: #1a7f8e;
    border: 2px solid #1a7f8e;
  }
  
  .btn-secondary:hover {
    background-color: #1a7f8e;
    color: white;
  }
  
  @media (max-width: 768px) {
    .hero-section {
      flex-direction: column;
      text-align: center;
    }
    
    .hero-content {
      padding-right: 0;
      margin-bottom: 2rem;
    }
    
    .hero-title {
      font-size: 2rem;
    }
    
    .hero-subtitle {
      font-size: 1.5rem;
    }
  }
</style>

---

## Recent Updates

<div class="updates-section">
  <div class="update-item">
    <h3> Healthy Lifestyle App —Full Stack</h3>
    <p>
    - Integrated public API and Google Gemini
   -Built Api endpoints and Database 
 -Tech Stack: HTML, CSS, JavaScript, Java, MySql, Spring Boot, React, public APIs, Netlify, GitHub</p>
  </div>
  
  <div class="update-item">
    <h3> ToDo List App — FrontEnd App</h3>
    <p>
    -Implemented Angular Components and two way binding 
    -Tech Stack: TypeScript, Angular, VS Code,  GitHub</p>
  </div>
  
  <div class="update-item">
    <h3>Financial App-FrontEnd</h3>
    <p>
    -Interactive financial calculator and blog platform
    -Integrated Routing
    -sTech Stack: TypeScript, Angular, VS Code,  GitHub.</p>
  </div>
</div>

<style>
  .updates-section {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 3rem 0;
  }
  
  .update-item {
    background: #f8f9fa;
    padding: 1.5rem;
    border-radius: 8px;
    border-left: 4px solid #1a7f8e;
  }
  
  .update-item h3 {
    color: #1a7f8e;
    margin-bottom: 0.5rem;
  }
  
  .update-item p {
    color: #666;
    line-height: 1.6;
  }
</style>
