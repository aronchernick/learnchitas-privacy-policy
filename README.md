<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Privacy Policy</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,600;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
  <style>
    :root {
      --ink: #1a1a2e;
      --muted: #5a5a72;
      --accent: #c8793a;
      --bg: #faf9f6;
      --card: #ffffff;
      --border: #e8e4dc;
      --rule: #d4cfc4;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'DM Sans', sans-serif;
      background: var(--bg);
      color: var(--ink);
      font-size: 16px;
      line-height: 1.8;
    }

    /* ── Top bar ── */
    header {
      border-bottom: 1px solid var(--border);
      padding: 1.2rem 2rem;
      display: flex;
      align-items: center;
      gap: 0.6rem;
      background: var(--card);
    }
    header .dot {
      width: 8px; height: 8px;
      border-radius: 50%;
      background: var(--accent);
    }
    header span {
      font-size: 0.78rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: var(--muted);
      font-weight: 500;
    }

    /* ── Hero ── */
    .hero {
      max-width: 760px;
      margin: 5rem auto 0;
      padding: 0 2rem;
    }
    .hero h1 {
      font-family: 'Lora', serif;
      font-size: clamp(2rem, 5vw, 3.2rem);
      font-weight: 600;
      line-height: 1.2;
      color: var(--ink);
    }
    .hero .meta {
      margin-top: 1rem;
      font-size: 0.85rem;
      color: var(--muted);
      display: flex;
      gap: 1.5rem;
    }
    .hero .meta span::before {
      content: "·";
      margin-right: 1.5rem;
      color: var(--rule);
    }
    .hero .meta span:first-child::before { display: none; }

    hr.fancy {
      max-width: 760px;
      margin: 2.5rem auto;
      border: none;
      border-top: 1px solid var(--rule);
    }

    /* ── TOC ── */
    .toc-wrap {
      max-width: 760px;
      margin: 0 auto 3rem;
      padding: 0 2rem;
    }
    .toc {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 1.5rem 2rem;
    }
    .toc h2 {
      font-family: 'Lora', serif;
      font-size: 0.9rem;
      font-weight: 600;
      letter-spacing: 0.06em;
      text-transform: uppercase;
      color: var(--muted);
      margin-bottom: 0.8rem;
    }
    .toc ol {
      padding-left: 1.2rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0.25rem 2rem;
    }
    .toc ol li { font-size: 0.9rem; }
    .toc a {
      color: var(--ink);
      text-decoration: none;
      transition: color 0.15s;
    }
    .toc a:hover { color: var(--accent); }

    @media (max-width: 540px) {
      .toc ol { grid-template-columns: 1fr; }
    }

    /* ── Main content ── */
    main {
      max-width: 760px;
      margin: 0 auto;
      padding: 0 2rem 6rem;
    }

    section {
      margin-bottom: 3.5rem;
      scroll-margin-top: 2rem;
    }

    h2 {
      font-family: 'Lora', serif;
      font-size: 1.4rem;
      font-weight: 600;
      color: var(--ink);
      margin-bottom: 0.75rem;
      padding-bottom: 0.5rem;
      border-bottom: 1px solid var(--border);
    }
    h2 .num {
      color: var(--accent);
      font-style: italic;
      margin-right: 0.4rem;
      font-size: 1.1rem;
    }

    p { margin-bottom: 1rem; color: #2e2e45; }
    p:last-child { margin-bottom: 0; }

    ul, ol {
      padding-left: 1.4rem;
      margin-bottom: 1rem;
    }
    li { margin-bottom: 0.35rem; color: #2e2e45; }

    strong { font-weight: 500; color: var(--ink); }

    .callout {
      background: #fff8f2;
      border-left: 3px solid var(--accent);
      border-radius: 0 6px 6px 0;
      padding: 1rem 1.2rem;
      margin: 1.2rem 0;
      font-size: 0.93rem;
    }
    .callout p { margin: 0; }

    a { color: var(--accent); }
    a:hover { text-decoration: underline; }

    /* ── Footer ── */
    footer {
      border-top: 1px solid var(--border);
      text-align: center;
      padding: 2rem;
      font-size: 0.8rem;
      color: var(--muted);
    }
  </style>
</head>
<body>

<header>
  <div class="dot"></div>
  <span>Your App Name &mdash; Legal</span>
</header>

<div class="hero">
  <h1>Privacy Policy</h1>
  <div class="meta">
    <span>Effective Date: January 1, 2025</span>
    <span>Last Updated: January 1, 2025</span>
  </div>
</div>

<hr class="fancy">

<div class="toc-wrap">
  <div class="toc">
    <h2>Contents</h2>
    <ol>
      <li><a href="#information-we-collect">Information We Collect</a></li>
      <li><a href="#how-we-use">How We Use Your Information</a></li>
      <li><a href="#sharing">Sharing &amp; Disclosure</a></li>
      <li><a href="#cookies">Cookies &amp; Tracking</a></li>
      <li><a href="#data-retention">Data Retention</a></li>
      <li><a href="#security">Security</a></li>
      <li><a href="#your-rights">Your Rights</a></li>
      <li><a href="#childrens-privacy">Children's Privacy</a></li>
      <li><a href="#third-party">Third-Party Links</a></li>
      <li><a href="#changes">Changes to This Policy</a></li>
      <li><a href="#contact">Contact Us</a></li>
    </ol>
  </div>
</div>

<main>

  <section>
    <p>
      This Privacy Policy describes how <strong>Aaron Chernick</strong> ("we," "us," or "our") collects, uses, and shares information about you when you use <strong>Learn Chitas</strong> (the "Service"). By using the Service, you agree to the collection and use of information in accordance with this policy.
    </p>
    <div class="callout">
      <p>If you have questions about this policy or your data, contact us at <a href="mailto:aronchernick@gmail.com">aronchernick@gmail.com</a>.</p>
    </div>
  </section>

  <section id="information-we-collect">
    <h2><span class="num">1.</span> Information We Collect</h2>
    <p>We collect information you provide directly, information collected automatically, and information from third parties.</p>

    <p><strong>Information you provide directly:</strong></p>
    <ul>
      <li>Account registration details (name, email address, password)</li>
      <li>Profile information you choose to add</li>
      <li>Content you create, upload, or submit through the Service</li>
      <li>Communications you send us (support requests, feedback)</li>
      <li>Payment information (processed by our payment provider; we do not store raw card numbers)</li>
    </ul>

    <p><strong>Information collected automatically:</strong></p>
    <ul>
      <li>Log data: IP address, browser type, pages visited, time and date of visits, referring URLs</li>
      <li>Device information: hardware model, operating system, unique device identifiers</li>
      <li>Usage data: features used, actions taken, session duration</li>
      <li>Cookies and similar tracking technologies (see Section 4)</li>
    </ul>

    <p><strong>Information from third parties:</strong></p>
    <ul>
      <li>If you sign in via Google, Apple, or another OAuth provider, we receive basic profile information they share with us</li>
      <li>Analytics partners may provide aggregated demographic or interest data</li>
    </ul>
  </section>

  <section id="how-we-use">
    <h2><span class="num">2.</span> How We Use Your Information</h2>
    <p>We use the information we collect to:</p>
    <ul>
      <li>Provide, operate, and improve the Service</li>
      <li>Create and manage your account</li>
      <li>Process transactions and send related confirmations</li>
      <li>Send you technical notices, security alerts, and support messages</li>
      <li>Respond to your comments and questions</li>
      <li>Send marketing communications (where permitted by law and your preferences)</li>
      <li>Monitor and analyze trends, usage, and activities to improve the Service</li>
      <li>Detect, investigate, and prevent fraudulent transactions and other illegal activities</li>
      <li>Comply with legal obligations</li>
    </ul>
    <p>We process your data on the following legal bases: performance of a contract, legitimate interests, compliance with legal obligations, and, where required, your consent.</p>
  </section>

  <section id="sharing">
    <h2><span class="num">3.</span> Sharing &amp; Disclosure</h2>
    <p>We do not sell your personal information. We may share your information in the following circumstances:</p>
    <ul>
      <li><strong>Service providers:</strong> We share data with vendors who help us operate the Service (hosting, analytics, payment processing, email delivery). They are contractually bound to protect your data and use it only for the services they provide to us.</li>
      <li><strong>Business transfers:</strong> If we are involved in a merger, acquisition, or sale of assets, your information may be transferred as part of that transaction. We will notify you before your information is transferred and becomes subject to a different privacy policy.</li>
      <li><strong>Legal requirements:</strong> We may disclose your information if required by law, subpoena, or other legal process, or if we believe in good faith that disclosure is necessary to protect our rights, protect your safety or the safety of others, investigate fraud, or comply with a governmental request.</li>
      <li><strong>With your consent:</strong> We may share information with third parties when you give us explicit consent to do so.</li>
    </ul>
  </section>

  <section id="cookies">
    <h2><span class="num">4.</span> Cookies &amp; Tracking</h2>
    <p>We use cookies, web beacons, and similar tracking technologies to collect and track information about your use of the Service.</p>
    <ul>
      <li><strong>Essential cookies:</strong> Required for the Service to function (authentication, security). Cannot be disabled.</li>
      <li><strong>Analytics cookies:</strong> Help us understand how the Service is used (e.g., Google Analytics).</li>
      <li><strong>Preference cookies:</strong> Remember your settings and preferences.</li>
      <li><strong>Marketing cookies:</strong> Used to deliver relevant advertising (where applicable).</li>
    </ul>
    <p>You can control cookies through your browser settings. Disabling certain cookies may affect the functionality of the Service. Where required by law, we will obtain your consent before placing non-essential cookies.</p>
  </section>

  <section id="data-retention">
    <h2><span class="num">5.</span> Data Retention</h2>
    <p>We retain your personal information for as long as your account is active or as needed to provide the Service. We will also retain and use your information as necessary to comply with legal obligations, resolve disputes, and enforce our agreements.</p>
    <p>When you delete your account, we will delete or anonymize your personal information within <strong>30 days</strong>, except where retention is required by law or for legitimate business purposes (e.g., fraud prevention, accounting records).</p>
  </section>

  <section id="security">
    <h2><span class="num">6.</span> Security</h2>
    <p>We implement industry-standard technical and organizational measures to protect your information, including encryption in transit (TLS) and at rest, access controls, and regular security assessments.</p>
    <div class="callout">
      <p>No method of transmission over the internet or electronic storage is 100% secure. While we strive to protect your personal information, we cannot guarantee its absolute security. If you believe your account has been compromised, contact us immediately.</p>
    </div>
  </section>

  <section id="your-rights">
    <h2><span class="num">7.</span> Your Rights</h2>
    <p>Depending on your location, you may have the following rights regarding your personal information:</p>
    <ul>
      <li><strong>Access:</strong> Request a copy of the personal information we hold about you.</li>
      <li><strong>Correction:</strong> Request that we correct inaccurate or incomplete information.</li>
      <li><strong>Deletion:</strong> Request that we delete your personal information ("right to be forgotten").</li>
      <li><strong>Portability:</strong> Request your data in a structured, machine-readable format.</li>
      <li><strong>Restriction:</strong> Request that we restrict processing of your data in certain circumstances.</li>
      <li><strong>Objection:</strong> Object to processing based on legitimate interests or for direct marketing.</li>
      <li><strong>Withdraw consent:</strong> Where processing is based on consent, withdraw it at any time without affecting the lawfulness of prior processing.</li>
      <li><strong>Opt-out of sale/sharing (CCPA):</strong> California residents may opt out of the sale or sharing of personal information.</li>
    </ul>
    <p>To exercise any of these rights, contact us at <a href="mailto:aronchernick@gmail">aronchernick@gmail</a>. We will respond within 30 days. We may need to verify your identity before fulfilling your request.</p>
  </section>

  <section id="childrens-privacy">
    <h2><span class="num">8.</span> Children's Privacy</h2>
    <p>The Service is not directed to children under the age of 13 (or 16 in the European Economic Area). We do not knowingly collect personal information from children. If we become aware that we have collected personal information from a child without parental consent, we will take steps to delete that information promptly.</p>
    <p>If you are a parent or guardian and believe your child has provided us with personal information, please contact us at <a href="mailto:aronchernick@gmail">privacy@yourdomain.com</a>.</p>
  </section>

  <section id="third-party">
    <h2><span class="num">9.</span> Third-Party Links &amp; Services</h2>
    <p>The Service may contain links to third-party websites, apps, or services. This Privacy Policy does not apply to those third parties, and we are not responsible for their privacy practices. We encourage you to review the privacy policies of any third-party services you access.</p>
  </section>

  <section id="changes">
    <h2><span class="num">10.</span> Changes to This Policy</h2>
    <p>We may update this Privacy Policy from time to time. When we make material changes, we will notify you by updating the "Last Updated" date at the top of this page and, where required by law, by sending an email or displaying a prominent notice in the Service.</p>
    <p>Your continued use of the Service after changes take effect constitutes your acceptance of the revised policy. We encourage you to review this policy periodically.</p>
  </section>

  <section id="contact">
    <h2><span class="num">11.</span> Contact Us</h2>
    <p>If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:</p>
    <ul>
      <li><strong>Email:</strong> <a href="mailto:aronchernick@gmail">privacy@yourdomain.com</a></li>
      <li><strong>Mailing address:</strong> Aaron Chernick, 727 Fenimore St, Apt 1, Brooklyn, NY 11203, USA</li>
    </ul>
    <p>If you are located in the European Economic Area and have concerns about our data practices that we have not resolved, you have the right to lodge a complaint with your local data protection authority.</p>
  </section>

</main>

<footer>
  &copy; 2026 Aaron Chernick. All rights reserved.
</footer>

</body>
</html>
