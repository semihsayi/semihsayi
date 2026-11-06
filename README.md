<img src="https://capsule-render.vercel.app/api?type=waving&color=0:512BD4,100:2B7FD4&height=180&section=header&text=Semih%20Say%C4%B1&fontColor=ffffff&fontSize=52&fontAlignY=36&desc=Full-Stack%20Software%20Engineer%20%C2%B7%20.NET&descAlignY=58&descSize=18" alt="Semih Sayı · Full-Stack Software Engineer" width="100%" />

<div align="center">

🇹🇷 Based in Turkey · On GitHub since 2018

<a href="https://git.io/typing-svg">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=A78BFA&center=true&vCenter=true&width=560&lines=Enterprise+software+on+.NET;Identity%2C+SSO+%26+Active+Directory;e-Signature+%26+public-sector+integrations;Building+products+end+to+end" />
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=512BD4&center=true&vCenter=true&width=560&lines=Enterprise+software+on+.NET;Identity%2C+SSO+%26+Active+Directory;e-Signature+%26+public-sector+integrations;Building+products+end+to+end" alt="Enterprise software on .NET · Identity, SSO & Active Directory · e-Signature & public-sector integrations" />
  </picture>
</a>

<a href="https://www.linkedin.com/in/semihsayi/"><img src="https://img.shields.io/badge/LinkedIn-semihsayi-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://github.com/semihsayi"><img src="https://img.shields.io/badge/GitHub-semihsayi-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>

</div>

---

## 👋 About Me

I design, build and ship enterprise applications with **C# and .NET**, from the database and back-end services to the user interface, release pipeline and on-site deployment. My systems run in universities and public institutions: research funding and procurement, academic recruitment, student housing and student communities, identity and electronic signature.

I care about security and maintainability as much as features: I harden what I ship, automate releases and document everything for both users and integrators. Most of my work is closed source, so client names are omitted here.

<table align="center">
  <tr>
    <td align="center" width="160"><h2>4,000+</h2>commits across<br>production systems</td>
    <td align="center" width="160"><h2>3,000+</h2>commits on a platform<br>used by universities</td>
    <td align="center" width="160"><h2>9</h2>organizations running<br>my AD self-service portal</td>
    <td align="center" width="160"><h2>65%</h2>fewer password-reset<br>requests to IT</td>
  </tr>
</table>

## 🛠️ What I Do

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏛️ Institutional Platforms</h3>
      <ul>
        <li>A research funding platform with <b>20+ modules</b>: applications, peer review, budgets, procurement and tenders, accounting, committee meetings, ethics board, intellectual property, audit and reporting</li>
        <li>Academic recruitment with jury evaluation, plus student housing and student community portals</li>
        <li>Auto-generated official PDF documents and Excel reports</li>
        <li>Migrated a legacy database with <b>50+ versioned scripts</b></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 Identity &amp; Access</h3>
      <ul>
        <li>A central <b>e-Devlet login gateway</b> (OAuth2 + PKCE) that several applications plug into without handling tokens or secrets themselves</li>
        <li>SAML2 SSO, LDAP / Active Directory, MFA with SMS and TOTP</li>
        <li><a href="https://github.com/semihsayi/self-service-ad">Self-Service AD</a>: password and account self-service used by <b>9 organizations</b>, with delegated OU administration that needs no Domain Admin rights</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>✍️ Electronic Signature</h3>
      <ul>
        <li>Qualified e-signature with smart cards over <b>PKCS#11</b></li>
        <li>Signing workflows that enforce signing order for applications, jury and review reports, and meeting minutes</li>
        <li>A <b>multi-tenant signing API</b> where every document is signed with the signer's own card through a tray app and a local HTTP bridge, then verified on the server</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔗 Government Integrations</h3>
      <ul>
        <li>e-Devlet, KPS identity verification, YÖKSİS academic CV and project sync, ÖSYM exam and placement results</li>
        <li>Node.js / Express services in front of SOAP endpoints with <b>WS-Security</b> (nonce and password digest), mapping the XML into SQL Server</li>
        <li>Pluggable SMS, e-mail and Slack notification providers</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ Real-Time &amp; AI</h3>
      <ul>
        <li>A Kahoot-style multiplayer quiz platform on <b>SignalR</b> with live scoreboards, team mode and scheduled games</li>
        <li>AI quiz generation with Ollama and OpenAI, including quizzes from PDFs and adaptive difficulty</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>📦 Product Delivery</h3>
      <ul>
        <li>Products shipped as <b>signed release packages</b> with automatic on-site updaters (PowerShell, ClickOnce)</li>
        <li>A tamper-resistant license activation module (AES, TOTP, single license-admin lock) shared by <b>6 products</b></li>
        <li>Clinic management software (<a href="https://github.com/semihsayi/kolay-dent">KolayDent</a>) that runs offline on-site</li>
      </ul>
    </td>
  </tr>
