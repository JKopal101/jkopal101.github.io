---
layout: default
title: About Me
permalink: /about_me/
---

{% raw %}
<style>
  .about-photo {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid #333;
    margin-bottom: 1.5rem;
    display: block;
  }

  .about-intro {
    font-size: 15px;
    line-height: 1.8;
    color: #ccc;
    max-width: 720px;
    margin-bottom: 2.5rem;
  }

  .about-section-heading {
    font-size: 20px;
    font-weight: 600;
    color: #f0f0f0;
    margin: 2.5rem 0 1rem;
    padding-bottom: 0.5rem;
    border-bottom: 1px solid #2a2a2a;
  }

  .about-body {
    font-size: 15px;
    line-height: 1.8;
    color: #ccc;
    max-width: 720px;
    margin-bottom: 1.25rem;
  }

  .skill-list {
    list-style: none;
    padding: 0;
    margin: 1rem 0 1.5rem;
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
    max-width: 720px;
  }

  .skill-list li {
    font-size: 14px;
    color: #ccc;
    line-height: 1.6;
    display: flex;
    gap: 0.75rem;
    align-items: flex-start;
  }

  .skill-list li .bullet {
    color: #6b9fd4;
    font-size: 16px;
    flex-shrink: 0;
    margin-top: 1px;
  }

  .skill-list li strong {
    color: #f0f0f0;
  }

  .soft-skills {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin: 1rem 0 1.5rem;
  }

  .soft-skill-tag {
    font-size: 12px;
    padding: 4px 12px;
    border-radius: 999px;
    border: 1px solid #333;
    color: #aaa;
    background: #1e1e1e;
  }

  .goals-body {
    font-size: 15px;
    line-height: 1.8;
    color: #ccc;
    max-width: 720px;
    margin-bottom: 1rem;
  }

  .cert-status {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    margin: 1rem 0 1.5rem;
    max-width: 500px;
  }

  .cert-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 14px;
    color: #ccc;
    padding: 8px 12px;
    background: #1e1e1e;
    border: 1px solid #2a2a2a;
    border-radius: 8px;
  }

  .cert-badge {
    font-size: 10px;
    padding: 2px 8px;
    border-radius: 999px;
    font-weight: 500;
  }

  .badge-done       { background: #1a3d2b; color: #4caf7d; border: 1px solid #2a6644; }
  .badge-inprogress { background: #3d2e0a; color: #c4a85a; border: 1px solid #6b4f1a; }
  .badge-planned    { background: #0d2340; color: #6b9fd4; border: 1px solid #1a4570; }

  .blog-link {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 14px;
    color: #6b9fd4;
    text-decoration: none;
    margin-top: 0.5rem;
  }

  .blog-link:hover {
    text-decoration: underline;
  }

  .hobbies {
    font-size: 15px;
    line-height: 1.8;
    color: #888;
    max-width: 720px;
    margin-top: 1rem;
  }

  .contact-cta {
    display: inline-block;
    margin-top: 2rem;
    font-size: 13px;
    font-weight: 500;
    padding: 9px 20px;
    border-radius: 8px;
    background: #1a4570;
    color: #a8c8f0;
    border: 1px solid #1f5490;
    text-decoration: none;
  }

  .contact-cta:hover {
    opacity: 0.85;
    text-decoration: none;
  }
</style>

<h3><strong>About Me</strong></h3>

<img class="about-photo" src="https://jkopal101.github.io/assets/IMG_20220307_112617.jpg" alt="James Kopal" />

<p class="about-intro">
  From a young age I was drawn to how complex systems work — and how they fail. That curiosity led me through civil engineering and eventually into cybersecurity, where the problems are harder, the stakes are higher, and the field never stands still. The idea of protecting systems, hunting threats, and thinking like an attacker while defending like an analyst is where my engineering mindset found its best use.
</p>


<h3 class="about-section-heading">My Cybersecurity Journey</h3>

<p class="about-body">
  My path into cybersecurity started with a civil engineering background — a discipline built on risk assessment, documentation rigour, and working to tight standards. Those skills translate directly: gap analysis is gap analysis whether you're assessing a bridge or an ISO 27001 control set.
</p>

<p class="about-body">
  I made the transition through self-study, hands-on labs, and formal training. Along the way I've built experience in:
</p>

<ul class="skill-list">
  <li>
    <span class="bullet">◆</span>
    <span><strong>SOC & Threat Detection</strong> — Deploying and tuning SIEMs (Splunk, Microsoft Sentinel), writing custom detection rules in SPL and KQL, and investigating alerts end-to-end.</span>
  </li>
  <li>
    <span class="bullet">◆</span>
    <span><strong>Network Security</strong> — Monitoring traffic, configuring Suricata IDS with Emerging Threats rulesets, and analysing packet captures.</span>
  </li>
  <li>
    <span class="bullet">◆</span>
    <span><strong>GRC</strong> — Conducting security audits and risk assessments against NIST CSF 2.0 and ISO 27001, producing professional deliverables.</span>
  </li>
  <li>
    <span class="bullet">◆</span>
    <span><strong>Offensive Techniques</strong> — Running vulnerability assessments, simulating attacks from Kali Linux, and understanding the attacker perspective to inform better defences.</span>
  </li>
</ul>

<p class="about-body">
  The engineering background also means I bring skills that are harder to teach: structured thinking under pressure, clear technical documentation, and the habit of asking <em>why</em> a control exists before implementing it.
</p>

<div class="soft-skills">
  <span class="soft-skill-tag">Risk Assessment</span>
  <span class="soft-skill-tag">Technical Documentation</span>
  <span class="soft-skill-tag">Standards & Compliance</span>
  <span class="soft-skill-tag">Analytical Thinking</span>
  <span class="soft-skill-tag">Problem Solving</span>
  <span class="soft-skill-tag">Team Collaboration</span>
</div>

<a class="blog-link" href="https://jkopal101.github.io/2025/03/26/my-cyber-journey.html">👉 Read the full story on my blog</a>


<h3 class="about-section-heading">My Goals</h3>

<p class="goals-body">
  I'm actively targeting <strong>SOC Analyst and GRC Analyst roles in the Canadian market</strong>, with a particular interest in Alberta's energy, fintech, and healthcare sectors.
</p>

<p class="goals-body">Current certifications:</p>

<div class="cert-status">
  <div class="cert-row">TCM Security: SOC 101 <span class="cert-badge badge-done">Complete</span></div>
  <div class="cert-row">Google Cybersecurity Certificate <span class="cert-badge badge-done">Complete</span></div>
  <div class="cert-row">BrainStation Cybersecurity Capstone <span class="cert-badge badge-done">Complete</span></div>
  <div class="cert-row">ISC2 CC <span class="cert-badge badge-inprogress">In progress</span></div>
  <div class="cert-row">CompTIA Security+ <span class="cert-badge badge-inprogress">In progress</span></div>
  <div class="cert-row">ISO 27001 Lead Implementer <span class="cert-badge badge-inprogress">In progress</span></div>
  <div class="cert-row">CompTIA CySA+ <span class="cert-badge badge-planned">Planned</span></div>
  <div class="cert-row">CISSP <span class="cert-badge badge-planned">Planned</span></div>
</div>

<p class="goals-body">
  The longer-term ambition is a purple team consulting practice — but right now the focus is getting into a role where I can contribute, learn fast, and prove the work.
</p>

<p class="goals-body">🚀 Cybersecurity is an ever-evolving field, and I'm building for the long game.</p>

<p class="hobbies">
  Beyond cybersecurity, I enjoy hill walking, snowboarding, boxing, and playing the piano.
</p>

<a class="contact-cta" href="/contact/">Get in touch</a>
{% endraw %}
