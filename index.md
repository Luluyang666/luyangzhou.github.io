---
layout: default
title: Home
---

<style>
  /* Full-page background styling */
  .hero {
      background-image: url('/assets/images/background.jpg'); /* Replace with your actual image name */
      background-size: cover;
      background-position: center;
      height: 100vh; /* Full viewport height */
      display: flex;
      justify-content: center;
      align-items: center;
      color: black; /* Text color */
      text-align: center;
      flex-direction: column;
  }
  
  .hero h1 {
      font-size: 4em;
      font-weight: bold;
      margin: 0;
  }

  .hero h2 {
      font-size: 1.5em;
      margin-top: 10px;
  }

  /* Style the navigation buttons */
  .hero nav a {
      margin: 10px;
      padding: 10px 20px;
      background: rgba(255, 255, 255, 0.7); /* Transparent background for the buttons */
      border-radius: 10px;
      text-decoration: none;
      font-size: 1.2em;
      color: black;
      transition: background-color 0.3s ease;
  }

  .hero nav a:hover {
      background-color: #ddd;
  }
</style>

<div class="hero">
    <!-- Centered Name and University -->
    <h1>Luyang Zhou</h1>
    <h2>University of York</h2>

    <!-- Navigation Bar with Links -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#publications">Publications</a>
        <a href="#contact">Contact Me</a>
    </nav>
</div>

<!-- Markdown Content -->
## About Me {#about}

My research focuses on doctor-patient interactions, with a particular interest in pediatric consultations.

I also explore multimodal conversation analysis (CA), investigating how non-verbal cues, gestures, and visual elements contribute to communication in healthcare settings.

## Publications {#publications}

(Your publications go here)

## Contact Me {#contact}

You can reach me at [ftb512@york.ac.uk](mailto:ftb512@york.ac.uk).
