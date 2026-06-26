---
layout: default
title: Projects
permalink: /projects/
---

<style>
  .projects-intro {
    font-size: 16px;
    line-height: 1.7;
    margin-bottom: 2.5rem;
    max-width: 720px;
  }

  .category-label {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #888;
    margin: 2.5rem 0 1rem;
    padding-bottom: 0.5rem;
    border-bottom: 1px solid #333;
  }

  .card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.25rem;
    margin-bottom: 1rem;
  }

  .project-card {
    background: #1e1e1e;
    border: 1px solid #333;
    border-radius: 10px;
    padding: 1.25rem 1.5rem;
    display: flex;
    flex-direction: column;
    gap: 0.6rem;
    transition: border-color 0.2s;
  }

  .project-card:hover {
    border-color: #555;
  }

  .card-category {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.08em;
    text-transform: uppercase;
  }

  .cat-soc  { color: #e07b54; }
  .cat-grc  { color: #7ba8d4; }
  .cat-vuln { color: #c4a85a; }

  .card-title {
    font-size: 15px;
    font-weight: 600;
    color: #f0f0f0;
    line-height: 1.4;
    text-decoration: none;
  }

  .card-title:hover {
    color: #ffffff;
    text-decoration: underline;
  }

  .card-outcome {
    font-size: 13px;
    color: #aaa;
    line-height: 1.6;
    flex: 1;
  }

  .card-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    margin-top: 0.25rem;
  }

  .tag {
    font-size: 11px;
    padding: 3px 9px;
    border-radius: 999px;
    border: 1px solid #3a3a3a;
    color: #bbb;
    background: #2a2a2a;
  }

  .card-link {
    font-size: 12px;
    color: #6b9fd4;
    text-decoration: none;
    margin-top: 0.25rem;
    display: inline-flex;
    align-items: center;
    gap: 4px;
  }

  .card-link:hover {
    color: #8db8e8;
    text-decoration: underline;
  }

  .coming-soon-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 1rem;
    margin-top: 0.5rem;
  }

  .coming-soon-card {
    background: #181818;
    border: 1px dashed #333;
    border-radius: 10px;
    padding: 1rem 1.25rem;
    display: flex;
    flex-direction: column;
    gap: 0.4rem;
  }

  .coming-soon-card .card-category {
    color: #555;
  }

  .coming-soon-card .card-title {
    color: #555;
    font-style: italic;
    font-weight: 400;
  }

  .coming-soon-badge {
    font-size: 11px;
    color: #555;
    border: 1px dashed #3a3a3a;
    border-radius: 999px;
    padding: 2px 9px;
    width: fit-content;
  }
</style>

### **My Projects**
{: style="margin-bottom: 0.5rem;" }

<p class="projects-intro">
  Hands-on work across SOC operations, GRC, and vulnerability management — built in homelabs and real environments using industry-standard tools and frameworks. Each project links to a full write-up on GitHub.
</p>


<div class="category-label">🚨 Threat Hunting &amp; Security Operations</div>

<div class="card-grid">

  <div class="project-card">
    <span class="card-category cat-soc">SOC · SIEM · Cloud</span>
    <a class="card-title" href="https://github.com/JKopal101/ms-azure-with-siem" target="_blank">Microsoft Azure SIEM with Log Ingestion</a>
    <p class="card-outcome">Deployed Microsoft Sentinel in Azure, configured log ingestion, and built custom KQL analytics rules to detect threat activity including anomalous sign-ins and suspicious network behaviour.</p>
    <div class="card-tags">
      <span class="tag">Microsoft Sentinel</span>
      <span class="tag">KQL</span>
      <span class="tag">Azure</span>
      <span class="tag">Log Analysis</span>
      <span class="tag">Incident Response</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/ms-azure-with-siem" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-soc">SOC · IDS · Network</span>
    <a class="card-title" href="https://github.com/JKopal101/network-traffic-with-suricata" target="_blank">Network Traffic Analysis with Suricata</a>
    <p class="card-outcome">Configured Suricata as an IDS on a virtual network, loaded Emerging Threats rulesets, and analysed live traffic to detect port scans, protocol anomalies, and rule-triggered alerts.</p>
    <div class="card-tags">
      <span class="tag">Suricata</span>
      <span class="tag">IDS/IPS</span>
      <span class="tag">Network Monitoring</span>
      <span class="tag">Linux</span>
      <span class="tag">Log Analysis</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/network-traffic-with-suricata" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-soc">Threat Hunting · Endpoint</span>
    <a class="card-title" href="https://github.com/JKopal101/threat-hunting-scenario-tor" target="_blank">Threat Hunting Scenario: Tor Browser Detection</a>
    <p class="card-outcome">Simulated a Tor-based exfiltration scenario in Azure, then used Microsoft Defender and KQL hunting queries to identify the activity, trace the process tree, and document the full investigation.</p>
    <div class="card-tags">
      <span class="tag">KQL</span>
      <span class="tag">MS Defender</span>
      <span class="tag">Azure VM</span>
      <span class="tag">Threat Hunting</span>
      <span class="tag">MITRE ATT&CK</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/threat-hunting-scenario-tor" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-soc">Incident Response · Phishing</span>
    <a class="card-title" href="https://github.com/JKopal101/email-phishing-analysis" target="_blank">Incident Response: Email Phishing Analysis</a>
    <p class="card-outcome">Investigated a phishing email sample end-to-end — header analysis, URL and domain reputation checks via VirusTotal and URLscan, IOC extraction, and a structured incident report.</p>
    <div class="card-tags">
      <span class="tag">Header Analysis</span>
      <span class="tag">VirusTotal</span>
      <span class="tag">URLscan</span>
      <span class="tag">Python</span>
      <span class="tag">Report Writing</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/email-phishing-analysis" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-soc">Detection · Forensics</span>
    <a class="card-title" href="https://github.com/JKopal101/honeypot--and-canary-token-monitoring" target="_blank">Honeypot and Canary Token Monitoring</a>
    <p class="card-outcome">Deployed a honeypot and embedded canary tokens to detect unauthorised access attempts. Monitored triggered alerts, automated notifications via scripting, and analysed attacker behaviour patterns.</p>
    <div class="card-tags">
      <span class="tag">Honeypot</span>
      <span class="tag">Canary Tokens</span>
      <span class="tag">IDS</span>
      <span class="tag">Scripting</span>
      <span class="tag">Log Analysis</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/honeypot--and-canary-token-monitoring" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-soc">Recon · Network</span>
    <a class="card-title" href="https://github.com/JKopal101/Network-Scanning-with-Nmap" target="_blank">Network Scanning with Nmap</a>
    <p class="card-outcome">Performed structured network reconnaissance using Nmap across a lab environment — host discovery, port scanning, service enumeration, and OS fingerprinting — with findings documented and analysed.</p>
    <div class="card-tags">
      <span class="tag">Nmap</span>
      <span class="tag">Linux</span>
      <span class="tag">Network Recon</span>
      <span class="tag">Log Investigation</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/Network-Scanning-with-Nmap" target="_blank">View on GitHub →</a>
  </div>

</div>


<div class="category-label">⚠️ Vulnerability Management</div>

<div class="card-grid">

  <div class="project-card">
    <span class="card-category cat-vuln">Vuln Management · Cloud</span>
    <a class="card-title" href="https://github.com/JKopal101/vulnerability-management-project" target="_blank">Vulnerability Management Program Implementation</a>
    <p class="card-outcome">Designed and implemented a vulnerability management lifecycle using Tenable on Azure VMs — scanning, CVSS-based prioritisation, remediation tracking, and policy documentation.</p>
    <div class="card-tags">
      <span class="tag">Tenable</span>
      <span class="tag">Azure</span>
      <span class="tag">PowerShell</span>
      <span class="tag">BASH</span>
      <span class="tag">CVSS Prioritisation</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/vulnerability-management-project" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-vuln">Vuln Scanning · Log Analysis</span>
    <a class="card-title" href="https://github.com/JKopal101/Vulnerability-Scanning-using-Nessus" target="_blank">Vulnerability Scanning using Nessus</a>
    <p class="card-outcome">Ran authenticated and unauthenticated Nessus scans against lab targets, triaged findings by severity, and cross-referenced results with incident response logs to identify exploitable gaps.</p>
    <div class="card-tags">
      <span class="tag">Nessus</span>
      <span class="tag">Vulnerability Management</span>
      <span class="tag">Log Analysis</span>
      <span class="tag">Incident Response</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/Vulnerability-Scanning-using-Nessus" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-vuln">Vuln Assessment · Log Analysis</span>
    <a class="card-title" href="https://github.com/JKopal101/Vulnerability-Assessment-and-Log-Analysis-Lab" target="_blank">Vulnerability Assessment and Log Analysis Lab</a>
    <p class="card-outcome">Combined vulnerability assessment with log correlation in a lab environment — identifying findings, mapping them to attack patterns in logs, and producing a structured findings report.</p>
    <div class="card-tags">
      <span class="tag">Log Investigation</span>
      <span class="tag">Vulnerability Assessment</span>
      <span class="tag">Incident Response</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/Vulnerability-Assessment-and-Log-Analysis-Lab" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-vuln">Vuln Management · Volunteer</span>
    <a class="card-title" href="https://github.com/JKopal101/cybernara-project-portfolio" target="_blank">CyberNara Vulnerability Management Portfolio</a>
    <p class="card-outcome">Volunteer engagement with CyberNara — applied vulnerability management practices in a real-organisation context, including scanning with Tenable, remediation prioritisation, and policy development.</p>
    <div class="card-tags">
      <span class="tag">Tenable</span>
      <span class="tag">Azure</span>
      <span class="tag">Policy Development</span>
      <span class="tag">PowerShell</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/cybernara-project-portfolio" target="_blank">View on GitHub →</a>
  </div>

</div>


<div class="category-label">📜 Governance, Risk &amp; Compliance (GRC)</div>

<div class="card-grid">

  <div class="project-card">
    <span class="card-category cat-grc">GRC · NIST · ISO 27001</span>
    <a class="card-title" href="https://github.com/JKopal101/Conducting-a-Security-Audit" target="_blank">GRC Capstone: Security Audit and Risk Assessment</a>
    <p class="card-outcome">Conducted a full NIST-based security audit including risk register, controls gap analysis, compliance review against ISO 27001, and a remediation roadmap — presented as a professional deliverable.</p>
    <div class="card-tags">
      <span class="tag">NIST CSF</span>
      <span class="tag">ISO 27001</span>
      <span class="tag">Risk Register</span>
      <span class="tag">GDPR</span>
      <span class="tag">HIPAA</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/Conducting-a-Security-Audit" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-grc">GRC · Policy · IR</span>
    <a class="card-title" href="https://github.com/JKopal101/Conducting-a-Security-Audit" target="_blank">Conducting a Security Audit</a>
    <p class="card-outcome">Applied the NIST Risk Management Framework to evaluate an organisation's security posture — assessing controls against the CIA triad, identifying compliance gaps, and producing incident response playbook documentation.</p>
    <div class="card-tags">
      <span class="tag">NIST RMF</span>
      <span class="tag">CIA Triad</span>
      <span class="tag">IR Playbook</span>
      <span class="tag">Compliance Review</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/Conducting-a-Security-Audit" target="_blank">View on GitHub →</a>
  </div>

  <div class="project-card">
    <span class="card-category cat-grc">GRC · Architecture · Policy</span>
    <a class="card-title" href="https://github.com/JKopal101/Retail-Cyber-Defence-Strategy" target="_blank">Retail Cyber Defence Strategy</a>
    <p class="card-outcome">Designed a layered cybersecurity defence strategy for a retail organisation — applying Zero Trust architecture principles, vulnerability management controls, access control policies, and incident response procedures.</p>
    <div class="card-tags">
      <span class="tag">Zero Trust</span>
      <span class="tag">NIST RMF</span>
      <span class="tag">Access Control</span>
      <span class="tag">IR Playbook</span>
      <span class="tag">Vuln Management</span>
    </div>
    <a class="card-link" href="https://github.com/JKopal101/Retail-Cyber-Defence-Strategy" target="_blank">View on GitHub →</a>
  </div>

</div>


<div class="category-label">🔜 Coming Soon</div>

<div class="coming-soon-grid">

  <div class="coming-soon-card">
    <span class="card-category">Purple Team · Home Lab</span>
    <span class="card-title">Splunk SIEM Home Lab — Purple Team Build</span>
    <span class="coming-soon-badge">In progress</span>
  </div>

  <div class="coming-soon-card">
    <span class="card-category">Pen Testing · Vuln Assessment</span>
    <span class="card-title">Vulnerable Machine Assessment (Metasploitable2)</span>
    <span class="coming-soon-badge">In progress</span>
  </div>

  <div class="coming-soon-card">
    <span class="card-category">GRC · ISO 27001</span>
    <span class="card-title">SME Gap Assessment — ISO 27001 Scenario</span>
    <span class="coming-soon-badge">Planned</span>
  </div>

  <div class="coming-soon-card">
    <span class="card-category">Detection Engineering</span>
    <span class="card-title">Custom SPL Detection Rules — Brute Force &amp; Lateral Movement</span>
    <span class="coming-soon-badge">Planned</span>
  </div>

</div>
