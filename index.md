
<style>
  .hero {
    padding: 3.75rem 0 3.25rem;
    border-bottom: 1px solid #e5e7eb;
    margin-bottom: 3rem;
  }

  .hero-eyebrow {
    margin: 0 0 0.8rem;
    font-size: 0.88rem;
    font-weight: 700;
    letter-spacing: 0.09em;
    text-transform: uppercase;
    color: #6b7280;
  }

  .hero h1 {
    margin: 0;
    font-size: clamp(2.2rem, 5vw, 3.5rem);
    line-height: 1;
    letter-spacing: -0.04em;
    color: #111827;
  }

  .hero h2 {
    margin: 1rem 0 1.35rem;
    font-size: clamp(1.2rem, 2.5vw, 1.65rem);
    line-height: 1.35;
    font-weight: 600;
    color: #374151;
  }

  .hero-description {
    max-width: 760px;
    margin: 0 0 1.9rem;
    font-size: 1.08rem;
    line-height: 1.75;
    color: #4b5563;
  }

  .hero-links {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
  }

  .hero-links a {
    display: inline-block;
    padding: 0.65rem 1rem;
    border: 1px solid #d1d5db;
    border-radius: 8px;
    color: #111827;
    background: #fff;
    text-decoration: none;
    font-weight: 600;
    transition: all 0.15s ease;
  }

  .hero-links a:hover {
    border-color: #111827;
    background: #f9fafb;
    text-decoration: none;
  }

  .hero-links a.primary {
    color: #fff;
    background: #111827;
    border-color: #111827;
  }

  .hero-links a.primary:hover {
    background: #374151;
    border-color: #374151;
  }

  @media (max-width: 600px) {
    .hero {
      padding: 2.25rem 0 2rem;
    }

    .hero h1 {
      font-size: 2.7rem;
    }

    .hero-description {
      font-size: 1rem;
    }
  }
</style>

<section class="hero">
  <p class="hero-eyebrow">Data Analytics · Business Intelligence · Information Systems</p>

  <h1>Joseph Noto</h1>

  <h2>Computer Science Graduate Student at the University of Pennsylvania</h2>

  <p class="hero-description">
    I combine data analytics, computer science, and information systems
    to solve business problems, provide valuable insight, and make a positive impact.
  </p>

  <div class="hero-links">
    <a class="primary" href="https://github.com/jnoto424" target="_blank" rel="noopener noreferrer">GitHub</a>
    <a href="https://www.linkedin.com/in/joseph-noto-mis/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
  </div>
</section>

{{ content }}

## Skills

Python · SQL · PySpark · Pandas · Scikit-learn · Java · AWS · Machine Learning

## Education

**University of Pennsylvania**  
Master of Applied Science in Computer Science

**Pennsylvania State University**  
Bachelor of Science in Management Information Systems

<!-- Add this section after your introduction/skills section -->

<style>
  .project-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1.25rem;
    margin: 1.5rem 0 3rem;
  }

  .project-card {
    display: flex;
    flex-direction: column;
    min-height: 310px;
    padding: 1.5rem;
    border: 1px solid #e5e7eb;
    border-radius: 12px;
    background: #ffffff;
    box-shadow: 0 2px 8px rgba(17, 24, 39, 0.04);
    transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
  }

  .project-card:hover {
    transform: translateY(-3px);
    border-color: #d1d5db;
    box-shadow: 0 8px 24px rgba(17, 24, 39, 0.08);
  }

  .project-type {
    margin: 0 0 0.65rem;
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.07em;
    text-transform: uppercase;
    color: #6b7280;
  }

  .project-card h3 {
    margin: 0 0 0.75rem;
    font-size: 1.35rem;
    line-height: 1.3;
    color: #111827;
  }

  .project-card p {
    margin: 0 0 1rem;
    line-height: 1.65;
    color: #4b5563;
  }

  .project-tech {
    margin-top: auto !important;
    padding-top: 1rem;
    font-size: 0.88rem !important;
    font-weight: 600;
    color: #374151 !important;
  }

  .project-links {
    display: flex;
    gap: 0.65rem;
    margin-top: 0.9rem;
  }

  .project-links a {
    display: inline-block;
    padding: 0.55rem 0.8rem;
    border: 1px solid #d1d5db;
    border-radius: 7px;
    font-size: 0.88rem;
    font-weight: 600;
    text-decoration: none;
    color: #111827;
  }

  .project-links a:hover {
    border-color: #111827;
    background: #f9fafb;
    text-decoration: none;
  }

  @media (max-width: 700px) {
    .project-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<h2>Featured Projects</h2>

<div class="project-grid">

  <article class="project-card">
    <p class="project-type">Data Analytics · Machine Learning</p>
    <h3>Global Health &amp; Life Expectancy Analysis</h3>
    <p>
      Analyzed World Bank health indicators to identify factors associated
      with life expectancy. Cleaned and transformed large datasets, applied
      K-Means clustering, and evaluated regression models to predict life expectancy.
    </p>
    <p class="project-tech">
      Python · Pandas · Scikit-learn · Matplotlib
    </p>
    <div class="project-links">
      <a href="#" target="_blank" rel="noopener noreferrer">Read More</a>
    </div>
  </article>

  <article class="project-card">
    <p class="project-type">Programming · Data Structures</p>
    <h3>Technical News Search Engine</h3>
    <p>
      Built a Java application to process and analyze 100 technology-related
      articles. Implemented object-oriented programming and analytical features
      for article search, trending topics, popularity analysis, and database statistics.
    </p>
    <p class="project-tech">
      Java · Object-Oriented Programming · Data Structures · Eclipse
    </p>
    <div class="project-links">
      <a href="#" target="_blank" rel="noopener noreferrer">Read More</a>
    </div>
  </article>

  <article class="project-card">
    <p class="project-type">Database Management · Database Design</p>
    <h3>Relational Hospital Database</h3>
    <p>
      Designed an Entity-Relationship Diagram (ERD) modeling relationships between entities within a sample hospital. Built normalized tables with relational constraints to ensure data integrity and proper data loading. Performed aggregation queries across multiple tables to analyze hospital operations and generate insights.
    </p>
    <p class="project-tech">
      SQL · MySQL · ERD 
    </p>
    <div class="project-links">
      <a href="#" target="_blank" rel="noopener noreferrer">Read More</a>
    </div>
  </article>


</div>
