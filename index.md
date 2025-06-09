---
layout: default
title: Non-Invasive Blood Test for Oncology — Sensitive and Specific Detection
permalink: /
---
<img src="assets/double-strandLLC.png" alt="Double-Strand Logo" style="width: 100px; height: auto;">  

<nav>
  <a href="/">Home</a> |
  <a href="/about/">About</a> |
  <a href="/rnd/">R&D</a> |
  <a href="/contact/">Contact</a>
</nav>

# Blood test platform focused on non-invasive, sensitive, and specific detection of cancer-related biomarkers. 

We discover and develop non-invasive molecular tests based on nucleic acid analytes.


<img src="assets/plasmaAnalytes.png" alt="Double-Strand Logo" style="width: 200px; height: auto;">     
  
<hr>  

<div style="background-color: #123456; color: white; text-align: center; padding: 5px; width: 100%;">
  <p>© 2025 double-strand LLC. All rights reserved.</p>
  <p>
    <a href="/contact" style="color: #1e90ff; text-decoration: none; margin: 0 10px;">Contact</a> |
    <a href="/privacy_policy" style="color: #1e90ff; text-decoration: none; margin: 0 10px;">Privacy Policy</a>
  </p>
</div>

<div id="cookie-consent" style="position:fixed;bottom:0;width:100%;background:#222;color:#fff;padding:1em;text-align:center;z-index:1000;">
  This site uses cookies for Google Analytics.  
  <button onclick="acceptCookies()" style="margin-left:10px;">Accept</button>
  <button onclick="denyCookies()" style="margin-left:10px;">Deny</button>
</div>

<script async src="https://www.googletagmanager.com/gtag/js?id=G-8CK10GD9RF"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){ dataLayer.push(arguments); }

  function initGA() {
    gtag('js', new Date());
    gtag('config', 'G-XXXXXXX');
  }

  function acceptCookies() {
    localStorage.setItem("ga_consent", "accepted");
    initGA();
    document.getElementById("cookie-consent").style.display = "none";
  }

  function denyCookies() {
    localStorage.setItem("ga_consent", "denied");
    document.getElementById("cookie-consent").style.display = "none";
  }

  window.onload = function() {
    const consent = localStorage.getItem("ga_consent");
    if (consent === "accepted") {
      initGA();
      document.getElementById("cookie-consent").style.display = "none";
    } else if (consent === "denied") {
      document.getElementById("cookie-consent").style.display = "none";
    }
  }
</script>
