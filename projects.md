---
layout: default
title: Selected Projects
---

<style>
/* Hides the default site header banner on subpages */
.page-header, header, #header {
  display: none !important;
}

html, body, .wrapper, section, container, div.wrapper, main, #main_content, .container-lg, .outer {
  background: #0d1117 !important;
  background-color: #0d1117 !important;
  color: #39ff14 !important;
  font-family: 'Courier New', Courier, monospace !important;
}

/* SLEEK CENTERED NAVIGATION BAR */
.nav-bar {
  background-color: #161b22 !important;
  padding: 12px 15px !important;
  text-align: center !important;
  border: 1px solid #00ccff !important;
  border-radius: 6px !important;
  max-width: 650px !important;
  margin: 0 auto 25px auto !important;
}
.nav-bar a {
  color: #ffffff !important;
  text-decoration: none !important;
  font-weight: bold !important;
  margin: 0 8px !important;
  font-size: 13px !important;
}
.nav-bar a:hover, .nav-bar a.active {
  color: #39ff14 !important;
  text-shadow: 0 0 8px #39ff14 !important;
}

.work-item {
  background-color: #161b22;
  border: 1px solid #30363d;
  border-radius: 8px;
  padding: 20px;
  margin-bottom: 25px;
}
.work-item:hover {
  border-color: #00ccff;
}
.work-meta {
  color: #8b949e;
  font-size: 12px;
  font-weight: bold;
  letter-spacing: 1px;
  margin-bottom: 6px;
}
.work-title-row {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 8px;
}
.work-title-row h3 {
  margin: 0 !important;
  font-size: 20px !important;
  color: #00ccff !important;
}
.work-role {
  color: #8b949e;
  font-size: 12px;
  text-transform: uppercase;
}
.work-desc {
  color: #e6edf3 !important;
  font-size: 14px;
  line-height: 1.5;
  margin: 10px 0 15px 0;
}
ul {
  margin: 10px 0 15px 20px;
  line-height: 1.6;
}
li {
  margin-bottom: 6px;
  font-size: 14px;
  color: #e6edf3 !important;
}
.work-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 15px;
}
.work-tags span {
  background-color: rgba(57, 255, 20, 0.08);
  color: #39ff14 !important;
  border: 1px solid rgba(57, 255, 20, 0.35);
  padding: 3px 8px;
  border-radius: 4px;
  font-size: 11px;
  font-weight: bold;
  display: inline-block;
  margin-right: 5px;
  margin-bottom: 5px;
}
.live-btn {
  background-color: transparent !important;
  color: #00ccff !important;
  border: 1px solid #00ccff !important;
  padding: 6px 12px !important;
  border-radius: 4px !important;
  font-size: 12px !important;
  font-weight: bold !important;
  text-decoration: none !important;
  white-space: nowrap !important;
}
.live-btn:hover {
  background-color: rgba(0, 204, 255, 0.15) !important;
  color: #ffffff !important;
  box-shadow: 0 0 8px #00ccff !important;
}
</style>

<div class="nav-bar">
  <a href="{{ site.baseurl }}/">About Me</a> | 
  <a href="{{ site.baseurl }}/skills.html">Skills</a> | 
  <a href="{{ site.baseurl }}/projects.html" class="active">Projects</a> | 
  <a href="{{ site.baseurl }}/experience.html">Experience</a> | 
  <a href="{{ site.baseurl }}/education.html">Education</a>
</div>

<h2>Selected Projects</h2>

<!-- PROJECT 01 -->
<div class="work-item">
  <div class="work-meta">01 // GOVERNANCE, RISK & ZERO TRUST</div>
  <div class="work-title-row">
    <h3>Defensive CyberOps: Organizational Security Policy</h3>
    <span class="work-role">Security Risk Specialist</span>
  </div>
  <p class="work-desc">Developed a robust enterprise security framework for Complex Systems Innovations (CSI) to establish a "Security First" culture following a catastrophic data breach. The policy enforces strict administrative and technical controls across key security domains to mitigate risk and defend against evolving cyber threats.</p>
  <ul>
    <li><strong>Access Control & Zero Trust:</strong> Enforced a Zero Trust Architecture and the Principle of Least Privilege, requiring Multi-Factor Authentication (MFA) via biometric verification for all remote logins and administrative consoles, along with mandatory quarterly access reviews and 1-hour account deactivation windows for terminated personnel.</li>
    <li><strong>Incident Response:</strong> Established immediate reporting protocols requiring employees to notify the Security Operations Center within a 10-minute window of discovering suspicious activity, alongside rapid network segmentation and systematic backup restoration to eradicate threats.</li>
    <li><strong>Vulnerability Management:</strong> Mandated weekly automated scans (utilizing tools like Nmap) and bi-annual independent Black Box penetration testing, requiring Critical and High vulnerabilities (CVSS) to be remediated within 48 hours.</li>
    <li><strong>Data Protection & Recovery:</strong> Implemented a 3-2-1-1 Backup Strategy utilizing local server storage, encrypted cloud buckets, off-site retention, and immutable storage snapshots to guarantee a 4-hour Recovery Time Objective (RTO) against ransomware.</li>
    <li><strong>Compliance & Enforcement:</strong> Assigned ultimate oversight to the CISO while positioning all personnel as active human firewalls, backed by strict disciplinary protocols ranging from mandatory retraining to termination for non-compliance.</li>
  </ul>
  <div class="work-footer" style="margin-top: 15px;">
    <div class="work-tags">
      <span>Zero Trust</span><span>Incident Response</span><span>MFA</span><span>Vulnerability Mgmt</span><span>3-2-1-1 Backup</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>

