---
layout: default
title: Skills
---

<style>
/* Hides the default site header banner on subpages */
.page-header {
  display: none !important;
}

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

.skill-category {
  margin-bottom: 35px;
  border-bottom: 1px solid #30363d;
  padding-bottom: 25px;
}

.category-number {
  color: #8b949e;
  font-size: 13px;
  font-weight: bold;
  letter-spacing: 1.5px;
  margin-bottom: 6px;
}

.category-title {
  color: #00ccff;
  font-size: 20px;
  margin: 0 0 16px 0;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.skill-tags span {
  background-color: rgba(57, 255, 20, 0.08);
  color: #39ff14;
  border: 1px solid rgba(57, 255, 20, 0.35);
  padding: 6px 12px;
  border-radius: 4px;
  font-size: 13px;
  font-weight: bold;
}
</style>

<div class="nav-bar">
  <a href="{{ site.baseurl }}/">About Me</a> | 
  <a href="{{ site.baseurl }}/skills.html" class="active">Skills</a> | 
  <a href="{{ site.baseurl }}/projects.html">Projects</a> | 
  <a href="{{ site.baseurl }}/experience.html">Experience</a> | 
  <a href="{{ site.baseurl }}/education.html">Education</a>
</div>

<hr>

<h2>Technical Skills</h2>

<div class="skill-category">
  <div class="category-number">01 // NETWORK DEFENSE & AUDITING</div>
  <h3 class="category-title">Network Security & Packet Analysis</h3>
  <div class="skill-tags">
    <span>Wireshark</span>
    <span>OpenSSL</span>
    <span>Traffic Inspection</span>
    <span>Packet Capture</span>
    <span>Port Auditing</span>
    <span>TLS 1.3 / HTTPS</span>
  </div>
</div>

<div class="skill-category">
  <div class="category-number">02 // DIGITAL INVESTIGATION</div>
  <h3 class="category-title">Forensics & Crime Scene Reconstruction</h3>
  <div class="skill-tags">
    <span>Magnet AXIOM</span>
    <span>FTK Imager</span>
    <span>Chain of Custody</span>
    <span>Legal Affidavits</span>
    <span>Artifact Recovery</span>
    <span>Crime Scene Mapping</span>
  </div>
</div>

<div class="skill-category">
  <div class="category-number">03 // GOVERNANCE & ARCHITECTURE</div>
  <h3 class="category-title">Methodologies & Security Frameworks</h3>
  <div class="skill-tags">
    <span>NIST SP 800-171</span>
    <span>Zero Trust Architecture</span>
    <span>Incident Response</span>
    <span>3-2-1-1 Backup Rule</span>
    <span>Vulnerability Management</span>
  </div>
</div>

<div class="skill-category">
  <div class="category-number">04 // SYSTEMS & SCRIPTING</div>
  <h3 class="category-title">Languages, Databases & Analysis</h3>
  <div class="skill-tags">
    <span>SQL Server</span>
    <span>Python</span>
    <span>HTML5 / CSS3</span>
    <span>Excel VBA</span>
    <span>Minitab Statistical Analysis</span>
  </div>
</div>
