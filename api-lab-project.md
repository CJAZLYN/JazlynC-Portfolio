---
layout: default
title: The Secure Web API Lab
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
  <h2>The Secure Web API Lab</h2>
  <p><strong>Role:</strong> Security Auditor & Engineer</p>
  <hr style="border-color: #30363d; margin: 20px 0;">
  
  <h3>Overview</h3>
  <p>Audited an internal Web API using Wireshark during the initial security review and uncovered a critical vulnerability: user login credentials were being transmitted in cleartext, leaving users entirely exposed to Man-in-the-Middle attacks.</p>
  
  <h3>Technical Solutions Implemented</h3>
  <ul>
    <li><strong>Cryptographic Assets:</strong> Utilized OpenSSL to generate 2048-bit RSA keys and X.509 certificates to establish cryptographic trust.</li>
    <li><strong>Protocol Migration:</strong> Moved the server from standard HTTP to HTTPS over TLS 1.3 on Port 3443 to secure data in transit.</li>
    <li><strong>Secure Headers & HSTS:</strong> Injected a Strict-Transport-Security header configured with a max-age of 31.5 million seconds (one full year) to prevent protocol downgrade attacks and ensure permanent browser enforcement.</li>
    <li><strong>Validation & Audit:</strong> Performed follow-up packet analysis and professional audit checks to verify 100% successful encryption, ensuring all sensitive traffic is fully protected.</li>
  </ul>
</div>
