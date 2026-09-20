---
layout: default
title: Automated Grooming Service Management System
---

<style>
.page-header, header, #header { display: none !important; }
html, body, .wrapper, section, container, div.wrapper, main, #main_content, .container-lg, .outer {
  background: #0d1117 !important; background-color: #0d1117 !important; color: #39ff14 !important; font-family: 'Courier New', Courier, monospace !important;
}
.nav-bar {
  background-color: #161b22 !important; padding: 12px 15px !important; text-align: center !important; border: 1px solid #00ccff !important; border-radius: 6px !important; max-width: 650px !important; margin: 0 auto 25px auto !important;
}
.nav-bar a { color: #ffffff !important; text-decoration: none !important; font-weight: bold !important; margin: 0 8px !important; font-size: 13px !important; }
.nav-bar a:hover { color: #39ff14 !important; text-shadow: 0 0 8px #39ff14 !important; }
.detail-box {
  background-color: #161b22; border: 1px solid #00ccff; border-radius: 8px; padding: 30px; margin-bottom: 25px;
}
h2, h3 { color: #00ccff !important; }
p, li { color: #e6edf3 !important; line-height: 1.6; }
.back-btn {
  display: inline-block; background-color: transparent !important; color: #00ccff !important; border: 1px solid #00ccff !important; padding: 8px 16px !important; border-radius: 4px !important; font-weight: bold !important; text-decoration: none !important; margin-bottom: 20px;
}
.back-btn:hover { background-color: rgba(0, 204, 255, 0.15) !important; color: #ffffff !important; }
</style>

<div class="nav-bar">
  <a href="{{ site.baseurl }}/">About Me</a> | 
  <a href="{{ site.baseurl }}/skills.html">Skills</a> | 
  <a href="{{ site.baseurl }}/projects.html">Projects</a> | 
  <a href="{{ site.baseurl }}/experience.html">Experience</a> | 
  <a href="{{ site.baseurl }}/education.html">Education</a>
</div>

<a href="{{ site.baseurl }}/projects.html" class="back-btn">← Back to Projects</a>

<div class="detail-box">
  <h2>Automated Grooming Service Management System</h2>
  <p><strong>Role:</strong> Database Developer</p>
  <hr style="border-color: #30363d; margin: 20px 0;">
  
  <h3>Overview</h3>
  <p>Developed a comprehensive database management system designed to automate and optimize the operations of a mobile grooming service, featuring a robust SQL Server backend paired with a user-friendly Excel VBA frontend.</p>
  
  <h3>Key Contributions & Architecture</h3>
  <ul>
    <li><strong>Database Architecture:</strong> Designed and implemented a normalized relational schema (ERD) to manage complex data relationships between clients (Pet Parents), assets (Vans), and employees.</li>
    <li><strong>Business Logic Automation:</strong> Engineered T-SQL Triggers to enforce critical business rules, such as a four-appointment daily limit per vehicle to ensure operational efficiency and prevent employee burnout.</li>
    <li><strong>Front-End Integration:</strong> Developed a custom Excel VBA UserForm interacting with the SQL database via Stored Procedures and Views, enabling non-technical users to efficiently manage and update pet records.</li>
    <li><strong>Fleet & Resource Management:</strong> Integrated a tracking system for vehicle logistics, including VIN data and daily odometer synchronization to monitor fleet health.</li>
    <li><strong>Data Integrity:</strong> Authored a comprehensive Data Dictionary and implemented strict constraints (non-null indexes, Foreign Keys) to guarantee data consistency across the ecosystem.</li>
  </ul>
</div>
