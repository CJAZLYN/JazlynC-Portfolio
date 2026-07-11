---
layout: default
---


---
html, body, .wrapper, section, container, div.wrapper, main {
  background: #0d1117 !important;
  background-color: #0d1117 !important;
  color: #39ff14 !important; /* Terminal Green text */
  font-family: 'Courier New', Courier, monospace !important;
}

/* SIDEBAR & HEADER BACKGROUNDS */
header, .sidebar, aside {
  background: #161b22 !important;
  background-color: #161b22 !important;
}

/* TEXT COLOR ADJUSTMENTS */
header h1, header h1 a, h1, h2, h3, h4, h5, h6 {
  color: #00ccff !important; /* Cyber Blue headings */
  font-family: 'Courier New', Courier, monospace !important;
}

header p, header span, footer p {
  color: #8b949e !important;
}

li, p {
  color: #39ff14 !important; 
}

/* NAVIGATION HEADER DASHBOARD */
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

p[align="center"] a:hover {
  color: #39ff14 !important;
  text-shadow: 0 0 8px #39ff14 !important;
}

/* PROJECT CONTAINER STYLING */
.project-grid {
  display: flex !important;
  flex-direction: column !important;
  gap: 20px !important;
  margin-top: 20px !important;
  width: 100% !important;
}

.project-card {
  background-color: #161b22 !important;
  border: 1px solid #30363d !important;
  border-radius: 8px !important;
  padding: 24px !important;
  box-sizing: border-box !important;
}

.project-card:hover {
  border-color: #00ccff !important;
}

/* THIS MATCHES ALL PROJECT HEADERS SIDE-BY-SIDE */
.project-header {
  display: flex !important;
  justify-content: space-between !important;
  align-items: baseline !important;
  margin-bottom: 12px !important;
  width: 100% !important;
}

.project-card h3 {
  margin: 0 !important;
  font-size: 18px !important;
  color: #00ccff !important;
  border: none !important;
  padding: 0 !important;
}

.project-role {
  font-size: 12px !important;
  color: #8b949e !important;
  text-transform: uppercase !important;
}

.project-desc {
  font-size: 14px !important;
  color: #e6edf3 !important;
  line-height: 1.5 !important;
  margin: 10px 0 20px 0 !important;
}

.project-tags span {
  background-color: rgba(57, 255, 20, 0.1) !important;
  color: #39ff14 !important;
  border: 1px solid rgba(57, 255, 20, 0.3) !important;
  padding: 4px 8px !important;
  border-radius: 4px !important;
  font-size: 11px !important;
  font-weight: bold !important;
  display: inline-block !important;
  margin-right: 6px !important;
}
</style>



<p align="center">
  <a href="#about">About Me</a> | 
  <a href="#skills">Skills</a> | 
  <a href="#projects">Projects</a> | 
  <a href="#experience">Experience</a> | 
  <a href="#education">Education & Certificates</a> | 
  <a href="mailto:Jazlyn.collyear@gmail.com">Contact & Connect</a>
</p>

<hr>

<!-- ABOUT ME SECTION -->
<div id="about">
  <h2>About Me</h2>
  <p>I’ve always seen cybersecurity as a massive puzzle. I love the challenge of piecing together clues, finding patterns, and solving complex problems to stay ahead of threats. As a recent Cybersecurity graduate from Indiana Tech, I genuinely enjoy diving into the technical details to uncover and fix hidden vulnerabilities.</p>
  <p>My passion for defense really clicked when I worked independently on "The Secure Web API." Using Wireshark to run packet analysis, I watched exactly how easily sensitive data like emails and passwords can be exposed if they aren't properly protected. Seeing that exposure firsthand is what drives my focus on data protection and secure protocols. Now, I’m excited to bring that analytical mindset and hands-on investigative drive to a fast-paced Security Operations Center (SOC) team.</p>
</div>

<hr>

<!-- TECHNICAL SKILLS SECTION -->
<div id="skills">
  <h2>Technical Skills</h2>
  <ul>
    <li>Network Security & Analysis:Wireshark, OpenSSL, network traffic analysis, Packet Capture & Inspection</li>
    <li>Methodologies & Frameworks: NIST SP 800-171, Secure Design Principles, Front-End Web Development</li>
    <li>Languages & Databases: Python, SQL, HTML/CSS</li>
    <li>Data & Statistical Analysis:Python, SQL, HTML, Minitab statistical analysis</li>
  </ul>
</div>

<hr>

