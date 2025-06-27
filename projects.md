---
layout: default
title: Projects
permalink: /projects
---

<!-- Projects
- Business Analytics - DONE [12/24/24]
    - Pet Sales - DONE [12/24/24]
	⁃ Product Sales - DONE [12/24/24]
- Data Analysis - DONE [12/24/24]
	⁃ Excel - DONE [12/24/24]
	⁃ Tableau - DONE [12/24/24]
- General Programming - 
	⁃ Morse Code Translator (beautiful soup, selenium) - DONE [12/24/24]
	⁃ Book Library Project (flask-sqlalchemy, flask) - DONE [12/24/24]
	⁃ Stock Trading (json, API requests) - DONE [12/29/24]
- Machine Learning/Data Science
    ⁃ KNN Breast Cancer - DONE [1/3/25]
	⁃ OLS vs. Gradient Descent - DONE [1/2/25]
	⁃ sustainability? => https://www.kaggle.com/datasets/mujtabamatin/air-quality-and-pollution-assessment (random forests) => 1/4-1/5?
    - Neural Networks? PyTorch? -->

<!-- THEN: Finish updating resume with work experience and projects -->

<!-- Finish stats course: 
    - sections 14, 11, 15 (what about sections 12-13?)
    ⁃ start doing the coding for the course
⁃	start the statistics book
	⁃	briefly review linear algebra (will have to finish course at some point)
-	Complete online course: feature engineering and cross validation (sections 11-12) -->

<!-- Schedule:
Saturday: start DS sustainability project
Sunday: Complete DS sustainability project, do neural networks project (?), update resume w/ QR code  --->

