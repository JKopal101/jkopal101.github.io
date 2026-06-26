---
layout: default
title: Exploring Cybersecurity & Digital Defense
permalink: /
---

{% raw %}
<style>
  .home-intro {
    font-size: 15px;
    line-height: 1.75;
    color: #ccc;
    max-width: 760px;
    margin-bottom: 2.5rem;
  }

  .section-heading {
    font-size: 20px;
    font-weight: 600;
    color: #f0f0f0;
    margin: 2.5rem 0 0.4rem;
    padding-bottom: 0.5rem;
    border-bottom: 1px solid #2a2a2a;
  }

  .section-sub {
    font-size: 14px;
    color: #777;
    margin-bottom: 1.25rem;
  }

  /* Featured project cards */
  .featured-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1rem;
    margin-bottom: 1rem;
  }

  .featured-card {
    background: #1e1e1e;
    border: 1px solid #333;
    border-radius: 10px;
    padding: 1.25rem 1.5rem;
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
    text-decoration: none;
    transition: border-color 0.2s;
  }

  .featured-card:hover {
    border-color: #555;
    text-decoration: none;
  }

  .featured-category {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .cat-soc  { color: #e07b54; }
  .cat-grc  { color: #7ba8d4; }
  .cat-vuln { color: #c4a85a; }

  .featured-title {
    font-size: 14px;
    font-weight: 600;
    color: #f0f0f0;
    line-height: 1.4;
  }

  .featured-desc {
    font-size: 13px;
    color: #888;
    line-height: 1.6;
    flex: 1;
  }

  .featured-link {
    font-size: 12px;
    color: #6b9fd4;
    margin-top: 0.25rem;
  }

  .all-projects-link {
    display: inline-block;
    font-size: 13px;
    color: #6b9fd4;
    text-decoration: none;
    margin-top: 0.5rem;
  }

  .all-projects-link:hover {
    text-decoration: underline;
  }

  /* Cert list */
  .cert-list {
    list-style: none;
    padding: 0;
    margin: 0 0 0.5rem;
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
  }

  .cert-list li {
    font-size: 14px;
    color: #ccc;
    display: flex;
    align-items: baseline;
    gap: 0.5rem;
  }

  .cert-list li::before {
    content: "✓";
    color: #4caf7d;
    font-size: 12px;
    flex-shrink: 0;
  }

  .cert-list li.planned::before {
    content: "→";
    color: #6b9fd4;
  }

  .cert-list li.inprogress::before {
    content: "◎";
    color: #c4a85a;
  }

  .cert-list a {
    color: #ccc;
    text-decoration: none;
  }

  .cert-list a:hover {
    color: #fff;
    text-decoration: underline;
  }

  .cert-badge {
    font-size: 10px;
    padding: 1px 7px;
    border-radius: 999px;
    vertical-align: middle;
    margin-left: 4px;
  }

  .badge-done       { background: #1a3d2b; color: #4caf7d; border: 1px solid #2a6644; }
  .badge-inprogress { background: #3d2e0a; color: #c4a85a; border: 1px solid #6b4f1a; }
  .badge-planned    { background: #0d2340; color: #6b9fd4; border: 1px solid #1a4570; }

  /* Tools section */
  .tools-section {
    margin-top: 0.5rem;
  }

  .tool-group {
    margin-bottom: 1.25rem;
  }

  .tool-group-label {
    font-size: 13px;
    color: #888;
    margin-bottom: 0.5rem;
    font-weight: 500;
  }

  .tool-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .tool-badge {
    font-size: 12px;
    font-weight: 500;
    padding: 5px 14px;
    border-radius: 6px;
    border: 1px solid #3a3a3a;
    color: #ddd;
    background: #2a2a2a;
    text-decoration: none;
    transition: border-color 0.2s, background 0.2s;
    cursor: default;
  }

  .tool-badge.linked {
    cursor: pointer;
  }

  .tool-badge.linked:hover {
    background: #333;
    border-color: #555;
    text-decoration: none;
  }

  .tool-badge.blue   { border-color: #1a4570; color: #6b9fd4; background: #0d2340; }
  .tool-badge.orange { border-color: #6b3520; color: #e07b54; background: #2d1508; }
  .tool-badge.gold   { border-color: #6b4f1a; color: #c4a85a; background: #2d2008; }
  .tool-badge.green  { border-color: #2a6644; color: #4caf7d; background: #0d2318; }

  /* CTA row */
  .cta-row {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
    margin-top: 2.5rem;
    padding-top: 2rem;
    border-top: 1px solid #2a2a2a;
  }

  .cta-btn {
    font-size: 13px;
    font-weight: 500;
    padding: 9px 20px;
    border-radius: 8px;
    text-decoration: none;
    transition: opacity 0.2s;
  }

  .cta-btn:hover { opacity: 0.85; text-decoration: none; }

  .cta-primary {
    background: #1a4570;
    color: #a8c8f0;
    border: 1px solid #1f5490;
  }

  .cta-secondary {
    background: #1e1e1e;
    color: #ccc;
    border: 1px solid #333;
  }
</style>

<h1 style="font-size:2rem; font-weight:700; color:#f0f0f0; margin-bottom:1.5rem; line-height:1.2;">Exploring Cybersecurity &amp; Digital Defense</h1>

<p class="home-intro">
  I'm James — a civil engineer turned cybersecurity practitioner, focused on SOC operations and GRC. I build hands-on labs, simulate attacks using Kali Linux, and document everything. This portfolio is where I show the work.
</p>


<h2 class="section-heading">Featured Projects</h2>
<p class="section-sub">A selection of hands-on work — <a href="/projects/" style="color:#6b9fd4;">view all projects →</a></p>

<div class="featured-grid">

  <div class="featured-card">
    <span class="featured-category cat-soc">SOC · SIEM · Cloud</span>
    <span class="featured-title">Microsoft Azure SIEM with Log Ingestion</span>
    <span class="featured-desc">Deployed Sentinel in Azure, configured log ingestion pipelines, and wrote custom KQL detection rules to catch anomalous sign-ins and lateral movement.</span>
    <a class="featured-link" href="https://github.com/JKopal101/ms-azure-with-siem" target="_blank">View on GitHub →</a>
  </div>

  <div class="featured-card">
    <span class="featured-category cat-soc">Threat Hunting · Endpoint</span>
    <span class="featured-title">Threat Hunting Scenario: Tor Browser Detection</span>
    <span class="featured-desc">Simulated Tor-based exfiltration in Azure, then hunted it down using Microsoft Defender and KQL — traced the process tree and documented the full investigation.</span>
    <a class="featured-link" href="https://github.com/JKopal101/threat-hunting-scenario-tor" target="_blank">View on GitHub →</a>
  </div>

  <div class="featured-card">
    <span class="featured-category cat-grc">GRC · NIST · ISO 27001</span>
    <span class="featured-title">GRC Capstone: Security Audit and Risk Assessment</span>
    <span class="featured-desc">Full NIST-based security audit — risk register, controls gap analysis against ISO 27001, and a remediation roadmap presented as a professional deliverable.</span>
    <a class="featured-link" href="https://github.com/JKopal101/Conducting-a-Security-Audit" target="_blank">View on GitHub →</a>
  </div>

</div>

<a class="all-projects-link" href="/projects/">→ View all projects</a>


<h2 class="section-heading">Certifications & Learning Path</h2>

<ul class="cert-list">
  <li><a href="https://tcm-sec.com/" target="_blank">TCM Security: SOC 101</a> <span class="cert-badge badge-done">Complete</span></li>
  <li><a href="https://www.coursera.org/" target="_blank">Google Cybersecurity Certificate</a> <span class="cert-badge badge-done">Complete</span></li>
  <li><a href="https://brainstation.io/" target="_blank">BrainStation Cybersecurity Capstone</a> <span class="cert-badge badge-done">Complete</span></li>
  <li class="inprogress">ISC2 CC <span class="cert-badge badge-inprogress">In progress</span></li>
  <li class="inprogress">CompTIA Security+ <span class="cert-badge badge-inprogress">In progress</span></li>
  <li class="inprogress">ISO 27001 Lead Implementer <span class="cert-badge badge-inprogress">In progress</span></li>
  <li class="planned">CompTIA CySA+ <span class="cert-badge badge-planned">Planned</span></li>
  <li class="planned">CISSP <span class="cert-badge badge-planned">Planned</span></li>
</ul>


<h2 class="section-heading">Key Tools</h2>

<div class="tools-section">

  <div class="tool-group">
    <p class="tool-group-label">Networking</p>
    <div class="tool-badges">
      <span class="tool-badge">tcpdump</span>
      <span class="tool-badge">Wireshark</span>
      <span class="tool-badge">Nmap</span>
    </div>
  </div>

  <div class="tool-group">
    <p class="tool-group-label">Endpoint Protection</p>
    <div class="tool-badges">
      <span class="tool-badge blue">Microsoft Defender</span>
      <span class="tool-badge">Velociraptor</span>
    </div>
  </div>

  <div class="tool-group">
    <p class="tool-group-label">SIEM & Detection</p>
    <div class="tool-badges">
      <span class="tool-badge orange">Splunk</span>
      <span class="tool-badge blue">Microsoft Sentinel</span>
      <span class="tool-badge">Elastic</span>
    </div>
  </div>

  <div class="tool-group">
    <p class="tool-group-label">IDS / Network Monitoring</p>
    <div class="tool-badges">
      <span class="tool-badge green">Suricata</span>
      <span class="tool-badge">pfSense</span>
      <span class="tool-badge">Zeek</span>
    </div>
  </div>

  <div class="tool-group">
    <p class="tool-group-label">Offensive / Pen Testing</p>
    <div class="tool-badges">
      <span class="tool-badge orange">Kali Linux</span>
      <span class="tool-badge">Nessus</span>
      <span class="tool-badge">Tenable</span>
      <span class="tool-badge">Burp Suite</span>
    </div>
  </div>

  <div class="tool-group">
    <p class="tool-group-label">GRC & Frameworks</p>
    <div class="tool-badges">
      <span class="tool-badge gold">NIST CSF 2.0</span>
      <span class="tool-badge gold">ISO 27001</span>
      <span class="tool-badge gold">MITRE ATT&CK</span>
      <span class="tool-badge gold">CIS Controls v8</span>
    </div>
  </div>

</div>


<div class="cta-row">
  <a class="cta-btn cta-primary" href="/projects/">View all projects</a>
  <a class="cta-btn cta-secondary" href="/contact/">Get in touch</a>
</div>
{% endraw %}
