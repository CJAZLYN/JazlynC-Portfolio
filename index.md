---
layout: default
---

<style>
/* Import the Fira Code font from Google Fonts */
@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;700&display=swap');

html { scroll-behavior: smooth !important; }
html, body, .wrapper, section {
  background: #0d1117 !important;
  background-color: #0d1117 !important;
  color: #39ff14 !important;
  font-family: 'Fira Code', monospace !important;
}
header, .sidebar, aside {
  background: #161b22 !important;
  background-color: #161b22 !important;
}
header h1, header h1 a {
  color: #39ff14 !important;
  text-shadow: 0 0 10px rgba(57, 255, 20, 0.7) !important;
  font-weight: bold !important;
}
h1, h2, h3, h4, h5, h6 {
  color: #00ccff !important;
  font-family: 'Fira Code', monospace !important;
}
p[align="center"] {
  background-color: #161b22 !important;
  padding: 12px 10px !important;
  text-align: center !important;
  border: 1px solid #00ccff !important;
  border-radius: 6px !important;
}
p[align="center"] a {
  color: #ffffff !important;
  text-decoration: none !important;
  font-weight: bold !important;
  margin: 0 10px !important;
}
p[align="center"] a:hover, p[align="center"] a.active {
  color: #39ff14 !important;
}
strong {
  color: #ffffff !important;
  font-weight: bold !important;
}

/* --- Profile Section Styles --- */
.about-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 20px;
}

.profile-frame {
  width: 280px;
  height: 280px;
  border-radius: 50%;
  border: 4px solid #39ff14;
  box-shadow: 0 0 20px #39ff14, inset 0 0 15px rgba(57, 255, 20, 0.5);
  overflow: hidden;
  margin-bottom: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.profile-frame img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.content-box {
  background-color: rgba(22, 27, 34, 0.85);
  background-image: 
    linear-gradient(rgba(0, 204, 255, 0.05) 1px, transparent 1px),
    linear-gradient(90deg, rgba(0, 204, 255, 0.05) 1px, transparent 1px);
  background-size: 20px 20px;
  border: 1px solid #00ccff;
  border-radius: 8px;
  padding: 25px;
  text-align: left;
  max-width: 800px;
  width: 100%;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
}

.content-box h2 {
  margin-top: 0;
  border-bottom: 2px solid #00ccff;
  padding-bottom: 8px;
}

.content-box p {
  line-height: 1.6;
}
</style>

<p align="center">
  <a href="{{ site.baseurl }}/" class="active">About Me</a> | 
  <a href="{{ site.baseurl }}/skills.html">Skills</a> | 
  <a href="{{ site.baseurl }}/projects.html">Projects</a> | 
  <a href="{{ site.baseurl }}/experience.html">Experience</a> | 
  <a href="{{ site.baseurl }}/education.html">Education</a>
</p>

<hr>

<div class="about-container">
  <!-- Circular Profile Picture Frame -->
  <div class="profile-frame">
    <img src="profile.jpg" alt="Profile Picture">
  </div>

  <!-- Content Box with Cybersecurity Grid Background -->
  <div class="content-box" id="about">
    <h2>About Me</h2>
    <p>I’ve always seen cybersecurity as a massive puzzle. I love the challenge of piecing together clues, finding patterns, and solving complex problems to stay ahead of threats. As a recent Cybersecurity graduate from Indiana Tech, I genuinely enjoy diving into the technical details to uncover and fix hidden vulnerabilities.</p>
    <p>My passion for defense really clicked when I worked independently on The Secure Web API. Using Wireshark to run packet analysis, I watched exactly how easily sensitive data like emails and passwords can be exposed if they aren't properly protected. Seeing that exposure firsthand is what drives my focus on data protection and secure protocols. Now, I’m excited to bring that analytical mindset, hands-on investigative drive, and strong foundational knowledge to a collaborative cybersecurity team.</p>
  </div>
</div>