<div class="split-container">
    <div class="left-section">
        <!-- <div class="introduction"> -->
        <p>
            This page showcases a curated selection of projects covering:
        </p>
        <p><a href="#no-code-tools">No-code Tools</a></p>
        <p><a href="#business-analytics">Business Analytics</a></p>
        <p><a href="#general-programming">General Programming</a></p>
        <p><a href="#machine-learning">Machine Learning</a></p>
        <!-- </div> -->
    </div>
    <div class="right-section">
        <div id="no-code-tools">
            <h1>No-code Tools</h1>
        </div>
            <h2>Excel</h2>
                <h3>Space Missions Project</h3>
                    <p>A rich dataset from <a href="https://nextspaceflight.com" target="_blank">Next Space Flight</a> offers valuable insights into the history of space missions, including information on organizations, launch dates, and costs. As part of the 100 Days of Code Bootcamp on Udemy, I explored this dataset <em>using Excel (!)</em> to answer key questions:</p>
                        <p><strong>Top Launchers</strong>: Who launched the most missions in any given year?</p>
                        <p><strong>Cost Trends</strong>: How has the cost of a space mission varied over time?</p>
                        <p><strong>Seasonal Patterns</strong>: Which months are the most popular for launches?</p>
                        <p><strong>Mission Safety</strong>: Have space missions gotten safer, or has the chance of failure remained unchanged?</p>
                    <p>Explore the analysis and findings in the full project <a href="https://github.com/add0794/space_race/blob/8a1ebe36f9c88862b1bd0f89841e1685f2bf2cf5/README.md">here</a>.
                    </p>
                <h2>Tableau (VizQL)</h2>
                    <h3>Consumer Shopping Trends Project</h3>
                        <p>A Tableau story analyzes customer shopping trends, highlighting product preferences, demographic insights, and regional sales performance. Key findings include:</p>
                            <p>Men outspend women.</p>
                            <p>Medium-size clothing is preferred by most age groups.</p>
                            <p>Clothing leads product categories.</p>
                            <p>AL, CA, ID, IL, MT lead in state sales.</p>
                            <p>Promo codes have a <em>mixed</em> impact on average price.</p>
                            <p>Seasonal sales are consistent.</p>
                        <p>Explore the analysis and findings in the full project <a href="https://public.tableau.com/app/profile/alex.dubro/viz/CustomerShoppingTrends_17337058411000/Story1?publish=yes" target="_blank">here</a>.</p>
        <div id="business-analytics">
            <h1>Business Analytics</h1>
        </div>
            <h2>Pet Sales Project</h2>
                <p>PetMind aims to launch a monthly pet box subscription to enhance customer retention and foster brand loyalty. The analysis focuses on identifying patterns in product repurchases and their implications for sales. Key questions addressed include:</p>
                    <p><strong>Product Repurchases</strong>: How many products are being purchased multiple times?</p>
                    <p><strong>Sales Performance</strong>: Do products purchased repeatedly perform better in sales?</p>
                    <p><strong>Pet-Specific Trends</strong>: What products are frequently repurchased for different pet types?</p>
                <p>The project explores these questions using the provided sales dataset, offering insights to guide subscription product offerings. Full project details are available <a href="https://github.com/add0794/pet_sales_analysis/blob/1526e06fd0b8338261c4ab0718ad06529486883e/README.md">here</a>.</p>
            <h2>Product Sales Project</h2>
                <p>Pens and Partners plans to launch a new product line and seeks to evaluate the effectiveness of various sales tactics. The analysis investigates the following:</p>
                    <p><strong>Customer Engagement</strong>: How many customers engaged with each sales method?</p>
                    <p><strong>Revenue Distribution</strong>: What is the overall revenue spread, and how does it differ by sales method?</p>
                    <p><strong>Trends Over Time</strong>: Are there notable revenue differences over time for each method?</p>
                    <p><strong>Recommended Tactics</strong>: Which sales method is most effective, factoring in team effort and similar results?</p>
                <p>Insights from the dataset guide decisions on which sales tactics to prioritize for maximum impact. Full project details are available <a href="https://github.com/add0794/product_sales_analysis/blob/f85af366447686c8ff2b724e8aafee580a3c8707/README.md" target="_blank">here</a>.</p>
        <div id="general-programming">
            <h1>General Programming</h1>
        </div>
            <h2>Stock Trading Project (API Requests)</h2>
                <p>This <a href="https://github.com/add0794/stock-trading/" target="_blank">project</a> uses API requests to text you when a public company's stock significantly increases or decreases (i.e., by more or less than 5%). It tracks the percentage change, author, title, and content, and sends changes straight to your phone. The data comes from the stock's daily low. Make your investing life easier and perhaps stop using a certified financial analyst (CFA) to do the dirty work.
                </p>
            <h2>Testing International Morse Code Translator Project (Web Scraping)</h2>
                <p>This <a href="https://github.com/add0794/Testing-International-Morse-Code-Translator/tree/main" target="_blank">project</a> uses web scraping to test the accuracy of an <a href="https://morsecodetranslator.com/" target="_blank">International Morse Code translator</a>. By leveraging Beautiful Soup, it creates a Pandas DataFrame that translates English to <a href="https://www.hobby-hour.com/electronics/morse_code.php#google_vignette" target="_blank">Morse Code</a>. Selenium automates inputting text into the translator and verifies its output by cross-checking it against the custom Morse code alphabet.
                </p>
            <h2>Book Library Project (Flask Web Development)</h2>
                <p>This <a href="https://github.com/add0794/flask-sqlalchemy-library" target="_blank">project</a> leverages Flask-SQLAlchemy with SQLite to help you manage a personalized library of your favorite books. Use Pandas to perform SQL queries and generate tables tailored to your inputs. Ready for a reset? Clear the library in one simple step. Need a backup? Export your collection as a JSON file. Managing your book collection has never been more intuitive.
                </p>
            <h2>LGBTQ+ Rights in 2025: A Global Snapshot (Streamlit & Plotly)</h2>
                <p>This <a href="https://github.com/add0794/lgbtq-rights" target="_blank">project</a> leverages publicly available data to visualize and analyze the state of LGBTQ+ rights across the globe. It explores key legal indicators—such as marriage equality, adoption rights, and anti-discrimination protections—and examines how these correlate with democracy scores. Built with Streamlit and Plotly, the app highlights both progress and ongoing disparities in LGBTQ+ rights worldwide.</p>
        <div id="machine-learning">
            <h1>Machine Learning (Python)</h1>
        </div>
            <h2>Shallow Learning</h2>
            <h3>Ordinary Least Squares vs. Gradient Descent (Prediction)</h3>
                <p>This <a href="https://github.com/add0794/ordinary-least-squares-gradient-descent" target="_blank">project</a> evaluates when traditional statistical methods are as effective as machine learning algorithms. By comparing ordinary least squares (OLS) with gradient descent (GD), it develops a regression model for predicting academic performance.</p>
            <h3>Predicting Breast Cancer with K-Nearest Neighbors (KNN)</h3>
                <p>This <a href="https://github.com/add0794/knn-breast-cancer-prediction/tree/main" target="_blank">project</a> predicts breast cancer using KNN, finding the best <i>k</i> value based on the smallest difference in accuracy (and F1 score) between training and test sets.</p>
            <i>Note: Every machine learning project has a Jupyter notebook and an object-oriented programming (OOP) version. The Jupyter notebook version allows you to see how I completed the project while the OOP version allows you to apply the program to your own examples.</i>
    </div>
