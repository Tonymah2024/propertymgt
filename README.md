Property Management Analytics Dashboard Demo

This is an interactive, single-page web application demonstrating a modern analytics dashboard for the property management industry. The project is built for a fictional Canadian company, "MapleLeaf Properties", and is presented as a demo by VisiVault Analytics Ltd.

The dashboard is built entirely with front-end technologies and leverages Google's Gemini API to generate real-time, AI-powered insights from the displayed portfolio data.

Live Demo: https://tonymah2024.github.io/propertymgt/

Key Features

    At-a-Glance KPIs: Key Performance Indicators are prominently displayed for a quick overview of portfolio health, including:

        Portfolio Occupancy Rate: The percentage of rented units across the entire portfolio.

        Average Rent per Unit (ARPU): The average rental income per occupied unit.

        Open Maintenance Requests: A real-time count of outstanding maintenance tickets.

        Rent Arrears: The total amount of overdue rent payments from tenants.

    Interactive Data Visualization:

        Portfolio Occupancy Over Time: A line chart tracking occupancy trends across different periods.

        Revenue vs. Expenses: A bar chart comparing total income against operational costs for financial health analysis.

        Upcoming Lease Expirations: A horizontal bar chart that helps management forecast potential vacancies and proactively manage renewals.

        Maintenance Request Status: A doughnut chart visualizing the breakdown of maintenance tickets by their current status (New, In Progress, Completed, etc.).

    AI-Powered Insights: A "Generate Insights" button uses the Google Gemini API to analyze the current dashboard data and provide an executive-level summary and actionable advice from the perspective of a senior property analyst.

    Custom Data Loading: A "Load Data" feature allows you to upload a local .json file to instantly populate the dashboard with your own custom data sets. The required JSON structure is documented within the index.html file's comments.

Technologies Used

    HTML5 for the core structure.

    Tailwind CSS for modern, responsive styling.

    Chart.js for creating interactive and beautiful charts.

    Google Gemini API for generative AI features.

How to Run Locally

    Download the index.html file.

    Open it in any modern web browser.

    When prompted, enter your Google AI API key to enable the "Generate Insights" feature.
