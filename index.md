<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kaike Vieira – Data Analyst & BI Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

  <!-- Optional: Google Font -->
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
    h1 {
      font-size: 2.8rem;
      font-weight: 700;
    }
    h2 {
      font-size: 2rem;
      font-weight: 700;
      margin-top: 2rem;
      margin-bottom: 1rem;
      border-left: 6px solid #1e3c72;
      padding-left: 0.6rem;
      color: #1e3c72;
    }
    h3 {
      font-size: 1.5rem;
      font-weight: 600;
      margin-top: 1.5rem;
      color: #333;
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
      margin-top: 1rem;
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
  <h1>Kaike Vieira</h1>
  <p style="font-size: 1.2rem;">Data & Business Intelligence Analyst | Process Optimizer</p>
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
    With over 4 years of experience in both engineering and analytics roles, I’ve developed a keen eye for optimizing processes and delivering data-driven results. I hold a Graduate Certificate in Data Analytics for Business from St. Clair College and a degree in Mechanical Engineering from a Brazilian university.
  </p>
  <p>
    Currently, I work for the City of Windsor and COBS Bread, where I manage workforce data and analyze daily sales trends while assisting customers. My past experience includes building KPIs and dashboards in SQL, Excel, and Power BI to reduce equipment failure and improve operations.
  </p>
</section>

<!-- Portfolio Section -->
<section>
  <h2><i class="fas fa-chart-line"></i> Featured Projects</h2>

  <div>
    <h3>📦 Sales Forecasting – E-Grocery Industry</h3>
    <!-- Project Thumbnail -->
    <img src="assets/xgboost-thumbnail.png" alt="Sales Forecasting Thumbnail" style="width:100%; border-radius: 10px; margin-bottom: 1rem;" />
    <p>
      This project forecasts 14-day sales for a grocery warehouse in Frankfurt using advanced time series modeling. The goal was to reduce waste and improve inventory planning by capturing seasonal, promotional, and weather-driven sales patterns.
    </p>
    <p>
      <strong>Key Insights:</strong> Sales peaked on Fridays and dipped during holidays or store closures. Discounts often boosted sales but did not show a direct linear correlation. The "Fruit and Vegetables" category dominated total sales. Recursive Feature Elimination proved critical in selecting engineered features that significantly improved model performance.
    </p>
      <p>
      <strong>Conclusion:</strong> XGBoost outperformed LightGBM in accuracy, achieving the lowest MAE and strongest R², but showed mild overfitting on high sales volumes. The combination of lag features, Fourier transforms, and calendar effects led to high model interpretability. This approach provides a scalable foundation for real-world sales forecasting in retail environments.
    </p>
      <ul>
      <li><strong>Objective:</strong> Predict sales with high accuracy to reduce overstocking/understocking.</li>
      <li><strong>Data:</strong> Historical sales (2 years), calendar (holidays), inventory, weather (Visual Crossing API)</li>
      <li><strong>Features:</strong> Lag (7, 14, 365), rolling means, Fourier transforms, target & one-hot encoding</li>
      <li><strong>Models:</strong> XGBoost (best), LightGBM</li>
      <li><strong>Tech Stack:</strong> Python, Scikit-learn, Optuna, Google Colab, VS Code</li>
      <li><a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/tree/main/sales-forecasting-egrocery">View on GitHub</a></li>
    </ul>
      <!-- Code Thumbnail -->
    <img src="assets/metrics-thumbnail.png" alt="Code Snapshot" style="width:100%; border-radius: 10px; margin-top: 1rem;" />
      <!-- Download Button -->
    <a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/blob/main/sales-forecasting-egrocery/Final_Project_Report.pdf" class="button-link" style="margin-top: 1rem; display: inline-block;">
      📄 Download Project Report
    </a>
  </div>



  <div>
    <h3>💰 Financial Analysis – Canadian Banks (Video Demo)</h3>
    <!-- Embedded Video -->
    <video width="100%" height="425" controls style="border-radius: 10px; margin-bottom: 1rem;">
      <source src="assets/financial-analysis-report-video.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p>
      This video demo presents a Power BI dashboard built to analyze Canada's Big 5 Banks using financial KPIs from Alpha Vantage API data. It showcases dynamic charts for profitability, performance trends, and bank comparisons. The data was cleaned, modeled, and visualized using Power BI, DAX, and Excel. Unfortunately, due to restrictions associated with my student account, I am unable to embed the dashboard publicly.  
    </p>
    <ul>
      <li><strong>Tools:</strong> Power BI, DAX, Alpha Vantage API, Excel</li>
      <li><a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/tree/main/financial-powerbi-big5-analysis">Download report from GitHub</a></li>
      <li><a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/blob/main/financial-powerbi-big5-analysis/Big5CanadianBanks_Presentation.pdf">View Project Presentation</a></li>
    </ul>
  
  </div>
    <div>
    <h3>🚗 User Engagement & Churn Analysis – Waze App</h3>
    <!-- Project Thumbnail -->
      <p>
      Relationship between minutes and kms driven
      </p>
    <img src="assets/waze-thumbnail.png" alt="Waze Project Thumbnail" style="width:100%; border-radius: 10px; margin-bottom: 1rem;" />
    <p>
      This project explored Waze user engagement and churn behavior using a labeled dataset of app activity. It applies data preprocessing, statistical analysis, segmentation, and predictive modeling to support retention strategy recommendations.
    </p>
    <p>
      <strong>Key Insights:</strong> Users with longer tenure showed significantly lower churn risk. Android users had different engagement patterns compared to iOS users. High churn correlated with reduced app usage metrics such as drives and minutes driven.
    </p>
    <p>
      <strong>Conclusion:</strong> By using a Decision Tree classifier and visual data exploration, the analysis revealed churn predictors and enabled targeted retention actions like device-specific marketing and reactivation campaigns.
    </p>
    <ul>
      <li><strong>Objective:</strong> Predict user churn and optimize marketing for retention</li>
      <li><strong>Data:</strong> User engagement logs, churn labels, device type, tenure</li>
      <li><strong>Models:</strong> Decision Tree Classifier</li>
      <li><strong>Visuals:</strong> Correlation matrix, feature importance, churn distribution, customer attrition profile</li>
      <li><strong>Tech Stack:</strong> Python (Pandas, scikit-learn), Jupyter Notebook, PowerPoint</li>
      <li><a href="https://github.com/kaikesvieira/kaikevieira-data-portfolio/tree/main/marketing-waze-analysis">View on GitHub</a></li>
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