</div>

<nav class="main-nav">
  <a href="/" class="nav-item">Go to Home Page</a>
</nav>

<footer>
    <div class="social-links">
        <a href="https://www.linkedin.com/in/alexdubro/" aria-label="LinkedIn profile">
            <img src="linkedin-icon.png" alt="LinkedIn Icon" />
        </a>
        <a href="https://github.com/add0794" aria-label="GitHub profile">
            <img src="github-icon.png" alt="GitHub Icon" />
        </a>
        <a href="mailto:add0794@gmail.com" aria-label="Email">
            <img src="email-icon.png" alt="Email Icon" />
        </a>
    </div>
</footer>

<style>

/* Split text into left and right containers, with left scrolling */
.split-container {
  display: flex; /* Ensure sections are side by side */
  flex-direction: row; /* Aligns children horizontally */
  margin: 0;
  padding: 0;
}

.left-section {
  position: sticky; /* Makes the left section stick to the top of the viewport */
  top: 0; /* Adjust to account for any header if needed */
  height: 100vh; /* Makes it span the full height of the viewport */
  overflow-y: auto; /* Adds a scrollbar if content overflows */
  flex: 1; /* Allows it to take proportional width in a flex container */
  padding-right: 1rem; /* Adds space between the left and right sections */
  font-size: 1rem; /* Sets a readable font size */
  color: #555; /* Neutral color for text */
}

.right-section {
  flex: 2; /* Allows the right section to take more space */
}

/* Text size for paragraphs */
p {
  font-size: 1rem; /* Adjust this as needed */
  line-height: 1.5; /* Improves readability */
}

/* Navigation styling */

.main-nav {
    padding: 20px 0;
    margin-bottom: 30px;
}

.nav-item {
    text-decoration: none;
    color: #666;  /* Match the text color from your image */
    font-size: 18px;
    font-family: Arial, sans-serif;
    position: relative;
    transition: color 0.3s ease;
}
/* Hover effect */
.nav-item:hover {
    color: #1a4b8c;  /* Blue color from your header */
}
/* Active state */
.nav-item.active {
    color: #1a4b8c;
}
/* Underline effect on hover and active */
.nav-item::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: -5px;
    left: 0;
    background-color: #1a4b8c;
    transition: width 0.3s ease;
}
.nav-item:hover::after,
.nav-item.active::after {
    width: 100%;
}

/* General styling for the list */
.social-links {
    display: flex; /* Arrange items horizontally */
    gap: 15px; /* Add spacing between items */
    list-style: none; /* Remove bullets */
    padding: 0; /* Remove padding */
    margin: 0; /* Remove margin */
}

.social-links li {
    display: flex; /* Align icon and text */
    align-items: center; /* Vertically center items */
}

.social-links a {
    text-decoration: none; /* Remove underline from links */
    color: #333; /* Default text color */
    font-family: Arial, sans-serif;
    font-size: 14px;
}

.social-links a:hover {
    color: #0073b1; /* Change color on hover */
}

.social-links img {
    width: 20px; /* Set icon width */
    height: 20px; /* Set icon height */
    margin-right: 5px; /* Add spacing between icon and text */
}

/* Remove side and search bars */

#main-header {
    display: none;
}

.side-bar {
    display: none;
}

/* Center the main content text */
.main {
    margin-left: auto !important; /* Centers horizontally */
    margin-right: auto !important; /* Centers horizontally */
    max-width: 1200px !important;  /* Or your preferred max-width */
    padding: 0 2rem;  /* Add some padding on the sides */
    text-align: center; /* Centers the text */
}

/* Ensure header takes full width */
.main-header {
    width: 100% !important;
}

/* Adjust the main content container */
.main-content-wrap {
    padding-top: 2rem !important;
    padding-bottom: 2rem !important;
    text-align: center; /* Center text within content wrap */
}

/* Make sure content takes full width */
.main-content {
    width: 100% !important;
    margin: 0 auto !important; /* Centers content within its container */
    text-align: center; /* Centers the text */
}

/* Responsive design for smaller screens */
@media (max-width: 768px) {
    .intro {
        flex-direction: column;
        align-items: center;
    }

 .nav-links {
        flex-direction: column;
        align-items: center;
        gap: 15px;
    }

    .text {
        text-align: center;
    }

    .image img {
        max-width: 100%;
    }
}

</style>
