# Job-Application-Automation-System
This n8n project automates the process of generating customized CVs for hundreds of job listings in just a few minutes.
It combines Apify, Google Sheets, and AI integration to create a completely hands-free workflow that saves hours of manual effort.

How It Works

Apify Integration: The workflow starts by scraping job listings from LinkedIn (or any other job platform) using Apify.

Google Sheets Storage: The job data — including title, company, location, and job description — is automatically saved to a connected Google Sheet.

Loop Items (Automation): n8n loops through each job entry and processes them one by one.

AI-Powered CV Generation: For every job listing, AI generates a personalized CV tailored to the specific job description and company.

Google Drive Upload: The generated CVs are automatically uploaded, and their links are saved back to the same Google Sheet alongside job details.

Final Output: The result is a fully organized sheet with job title, company name, salary, job link, and a unique customized CV link for each role.

Key Features

Generate hundreds of CVs in minutes

Completely automated — no manual work needed after setup

Custom-tailored CVs for each job description

Easy-to-track output through Google Sheets

Saves time for freelancers, job seekers, and HR professionals