<!-- PROJECT 02 -->
<div class="work-item">
  <div class="work-meta">02 // CRYPTOGRAPHY & TRANSPORT LAYER SECURITY</div>
  <div class="work-title-row">
    <h3>The Secure Web API Lab</h3>
    <span class="work-role">Security Auditor & Engineer</span>
  </div>
  <p class="work-desc">Audited an internal Web API using Wireshark during the initial security review and uncovered a critical vulnerability: user login credentials were being transmitted in cleartext, leaving users entirely exposed to Man-in-the-Middle attacks.</p>
  <ul>
    <li><strong>Cryptographic Assets:</strong> Utilized OpenSSL to generate 2048-bit RSA keys and X.509 certificates to establish cryptographic trust.</li>
    <li><strong>Protocol Migration:</strong> Moved the server from standard HTTP to HTTPS over TLS 1.3 on Port 3443 to secure data in transit.</li>
    <li><strong>Secure Headers & HSTS:</strong> Injected a Strict-Transport-Security header configured with a max-age of 31.5 million seconds (one full year) to prevent protocol downgrade attacks and ensure permanent browser enforcement.</li>
    <li><strong>Validation & Audit:</strong> Performed follow-up packet analysis and professional audit checks to verify 100% successful encryption, ensuring all sensitive traffic is fully protected.</li>
  </ul>
  <div class="work-footer" style="margin-top: 15px;">
    <div class="work-tags">
      <span>OpenSSL</span><span>Wireshark</span><span>TLS 1.3/HTTPS</span><span>2048-bit RSA</span><span>HSTS</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>

<!-- PROJECT 03 -->
<div class="work-item">
  <div class="work-meta">03 // SECURE WEB DEVELOPMENT & ACCESSIBILITY</div>
  <div class="work-title-row">
    <h3>The Tech Bridge</h3>
    <span class="work-role">Front-End Developer</span>
  </div>
  <p class="work-desc">Designed and deployed a 10-page educational website built to bridge the gap between complex technology concepts and non-technical audiences.</p>
  <ul>
    <li><strong>Secure-Entry Interaction:</strong> Implemented a secure-entry form via client-side JavaScript to help users report job market scams and fraud safely.</li>
    <li><strong>Modern Interface Architecture:</strong> Utilized HTML5, CSS Grid Bento-box layouts, and JavaScript to engineer a responsive, high-performance interface.</li>
    <li><strong>Community Focus:</strong> Created intuitive user pathways to connect local professionals and raise awareness around digital security and emerging technology trends.</li>
  </ul>
  <div class="work-footer" style="margin-top: 15px;">
    <div class="work-tags">
      <span>HTML5</span><span>CSS Grid</span><span>JavaScript</span><span>Bento UI</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>

<!-- PROJECT 04 -->
<div class="work-item">
  <div class="work-meta">04 // DATABASE ARCHITECTURE & AUTOMATION</div>
  <div class="work-title-row">
    <h3>Automated Grooming Service Management System</h3>
    <span class="work-role">Database Developer</span>
  </div>
  <p class="work-desc">Developed a comprehensive database management system designed to automate and optimize the operations of a mobile grooming service, featuring a robust SQL Server backend paired with a user-friendly Excel VBA frontend.</p>
  <ul>
    <li><strong>Database Architecture:</strong> Designed and implemented a normalized relational schema (ERD) to manage complex data relationships between clients (Pet Parents), assets (Vans), and employees.</li>
    <li><strong>Business Logic Automation:</strong> Engineered T-SQL Triggers to enforce critical business rules, such as a four-appointment daily limit per vehicle to ensure operational efficiency and prevent employee burnout.</li>
    <li><strong>Front-End Integration:</strong> Developed a custom Excel VBA UserForm interacting with the SQL database via Stored Procedures and Views, enabling non-technical users to efficiently manage and update pet records.</li>
    <li><strong>Fleet & Resource Management:</strong> Integrated a tracking system for vehicle logistics, including VIN data and daily odometer synchronization to monitor fleet health.</li>
    <li><strong>Data Integrity:</strong> Authored a comprehensive Data Dictionary and implemented strict constraints (non-null indexes, Foreign Keys) to guarantee data consistency across the ecosystem.</li>
  </ul>
  <div class="work-footer" style="margin-top: 15px;">
    <div class="work-tags">
      <span>SQL Server</span><span>T-SQL Triggers</span><span>Excel VBA</span><span>ERD Schema</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>

<!-- PROJECT 05 -->
<div class="work-item">
  <div class="work-meta">05 // PACKET INSPECTION & TRAFFIC ANOMALY DETECTION</div>
  <div class="work-title-row">
    <h3>Network Traffic Analysis with Wireshark</h3>
    <span class="work-role">Network Analyst</span>
  </div>
  <p class="work-desc">Conducted comprehensive packet inspections as part of cybersecurity coursework in collaboration with a classmate, analyzing network traffic to identify patterns and potential threats.</p>
  <ul>
    <li>Executed delay testing within a structured testing environment to measure response times and evaluate network performance.</li>
    <li>Applied protocol display filters across ICMP, SSH, TCP, and FTP streams to isolate specific traffic types and trace handshakes.</li>
    <li>Enhanced core competencies in packet-level analysis, threat detection, and real-time traffic monitoring.</li>
  </ul>
  <div class="work-footer" style="margin-top: 15px;">
    <div class="work-tags">
      <span>Wireshark</span><span>TCP/IP Protocols</span><span>Traffic Filtering</span><span>Delay Testing</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>
