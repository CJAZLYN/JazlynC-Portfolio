---
layout: default
title: Projects
---

<style>
/* CORE THEME & LAYOUT */
html, body, .wrapper, section, container, div.wrapper, main, #main_content, .container-lg, .outer {
  background: #0d1117 !important;
  background-color: #0d1117 !important;
  color: #39ff14 !important;
  font-family: 'Courier New', Courier, monospace !important;
}

header, .sidebar, aside {
  background: #161b22 !important;
}

header h1 a, h1#site-title {
  color: #39ff14 !important;
  text-shadow: 0 0 10px rgba(57, 255, 20, 0.7) !important;
  font-weight: bold !important;
}

header h1, h1, h2, h3, h4, h5, h6 {
  color: #00ccff !important;
  font-family: 'Courier New', Courier, monospace !important;
}

/* TOP NAVIGATION BAR */
p[align="center"] {
  background-color: #161b22 !important;
  padding: 12px 10px !important;
  text-align: center !important;
  border: 1px solid #00ccff !important;
  border-radius: 6px !important;
  display: block !important;
}

p[align="center"] a {
  color: #ffffff !important;
  text-decoration: none !important;
  font-weight: bold !important;
  margin: 0 10px !important;
  font-size: 14px !important;
  display: inline-block !important;
}

p[align="center"] a:hover, p[align="center"] a.active {
  color: #39ff14 !important;
  text-shadow: 0 0 8px #39ff14 !important;
}

/* NUMBERED WORK SECTION STYLING */
.work-item {
  margin-bottom: 40px;
  border-bottom: 1px solid #30363d;
  padding-bottom: 30px;
}

.work-meta {
  color: #8b949e;
  font-size: 13px;
  font-weight: bold;
  letter-spacing: 1.5px;
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
  font-size: 22px !important;
  color: #00ccff !important;
}

.work-role {
  color: #8b949e;
  font-size: 13px;
  text-transform: uppercase;
}

.work-desc {
  color: #e6edf3 !important;
  font-size: 14px;
  line-height: 1.6;
  margin: 12px 0 18px 0;
}

.work-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 15px;
}

.work-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.work-tags span {
  background-color: rgba(57, 255, 20, 0.08);
  color: #39ff14 !important;
  border: 1px solid rgba(57, 255, 20, 0.35);
  padding: 4px 10px;
  border-radius: 4px;
  font-size: 12px;
  font-weight: bold;
}

.live-btn {
  background-color: transparent !important;
  color: #00ccff !important;
  border: 1px solid #00ccff !important;
  padding: 8px 16px !important;
  border-radius: 4px !important;
  font-size: 13px !important;
  font-weight: bold !important;
  text-decoration: none !important;
  transition: all 0.2s ease !important;
  white-space: nowrap !important;
}

.live-btn:hover {
  background-color: rgba(0, 204, 255, 0.15) !important;
  color: #ffffff !important;
  box-shadow: 0 0 10px #00ccff !important;
}
</style>

<p align="center">
  <a href="{{ site.baseurl }}/">About Me</a> | 
  <a href="{{ site.baseurl }}/skills.html">Skills</a> | 
  <a href="{{ site.baseurl }}/projects.html" class="active">Projects</a> | 
  <a href="{{ site.baseurl }}/experience.html">Experience</a> | 
  <a href="{{ site.baseurl }}/education.html">Education</a>
</p>

<hr>

<h2>Selected Projects</h2>

<!-- PROJECT 01: DEFENSIVE CYBEROPS -->
<div class="work-item">
  <div class="work-meta">01 // GOVERNANCE, RISK & ZERO TRUST</div>
  <div class="work-title-row">
    <h3>Defensive CyberOps: Organizational Security Policy</h3>
    <span class="work-role">Security Risk Specialist</span>
  </div>
  <p class="work-desc">Developed a robust enterprise security framework for Complex Systems Innovations (CSI) to establish a "Security First" posture following a severe security incident. Mandated administrative and technical controls centered on Zero Trust and Least Privilege, including multi-factor authentication, a 10-minute incident notification threshold, weekly automated vulnerability scans, bi-annual Black Box penetration testing, and a 3-2-1-1 backup model with immutable snapshots guaranteeing a 4-hour Recovery Time Objective (RTO).</p>
  <div class="work-footer">
    <div class="work-tags">
      <span>Zero Trust</span><span>Incident Response</span><span>MFA</span><span>Vulnerability Mgmt</span><span>3-2-1-1 Backup</span><span>NIST Guidelines</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>