<!-- PROJECTS SECTION -->
<div id="projects">
  <h2>Projects</h2>
  
  <div class="project-grid">

    <!-- CARD 1 -->
    <div class="project-card">
      <div class="project-header">
        <h3>The Secure Web API</h3>
        <span class="project-role">Security Auditor & Engineer</span>
      </div>
      <p class="project-desc">Conducted a comprehensive security audit on a custom Web API to identify data exposure vulnerabilities and implement robust transport layer defense. Upon discovering that user credentials were transmitting in plaintext, single-handedly engineered a complete cryptographic infrastructure to secure the environment against Man-in-the-Middle (MitM) attacks.</p>
      <div class="project-tags">
        
        <span>OpenSSL</span><span>Wireshark</span><span>TLS 1.3/HTTPS</span><span>2048-bit RSA</span><span>X.509 Certificates</span>
      </div>
    </div>

    <!-- CARD 2 -->
    <div class="project-card">
      <div class="project-header">
         
         <h3>Wireshark Network Analysis</h3>
        <span class="project-role">Network Analyst</span>
      </div>
      <p class="project-desc">Conducted a comprehensive analysis of live network traffic using Wireshark to monitor data flows, execute delay testing, and evaluate protocol performance. This hands-on project focused on identifying traffic patterns and isolating potential security anomalies within a network environment.</p>
      <div class="project-tags">
        <span>Wireshark</span><span>ICMP</span><span>SSH</span><span>TCP</span><span>FTP</span><span>Network Protocols</span>
      </div>
    </div>

    <!-- CARD 3 -->
    <div class="project-card">
      <div class="project-header">
        <h3>Defensive CyberOps Policy</h3>
        <span class="project-role">Security Risk Specialist</span>
      </div>
      <p class="project-desc">Developed a comprehensive enterprise security policy framework for a simulated organization following a major data breach. The framework engineered strict administrative and technical controls designed to mitigate lateral threat movement, enforce regulatory compliance, and build a proactive, security-first corporate culture.</p>
      <div class="project-tags">
        <span>Zero Trust</span><span>Incident Response</span><span>NIST Framework</span><span>Vulnerability Mgmt</span><span>3-2-1-1 Backup</span>
      </div>
    </div>

    <!-- CARD 4 -->
    <div class="project-card">
      <div class="project-header">
        <h3>Automated Management System</h3>
        <span class="project-role">Database Developer</span>
      </div>
      <p class="project-desc">Developed and deployed a comprehensive relational database management system designed to automate and optimize operations for a mobile business. Built a robust SQL Server backend integrated with a custom Excel VBA user interface, allowing non-technical managers to effortlessly update records, track fleet logistics, and maintain seamless business workflows.</p>
      <div class="project-tags">
        <span>SQL Server</span><span>Excel VBA</span><span>Relational Databases</span><span>Workflow Optimization</span>
      </div>
    </div>

    <!-- CARD 5 -->
    <div class="project-card">
      <div class="project-header">
        <h3>The Tech Bridge</h3>
        <span class="project-role">Secure Web Developer</span>
      </div>
      <p class="project-desc">Designed and deployed a comprehensive 10-page educational website engineered to bridge the gap between complex technological concepts and non-technical audiences. Built a highly responsive interface focused on user accessibility, clean performance, and community-focused digital resources.</p>
      <div class="project-tags">
        <span>HTML/CSS</span><span>User Accessibility</span><span>Responsive Design</span><span>Interface Engineering</span>
      </div>
    </div>

  </div>
</div>

<hr>

<!-- EXPERIENCE SECTION -->
<div id="experience">
  <h2>Experience</h2>
  <h3>Secretary | Indiana Tech Cybersecurity Society - Volunteer</h3>
  <ul>
    <li>Managed all internal and external communication channels, acting as the core bridge between student leadership, active members, and professional industry partners via corporate Outlook networks.</li>
    <li>Spearheaded calendar management and scheduling logistics for semester events, workshops, and meeting locations to ensure seamless organizational operations.</li>
    <li>Formally recorded critical executive meeting minutes, maintained comprehensive organizational documentation, and coordinated with the Student Executive Board (SEB) to align operational objectives.</li>
  </ul>

  <h3>Athletic Student Worker | Indiana Tech</h3>
  <ul>
    <li>Assisted with on-campus athletic operations, coordination, and administrative support.</li>
  </ul>
</div>

<hr>

<!-- EDUCATION SECTION -->
<div id="education">
  <h2>Education & Certificates</h2>
  <h3>Bachelor of Science in Cybersecurity</h3>
  <p><strong>Indiana Institute of Technology (Indiana Tech)</strong></p>
  <ul>
    <li><strong>Honors & Activities:</strong> Dean's List, Cybersecurity Society Secretary</li>
  </ul>
</div>

<hr>

<!-- CONTACT SECTION -->
<div id="contact">
  <h2>Contact & Connect</h2>
  <ul>
    <li><strong>Email:</strong> <a href="mailto:Jazlyn.collyear@gmail.com">Jazlyn.collyear@gmail.com</a></li>
    <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/jazlyn-collyear" target="_blank">linkedin.com/in/jazlyn-collyear</a></li>
    <li><strong>GitHub:</strong> <a href="https://github.com/CJAZLYN" target="_blank">github.com/CJAZLYN</a></li>
  </ul>
</div>