</table>

## 🧰 Tech Stack

| Area | Technologies |
|---|---|
| **Back-End** | C# / .NET 8–10, ASP.NET Core (MVC, Razor Pages, Web API), SignalR, Entity Framework Core, Node.js (Express), Go, PHP |
| **Front-End** | Razor, JavaScript, TypeScript, Bootstrap, jQuery, DataTables, HTML / CSS |
| **Identity & Security** | ASP.NET Core Identity, SAML2, OAuth2 / PKCE, JWT, LDAP / Active Directory, TOTP / SMS MFA, PKCS#11 e-signature |
| **Integration** | REST, SOAP, WS-Security, government web services (e-Devlet, ÖSYM, YÖKSİS, KPS) |
| **Messaging & Jobs** | RabbitMQ, Hangfire, Redis |
| **Observability** | Serilog, Seq, OpenTelemetry, Elastic APM, health checks |
| **DevOps** | GitHub Actions, Docker, IIS, PowerShell, ClickOnce |
| **Databases** | SQL Server, MongoDB |
| **Testing** | xUnit, Moq |
| **Mobile** | Kotlin |

<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,nodejs,express,go,php,js,ts,html,css,bootstrap,jquery,kotlin,docker,githubactions,redis,rabbitmq,powershell,mongodb&perline=9" alt="Tech stack icons" />
</p>

## 🏗️ How I Build

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🧱 Architecture</h4>
      Layered and onion architectures, the repository and unit-of-work patterns, CQRS and API gateways on EF Core. Distributed setups split into Web API, UI and worker services that talk over RabbitMQ, with Redis caching. Validation sits at the edges (FluentValidation) and responses share one <code>Result&lt;T&gt;</code> model.
    </td>
    <td width="50%" valign="top">
      <h4>🛡️ Security</h4>
      Hardening sweeps against IDOR, TOCTOU, CSRF and open redirects, including one pass of 100+ commits on a single platform. MFA, rate limiting, reCAPTCHA, IP allow-lists, security headers and CSP. File uploads validated by magic bytes, and sensitive fields kept out of logs and JSON responses.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🚢 Delivery</h4>
      GitHub Actions for build, test, release, dependency audit and secret scanning. Signed release packages with automatic updaters, versioned database migrations, and xUnit / Moq tests.
    </td>
    <td width="50%" valign="top">
      <h4>🔍 Observability</h4>
      Structured logging with Serilog and Seq, OpenTelemetry traces and metrics, Elastic APM, health checks, correlation IDs, plus Slack alerts for outages and suspicious IPs.
    </td>
  </tr>
</table>

## 📊 GitHub Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=semihsayi&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=github_dark&bg_color=00000000&title_color=A78BFA&icon_color=A78BFA" />
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=semihsayi&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&bg_color=00000000&title_color=512BD4&icon_color=512BD4" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=semihsayi&hide_border=true&theme=github-dark-blue&background=00000000&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA" />
    <img height="165" src="https://streak-stats.demolab.com?user=semihsayi&hide_border=true&background=00000000&ring=512BD4&fire=512BD4&currStreakLabel=512BD4" alt="GitHub streak" />
  </picture>
</p>

## 📫 Get in Touch

I'm open to new projects and collaborations. The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/semihsayi/).

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2B7FD4,100:512BD4&height=100&section=footer" alt="" width="100%" />
