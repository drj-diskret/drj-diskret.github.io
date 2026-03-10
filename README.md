---
layout: default
---

<header>
  <div class="business-name">Diskret/div>
  <div class="tagline">Pentesting, offensive security tooling, and building labs that mirror the messy real world.</div>
  <div class="divider"></div>
</header>

<div class="contacts">

  <div class="contact-item">
    <span class="contact-label">Email</span>
    <div class="contact-body">
      <div class="copy-row">
        <span class="contact-value" id="email-val">website@diskret.io<</span>
        <button class="copy-btn" onclick="copyTo('email-val', this)">Copy</button>
      </div>
      <span class="contact-note">PGP encryption preferred, see key below.</span>
    </div>
  </div>

  <div class="contact-item">
    <span class="contact-label">PGP</span>
    <div class="contact-body">
      <div class="fingerprint" id="pgp-fp">fd8af903ec30b423ee6c40d80ed5d21fca550719</div>
      <div class="copy-row" style="margin-top:0.45rem;">
        <button class="copy-btn" onclick="copyTo('pgp-fp', this)">Copy fingerprint</button>
      </div>
      <div class="pgp-links">
        <a class="pgp-link" href="/publickey.asc">Download public key ↓</a>
      </div>
    </div>
  </div>

  <div class="contact-item">
    <span class="contact-label">Threema</span>
    <div class="contact-body">
      <div class="copy-row">
      <!-- <img src="/threema-qr.webp" alt="Threema QR" style="margin-top:0.6rem;width:96px;height:96px;border-radius:4px;" /> -->
    </div>
  </div>
</div>

<footer>NDAs and rigorous security practices are standard.</footer>
