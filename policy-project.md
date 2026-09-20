---
layout: default
title: Defensive CyberOps Policy
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
  <h2>Defensive CyberOps: Organizational Security Policy</h2>
  <p><strong>Role:</strong> Security Risk Specialist</p>
  <hr style="border-color: #30363d; margin: 20px 0;">
  
  <h3>Overview</h3>
  <p>Developed a robust enterprise security framework for Complex Systems Innovations (CSI) to establish a "Security First" culture following a catastrophic data breach. The policy enforces strict administrative and technical controls across key security domains to mitigate risk and defend against evolving cyber threats.</p>
  
  <h3>Key Security Domains</h3>
  <ul>
    <li><strong>Access Control & Zero Trust:</strong> Enforced a Zero Trust Architecture and the Principle of Least Privilege, requiring Multi-Factor Authentication (MFA) via biometric verification for all remote logins and administrative consoles, along with mandatory quarterly access reviews and 1-hour account deactivation windows for terminated personnel.</li>
    <li><strong>Incident Response:</strong> Established immediate reporting protocols requiring employees to notify the Security Operations Center within a 10-minute window of discovering suspicious activity, alongside rapid network segmentation and systematic backup restoration to eradicate threats.</li>
    <li><strong>Vulnerability Management:</strong> Mandated weekly automated scans (utilizing tools like Nmap) and bi-annual independent Black Box penetration testing, requiring Critical and High vulnerabilities (CVSS) to be remediated within 48 hours.</li>
    <li><strong>Data Protection & Recovery:</strong> Implemented a 3-2-1-1 Backup Strategy utilizing local server storage, encrypted cloud buckets, off-site retention, and immutable storage snapshots to guarantee a 4-hour Recovery Time Objective (RTO) against ransomware.</li>
    <li><strong>Compliance & Enforcement:</strong> Assigned ultimate oversight to the CISO while positioning all personnel as active human firewalls, backed by strict disciplinary protocols ranging from mandatory retraining to termination for non-compliance.</li>
  </ul>
</div>