<!-- PROJECT 02: SECURE API LAB -->
<div class="work-item">
  <div class="work-meta">02 // CRYPTOGRAPHY & TRANSPORT LAYER SECURITY</div>
  <div class="work-title-row">
    <h3>The Secure Web API Lab</h3>
    <span class="work-role">Security Auditor & Engineer</span>
  </div>
  <p class="work-desc">Audited an internal Node.js web application using Wireshark and uncovered sensitive user credentials traversing Port 3000 in plaintext. Hardened the transport architecture by issuing 2048-bit RSA keys and self-signed X.509 certificates with OpenSSL, transitioning all communication to HTTPS over TLS 1.3 on Port 3443. Enforced HTTP Strict Transport Security (HSTS) with a 1-year max-age to prevent SSL stripping, achieving 100% encryption validation during follow-up packet inspection.</p>
  <div class="work-footer">
    <div class="work-tags">
      <span>OpenSSL</span><span>Wireshark</span><span>TLS 1.3/HTTPS</span><span>2048-bit RSA</span><span>HSTS</span><span>Port 3443</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>

<!-- PROJECT 03: THE TECH BRIDGE -->
<div class="work-item">
  <div class="work-meta">03 // SECURE WEB DEVELOPMENT & ACCESSIBILITY</div>
  <div class="work-title-row">
    <h3>The Tech Bridge</h3>
    <span class="work-role">Front-End Developer</span>
  </div>
  <p class="work-desc">Designed and deployed a responsive 10-page educational platform created to demystify emerging technologies like SaaS and AI for non-technical audiences. Built using HTML5, CSS Grid Bento-box layouts, Glassmorphism design principles, and client-side JavaScript, featuring an interactive reporting form tailored for reporting job market scams and connecting local professionals in Fort Wayne.</p>
  <div class="work-footer">
    <div class="work-tags">
      <span>HTML5</span><span>CSS Grid</span><span>JavaScript</span><span>Bento UI</span><span>Responsive Design</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>

<!-- PROJECT 04: AUTOMATED GROOMING SERVICE -->
<div class="work-item">
  <div class="work-meta">04 // DATABASE ARCHITECTURE & AUTOMATION</div>
  <div class="work-title-row">
    <h3>Automated Grooming Service Management System</h3>
    <span class="work-role">Database Developer</span>
  </div>
  <p class="work-desc">Architected a normalized relational database in SQL Server to streamline operational logistics across clients, service vans, and staff. Automated business logic through T-SQL triggers enforcing daily vehicle appointment limits, built a custom Excel VBA UserForm powered by Views and Stored Procedures for front-end management, and integrated fleet tracking via VIN and odometer tracking alongside a full Data Dictionary.</p>
  <div class="work-footer">
    <div class="work-tags">
      <span>SQL Server</span><span>T-SQL Triggers</span><span>Excel VBA</span><span>ERD Schema</span><span>Data Integrity</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>

<!-- PROJECT 05: WIRESHARK NETWORK ANALYSIS -->
<div class="work-item">
  <div class="work-meta">05 // PACKET INSPECTION & TRAFFIC ANOMALY DETECTION</div>
  <div class="work-title-row">
    <h3>Network Traffic Analysis with Wireshark & Kali</h3>
    <span class="work-role">Network Analyst</span>
  </div>
  <p class="work-desc">Conducted comprehensive packet inspections within a virtualized testbed utilizing Wireshark and Kali Linux to capture baseline and anomalous network traffic. Executed delay testing and applied display filters across ICMP, SSH, TCP, UDP, and FTP streams to identify latency bottlenecks, trace handshakes, and detect suspicious traffic volume spikes associated with denial-of-service behaviors.</p>
  <div class="work-footer">
    <div class="work-tags">
      <span>Wireshark</span><span>Kali Linux</span><span>TCP/IP Protocols</span><span>Traffic Filtering</span><span>PCAP Analysis</span>
    </div>
    <a href="https://github.com/CJAZLYN" target="_blank" rel="noopener noreferrer" class="live-btn">View Project ↗</a>
  </div>
</div>
