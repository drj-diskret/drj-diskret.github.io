---
layout: default
---

<header>
  <div class="business-name">Diskret</div>
  <!-- Optional one-line descriptor. Delete the line below if not needed. -->
  <div class="tagline">Pentesting, offensive security tooling, and building labs that mirror the messy real world.</div>
  <div class="divider"></div>
</header>

<div class="contacts">

  <div class="contact-item">
    <span class="contact-label">Email</span>
    <div class="contact-body">
      <div class="copy-row">
        <span class="contact-value" id="email-val">website@diskret.io</span>
        <button class="copy-btn" onclick="copyTo('email-val', this)">Copy</button>
      </div>
      <span class="contact-note">PGP encryption preferred — key below.</span>
    </div>
  </div>

  <div class="contact-item">
    <span class="contact-label">PGP</span>
    <div class="contact-body">
      <div class="fingerprint" id="pgp-fp">fd8af903ec30b423ee6c40d80ed5d21fca550719</div> 
      <div class="copy-row" style="margin-top:0.4rem;">
        <button class="copy-btn" onclick="copyTo('pgp-fp', this)">Copy fingerprint</button>
        <a class="pgp-link" href="https://keys.openpgp.org/search?q=you@yourdomain.com" target="_blank" rel="noopener noreferrer">Full public key ↗</a>
      </div>
    </div>
  </div>

  <div class="contact-item">
    <span class="contact-label">Signal</span>
    <div class="contact-body">
      <div class="copy-row">
        <span class="contact-value" id="signal-val">@diskret.01</span>
        <button class="copy-btn" onclick="copyTo('signal-val', this)">Copy</button>
      </div>
      <span class="contact-note">Note safety number on first contact.</span>
    </div>
  </div>

  <div class="contact-item">
    <span class="contact-label">Threema</span>
    <div class="contact-body">
      <div class="copy-row">
        <span class="contact-value" id="threema-val">5CB6Y5V8</span>
        <button class="copy-btn" onclick="copyTo('threema-val', this)">Copy</button>
      </div>
      <span class="contact-note">Verify via QR on first contact where possible.</span>
    </div>
  </div>

</div>

<!-- Optional footer line. E.g. "By appointment." / "Referrals only." — or delete. -->
<footer>By appointment.</footer>
