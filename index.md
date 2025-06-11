<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kaike Vieira – Data Analyst & BI Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <!-- Optional: Custom Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #ffffff;
      color: #222;
    }
    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    h1, h2, h3 {
      margin-top: 0;
    }
    a {
      color: #007acc;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    ul {
      padding-left: 1.2rem;
    }
    .hero {
      text-align: center;
      background: linear-gradient(to right, #1e3c72, #2a5298);
      color: white;
    }
    .hero img {
      width: 120px;
      border-radius: 50%;
      margin-bottom: 1rem;
    }
    .button-link {
      display: inline-block;
      margin: 0.5rem;
      padding: 0.6rem 1.2rem;
      background-color: white;
      color: #1e3c72;
      border-radius: 5px;
      font-weight: 600;
      text-decoration: none;
      border: 2px solid white;
    }
    .button-link:hover {
      background-color: #e0e0e0;
    }
    iframe {
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: gray;
      background-color: #fafafa;
    }
  </style>
</head>
<body>

<!-- Hero Section -->
<section class="hero">
  <img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e" alt="Professional Analytics Image">
  <h1>Kaike Vieira</h1>
  <p style="font-size: 1.2rem;">Data Analyst | BI Developer | Process Optimizer</p>
  <p>Transforming complex data into actionable insights using Power BI, SQL, Python, and Excel.</p>
  <div>
    <a href="https://www.linkedin.com/in/kaikevieira/" class="button-link"><i class="fab fa-linkedin"></i> LinkedIn</a>
    <a href="https://github.com/kaikesvieira" class="button-link"><i class="fab fa-github"></i> GitHub</a>
  </div>
</section>

<!-- About Section -->
<section style="background-color: #f7f7f7;">
  <h2><i class="fas fa-user"></i> About Me</h2>
  <p>
    With over 4 years of experience in both engineering and analytics roles, I’ve developed a keen eye for optimizing processes and delivering data-driven results.
    I hold a Graduate Certificate in Data Analytics for Business from St. Clair College and a Mechanical Engineering degree from Brazil.
  </p>
  <p>
    Currently, I work for the City of Windsor and COBS Bread, where I manage workforce data and analyze daily sales trends. My past experience includes building KPIs and dashboards in SQL, Excel, and Power BI to reduce equipment failure and improve operations.
  </p>
</section>

<!-- Portfolio Section -->
<section>
  <h2><i class="fas fa-chart-line"></i> Featured Projects</h2>

  <div>
    <h3>📦 Sales Forecasting – E-Grocery Industry</h3>
    <p>Forecasted 14-day sales using time series models, improving inventory accuracy and reducing waste.</p>
    <ul>
      <li><strong>Tools:</strong> Python (Scikit-learn, LightGBM), PowerPoint, APIs</li>
      <li><a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/tree/main/sales-forecasting-egrocery">View on GitHub</a></li>
    </ul>
  </div>

  <div>
    <h3>🛍️ Customer Segmentation – Retail Dataset</h3>
    <p>Segmented customers by purchasing behavior to support personalized marketing strategies.</p>
    <ul>
      <li><strong>Tools:</strong> Python (EDA, Clustering, Plotly)</li>
      <li><a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/tree/main/marketing2-customer-segmentation">View on GitHub</a></li>
    </ul>
  </div>

  <div>
    <h3>💰 Financial Analysis – Canadian Banks (Interactive Dashboard)</h3>
    <iframe title="Financial Analytics Project" width="100%" height="500" 
            src="https://app.powerbi.com/reportEmbed?reportId=1f7f554e-734f-4f01-898e-8d3557a33728&autoAuth=true&ctid=c986676f-9b39-4d08-b4f8-a668e0e8c6a5" 
            frameborder="0" allowFullScreen="true"></iframe>
    <p>
      Performed descriptive financial analysis of Canada's Big 5 Banks using Power BI and Alpha Vantage API. 
      Transformed raw API data into structured tables and created interactive dashboards visualizing profitability, growth trends, and bank comparisons.
    </p>
    <ul>
      <li><strong>Tools:</strong> Power BI, DAX, Alpha Vantage API, Excel</li>
      <li><a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/tree/main/financial-powerbi-big5-analysis">View Project on GitHub</a></li>
      <li><a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/blob/main/financial-powerbi-big5-analysis/Big5CanadianBanks_Presentation.pptx">View Project Presentation</a></li>
    </ul>
  </div>
</section>

<!-- Resume Section -->
<section style="background-color: #f0f0f0;">
  <h2><i class="fas fa-briefcase"></i> Resume Highlights</h2>
  <ul>
    <li><strong>Current Roles:</strong> Timekeeper (City of Windsor), Sales Assistant (COBS Bread)</li>
    <li><strong>Technical Tools:</strong> Power BI, Python, SQL, Excel, Git, SharePoint</li>
    <li><strong>Certifications:</strong> AWS Cloud Practitioner, Google Data Analytics</li>
    <li><strong>Education:</strong> St. Clair College (Data Analytics), Universidade Paulista (Engineering)</li>
  </ul>
</section>

<!-- Call to Action -->
<section style="text-align: center; background-color: #e8f0fe;">
  <h2><i class="fas fa-envelope"></i> Let’s Connect</h2>
  <p>If you're looking for a motivated data analyst who can bring clarity to your data and communicate findings effectively—let’s talk!</p>
  <a href="mailto:vieirakaike@icloud.com" class="button-link"><i class="fas fa-paper-plane"></i> Email Me</a>
  <a href="https://www.linkedin.com/in/kaikevieira/" class="button-link"><i class="fab fa-linkedin"></i> LinkedIn</a>
</section>

<!-- Footer -->
<footer>
  © 2025 Kaike Vieira. All rights reserved.
</footer>

</body>
</html>

