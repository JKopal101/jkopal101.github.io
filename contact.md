---
layout: default
title: Contact
permalink: /contact/
---

{% raw %}
<style>
  .contact-intro {
    font-size: 16px;
    line-height: 1.7;
    color: #aaa;
    max-width: 560px;
    margin-bottom: 2.5rem;
  }

  .contact-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1rem;
    margin-bottom: 2.5rem;
  }

  .contact-card {
    background: #1e1e1e;
    border: 1px solid #333;
    border-radius: 10px;
    padding: 1.25rem 1.5rem;
    display: flex;
    align-items: center;
    gap: 1rem;
    text-decoration: none;
    transition: border-color 0.2s, background 0.2s;
  }

  .contact-card:hover {
    border-color: #555;
    background: #252525;
    text-decoration: none;
  }

  .contact-icon {
    width: 40px;
    height: 40px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-shrink: 0;
  }

  .icon-linkedin { background: #0a3d6b; }
  .icon-github   { background: #2a2a2a; border: 1px solid #444; }
  .icon-email    { background: #5c1a1a; }
  .icon-twitter  { background: #0d2d45; }

  .contact-icon svg {
    width: 20px;
    height: 20px;
    fill: #fff;
  }

  .contact-label {
    display: flex;
    flex-direction: column;
    gap: 2px;
  }

  .contact-platform {
    font-size: 13px;
    font-weight: 600;
    color: #f0f0f0;
  }

  .contact-handle {
    font-size: 12px;
    color: #888;
  }

  .cv-section {
    border-top: 1px solid #2a2a2a;
    padding-top: 2rem;
  }

  .cv-label {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #555;
    margin-bottom: 1rem;
  }

  .cv-card {
    display: inline-flex;
    align-items: center;
    gap: 0.75rem;
    background: #1e1e1e;
    border: 1px solid #333;
    border-radius: 10px;
    padding: 1rem 1.5rem;
    text-decoration: none;
    transition: border-color 0.2s;
  }

  .cv-card:hover {
    border-color: #555;
    text-decoration: none;
  }

  .cv-card svg {
    width: 18px;
    height: 18px;
    fill: #6b9fd4;
    flex-shrink: 0;
  }

  .cv-text {
    display: flex;
    flex-direction: column;
    gap: 2px;
  }

  .cv-title {
    font-size: 14px;
    font-weight: 600;
    color: #f0f0f0;
  }

  .cv-sub {
    font-size: 12px;
    color: #888;
  }
</style>

<h3><strong>Contact</strong></h3>

<p class="contact-intro">
  Open to SOC analyst, GRC analyst, and junior security roles in the Canadian market. Feel free to reach out on LinkedIn or by email — I'm always happy to connect.
</p>

<div class="contact-grid">

  <a class="contact-card" href="https://www.linkedin.com/in/james-kopal/" target="_blank">
    <div class="contact-icon icon-linkedin">
      <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
      </svg>
    </div>
    <div class="contact-label">
      <span class="contact-platform">LinkedIn</span>
      <span class="contact-handle">james-kopal</span>
    </div>
  </a>

  <a class="contact-card" href="https://github.com/jkopal101" target="_blank">
    <div class="contact-icon icon-github">
      <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
    </div>
    <div class="contact-label">
      <span class="contact-platform">GitHub</span>
      <span class="contact-handle">jkopal101</span>
    </div>
  </a>

  <a class="contact-card" href="mailto:jkopal101@gmail.com">
    <div class="contact-icon icon-email">
      <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M24 5.457v13.909c0 .904-.732 1.636-1.636 1.636h-3.819V11.73L12 16.64l-6.545-4.91v9.273H1.636A1.636 1.636 0 010 19.366V5.457c0-.9.74-1.636 1.636-1.636h.49L12 10.09l9.874-6.269h.49A1.636 1.636 0 0124 5.457z"/>
      </svg>
    </div>
    <div class="contact-label">
      <span class="contact-platform">Email</span>
      <span class="contact-handle">jkopal101@gmail.com</span>
    </div>
  </a>

  <a class="contact-card" href="https://x.com/j_kopal" target="_blank">
    <div class="contact-icon icon-twitter">
      <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-4.714-6.231-5.401 6.231H2.744l7.73-8.835L1.254 2.25H8.08l4.253 5.622 5.91-5.622zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
      </svg>
    </div>
    <div class="contact-label">
      <span class="contact-platform">X / Twitter</span>
      <span class="contact-handle">@j_kopal</span>
    </div>
  </a>

</div>

<div class="cv-section">
  <p class="cv-label">CV / Resume</p>
  <a class="cv-card" href="https://docs.google.com/document/d/1F_LVblUTnLC8-tz-HEI1capla8Y_Z3qq/edit" target="_blank">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path d="M14 2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V8l-6-6zm-1 1.5L18.5 9H13V3.5zM6 20V4h5v7h7v9H6z"/>
    </svg>
    <div class="cv-text">
      <span class="cv-title">View CV / Resume</span>
      <span class="cv-sub">Opens in Google Docs</span>
    </div>
  </a>
</div>
{% endraw %}
