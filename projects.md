---
layout: default
title: Projects
permalink: /projects
---

# No-code Tools

## Excel

### Space Missions Project

A rich dataset from [Next Space Flight](https://nextspaceflight.com) offers valuable insights into the history of space missions, including information on organizations, launch dates, and costs. As part of the 100 Days of Code Bootcamp on Udemy, I explored this dataset *using Excel (!)* to answer key questions:

- **Top Launchers**: Who launched the most missions in any given year?  
- **Cost Trends**: How has the cost of a space mission varied over time?  
- **Seasonal Patterns**: Which months are the most popular for launches?  
- **Mission Safety**: Have space missions gotten safer, or has the chance of failure remained unchanged?  

Explore the analysis and findings in the full project [here](https://github.com/add0794/space_race/blob/8a1ebe36f9c88862b1bd0f89841e1685f2bf2cf5/README.md).

## Tableau (VizQL)

### Consumer Shopping Trends Project

A Tableau story analyzes customer shopping trends, highlighting product preferences, demographic insights, and regional sales performance. Key findings include:
- Men outspend women.
- Medium-size clothing is preferred age group.
- Clothing leads product categories.
- AL, CA, ID, IL, MT lead in state sales.
- Promo code has a *mixed* impact on average price.
- Seasonal sales is consistent.

Explore the analysis and findings in the full project [here](https://public.tableau.com/app/profile/alex.dubro/viz/CustomerShoppingTrends_17337058411000/Story1?publish=yes).

---

# Programming Tools

## Business Analytics

### Pet Sales Project

PetMind aims to launch a monthly pet box subscription to enhance customer retention and foster brand loyalty. The analysis focuses on identifying patterns in product repurchases and their implications for sales. Key questions addressed include:  
- **Product Repurchases**: How many products are being purchased multiple times?  
- **Sales Performance**: Do products purchased repeatedly perform better in sales?  
- **Pet-Specific Trends**: What products are frequently repurchased for different pet types?  

The project explores these questions using the provided sales dataset, offering insights to guide subscription product offerings. Full project details are available [here](https://github.com/add0794/pet_sales_analysis/blob/1526e06fd0b8338261c4ab0718ad06529486883e/README.md).

### Product Sales Project

Pens and Partners plans to launch a new product line and seeks to evaluate the effectiveness of various sales tactics. The analysis investigates the following:  
- **Customer Engagement**: How many customers engaged with each sales method?  
- **Revenue Distribution**: What is the overall revenue spread, and how does it differ by sales method?  
- **Trends Over Time**: Are there notable revenue differences over time for each method?  
- **Recommended Tactics**: Which sales method is most effective, factoring in team effort and similar results?  

Insights from the dataset guide decisions on which sales tactics to prioritize for maximum impact. Full project details are available [here](https://github.com/add0794/product_sales_analysis/blob/f85af366447686c8ff2b724e8aafee580a3c8707/README.md).

---

## General Programming

### Stock Trading Project (API Requests)

This [project](https://github.com/add0794/stock-trading/) uses API requests to text you when a public company's stock significantly increases or decreases (i.e. by more or less than 5%). It can be time-consuming to follow a company's stock value, but you still want to earn a little extra income from investing. By tracking the percentage change, author, title, and content, you'll get changes straight to your phone -- all you need is to read text messages! The data comes from the stock's daily low. Make your investing life easier, and perhaps, stop using a certified financial analyst (CFA) to do the dirty work.

### Testing International Morse Code Translator Project (Web Scraping)

This [project](https://github.com/add0794/Testing-International-Morse-Code-Translator/tree/main) uses web scraping to test the accuracy of an [International Morse Code translator](https://morsecodetranslator.com/). By leveraging Beautiful Soup, it creates a Pandas DataFrame that translates English to [Morse Code](https://www.hobby-hour.com/electronics/morse_code.php#google_vignette). Selenium automates inputting text into the translator and verifies its output by cross-checking it against the custom Morse code alphabet. The project highlights the effectiveness of web scraping, automation, and data validation in testing online tools, while showcasing Morse code’s historical relevance and modern applications in ensuring message integrity.

### Book Library Project (Flask Web Development)

This [project](https://github.com/add0794/flask-sqlalchemy-library) leverages Flask-SQLAlchemy with SQLite to help you manage a personalized library of your favorite books. Rate your books from 1 to 10 and effortlessly add, edit, or delete entries. Use Pandas to perform SQL queries and generate tables tailored to your inputs. Ready for a reset? Clear the library in one simple step. Need a backup? Export your collection as a JSON file. Managing your book collection has never been more intuitive.

---

# Machine Learning (Python)

## Shallow Learning

### Ordinary Least Squares vs. Gradient Descent (Prediction)

This [project](https://github.com/add0794/ordinary-least-squares-gradient-descent) evaluates when traditional statistical methods are as effective as machine learning algorithms. By comparing ordinary least squares (OLS) with gradient descent (GD) to develop a regression model for predicting academic performance, the research guides analysts in selecting the most appropriate modeling approach. The analysis additionally explores alternative machine learning techniques like ridge regression (ℓ2 norm), lasso regression (ℓ1 norm), and cross-validation to illuminate the nuanced decision between traditional and machine learning algorithms.

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

body {
    font-family: Arial, sans-serif;
    color: #4A4A4A;
    line-height: 1.6;
}

/* Header section with name and title */
.header-name {
    color: #2E8B57;  /* Dark blue for name */
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 5px;
}

.job-title {
    color: #2E8B57;  /* Lighter blue for job title */
    font-size: 20px;
    margin-bottom: 20px;
}

/* Section headers with blue background */
.section-header {
    background-color: #2E8B57;  /* Dark blue background */
    color: white;
    padding: 8px 15px;
    margin: 25px 0 15px 0;
    font-size: 18px;
    font-weight: bold;
}

/* Content sections */
.section-content {
    margin-bottom: 20px;
    color: #666;  /* Grey color for main text */
}

/* List styling */
ul {
    margin: 0;
    padding-left: 20px;
}

li {
    color: #666;
    margin-bottom: 8px;
}

/* Styling for the intro header and image */
.intro {
    display: flex;
    align-items: center;
    gap: 30px;
}

.text {
    flex: 1;
}

.image img {
    max-width: 300px;
    height: auto;
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
