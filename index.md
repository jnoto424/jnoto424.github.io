layout: default

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
    font-size: clamp(2.8rem, 7vw, 4.75rem);
    line-height: 1;
    letter-spacing: -0.05em;
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
  <p class="hero-eyebrow">Data Analytics · Business Intelligence · Systems Analysis</p>

  <h1>Joseph Noto</h1>

  <h2>Computer Science Graduate Student at the University of Pennsylvania</h2>

  <p class="hero-description">
    I combine computer science, data analytics, and business information systems
    to solve business problems, improve processes, and turn data into actionable
    insights.
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

## Featured Projects

### Global Health & Life Expectancy Analysis

Big Data Analytics and Machine Learning project focused on using World Bank Health, Nutrition, and Population Statistics to find significant predictors of life expectancy.

Steps included filtering and cleaning the raw dataset, grouping countries together using K-Means clustering, and running different linear regression models on the data to find which one performed the best.

Overall, our model using health indicators as well as regional and time data was the most effective in predicting life expectancy.

**Technologies:** Python, Pandas, Scikit-learn, Matplotlib, Google Colab

### Technical News Search Engine

Programming and Data Structure project that involved processing a set of 100 technology-related articles for analysis.

Implemented Object Oriented Programming to read articles and process different article concepts. Added analytical features including article search, top trending topics over a certain time period, popularity of a specific topic over a period, and general database statistics/analysis. Built a menu interface over these features to allow for simple querying and analysis.

**Technologies:** Java, Eclipse

[LinkedIn] [Resume]
