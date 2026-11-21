<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:020617,40:0a0e17,100:052e1f&height=260&section=header&text=%3E_%20mr-coder20&fontSize=62&fontColor=00FF9D&fontAlignY=40&stroke=00FF9D&strokeWidth=1&desc=SOC%20Analyst%20%E2%80%A2%20Pentester%20%E2%80%A2%20Bug%20Bounty%20Hunter%20%E2%80%A2%20Mobile%20AppSec&descSize=18&descAlignY=64&descFill=00F0FF&animation=twinkling" width="100%" alt="header"/>

<a href="https://github.com/mr-coder20"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2600&pause=800&color=00FF9D&background=0A0E1700&center=true&vCenter=true&width=900&height=50&lines=root%40kali%3A~%23+whoami+%E2%86%92+Amirhossein+Ghafari;root%40kali%3A~%23+nmap+-sV+-sC+--script+vuln+target;root%40kali%3A~%23+frida+-U+-f+com.target.app+-l+bypass_pinning.js;root%40kali%3A~%23+curl+-H+%22Authorization%3A+Bearer+%24FORGED_JWT%22+%2Fapi%2Fadmin;root%40siem%3A~%23+alert+triage+%E2%86%92+enrich+IOC+%E2%86%92+contain+%E2%86%92+report;root%40kali%3A~%23+echo+%22I+break+it.+Then+I+defend+it.%22" alt="typing"/></a>

<br/>

<img src="https://img.shields.io/badge/SOC-BLUE_TEAM-0088CC?style=for-the-badge&logo=elastic&logoColor=fff&labelColor=0a0e17"/>
<img src="https://img.shields.io/badge/PENTEST-RED_TEAM-FF0055?style=for-the-badge&logo=kalilinux&logoColor=fff&labelColor=0a0e17"/>
<img src="https://img.shields.io/badge/PURPLE-TEAM-A855F7?style=for-the-badge&logo=target&logoColor=fff&labelColor=0a0e17"/>
<img src="https://img.shields.io/badge/BUG_BOUNTY-HUNTER-00FF9D?style=for-the-badge&logo=hackerone&logoColor=000&labelColor=0a0e17"/>
<img src="https://img.shields.io/badge/MOBILE-APPSEC-A855F7?style=for-the-badge&logo=android&logoColor=fff&labelColor=0a0e17"/>

<br/>

<a href="https://mr-coder20.github.io/my-portfolio/"><img src="https://img.shields.io/badge/PORTFOLIO-00F0FF?style=flat-square&logo=googlechrome&logoColor=000&labelColor=0a0e17"/></a>
<a href="https://t.me/a_god_3_6_9"><img src="https://img.shields.io/badge/TELEGRAM-0088CC?style=flat-square&logo=telegram&logoColor=fff&labelColor=0a0e17"/></a>
<a href="mailto:amirhosseinghafari29@gmail.com"><img src="https://img.shields.io/badge/EMAIL-FF0055?style=flat-square&logo=gmail&logoColor=fff&labelColor=0a0e17"/></a>
<a href="https://youtube.com"><img src="https://img.shields.io/badge/YOUTUBE-FF0000?style=flat-square&logo=youtube&logoColor=fff&labelColor=0a0e17"/></a>
<img src="https://komarev.com/ghpvc/?username=mr-coder20&style=flat-square&color=00FF9D&label=RECON+COUNT&labelColor=0a0e17"/>

</div>

<br/>

## `root@mr-coder20:~# cat /etc/profile`

```yaml
user:        Amirhossein Ghafari
alias:       mr-coder20
shell:       /bin/zsh
roles:
  - SOC Analyst          # monitoring · triage · IOC enrichment · incident response
  - Penetration Tester   # network · web · API · Android
  - Purple Teamer        # emulate attacks → validate detections → close gaps
  - Bug Bounty Hunter    # recon → exploit → report
  - Android Developer    # Kotlin · Compose · KMP
specialty:   Mobile AppSec · Auth & JWT attacks · API access-control flaws · Frida runtime hooking
education:   B.Sc. Software Engineering (Rajaei Technical College, Kashan)
mindset:     "Think like an attacker. Work like a defender. Report like a professional."
status:      ONLINE // ZERO-TRUST ENFORCED // 127.0.0.1
```

---

## 🔴 `./kill_chain.sh` — How I Hunt

```text
 ┌──────────┐   ┌──────────────┐   ┌────────────────┐   ┌─────────────┐   ┌──────────┐   ┌──────────┐
 │ 🔎 RECON │ → │ 📡 ENUMERATE │ → │ 🧪 VULN ANALYSIS│ → │ 💥 EXPLOIT  │ → │ 🧬 IMPACT│ → │ 📝 REPORT│
 └──────────┘   └──────────────┘   └────────────────┘   └─────────────┘   └──────────┘   └──────────┘
  subdomains     Nmap · endpoints   OWASP · logic ·      Frida · Burp ·    PoC · data     steps ·
  ports · tech   APK · traffic      auth flaws           JWT attacks       exposure       severity · fix
```

## 🔵 `./soc_playbook.sh` — How I Defend

```text
 ┌──────────┐   ┌──────────┐   ┌───────────┐   ┌───────────┐   ┌─────────────┐   ┌────────────┐
 │ 🚨 ALERT │ → │ 🧭 TRIAGE│ → │ 🧪 ENRICH │ → │ 🔒 CONTAIN│ → │ 🧹 ERADICATE│ → │ 📚 DOCUMENT│
 └──────────┘   └──────────┘   └───────────┘   └───────────┘   └─────────────┘   └────────────┘
  SIEM · IDS     true / false   VirusTotal ·     isolate · block  root cause ·     timeline · IOCs
  EDR            positive       AbuseIPDB · OTX  revoke tokens    patch            lessons learned
```

## 🟣 `./purple_team.sh` — Where Attack Meets Detection

```text
        ┌───────────────────────────────────────────────────────────┐
        │                    🟣  PURPLE TEAM LOOP                    │
        └───────────────────────────────────────────────────────────┘

   🔴 EMULATE ──► 🔵 DETECT ──► 🔍 FIND THE GAP ──► 🛠️ TUNE & FIX ──► ♻️ RE-TEST
        ▲                                                                  │
        └──────────────────────────────────────────────────────────────────┘
```

I run the attack, check whether the SOC would actually see it, then close the gap.

| 🔴 Attack (Red) | 🔵 Detection signal (Blue) | 🟣 Fix (Purple) |
|:--|:--|:--|
| Nmap port / service scan | One source hitting many ports in a short window | Rate-based alert, firewall rule, IOC enrichment |
| JWT tampering (`alg:none`, weak secret) | Signature-validation failures, odd claims | Strict verification, short expiry, key rotation |
| IDOR / BOLA enumeration | Sequential ID access, 200/403 spikes per user | Server-side ownership checks, enumeration alert |
| Credential brute-force | Repeated 401s per IP / account | Lockout, rate limiting, MFA |
| Frida hooking / pinning bypass | Proxy or hook indicators, abnormal API behaviour | Never trust the client: server-side validation, tamper checks |
| Suspicious IP / domain contact | Match against threat-intel feeds | Auto-enrichment with **IOC Lens**, blocklist update |

---

## ⚔️ Offensive & Defensive Capability Matrix

| Domain | Skills & Techniques |
|:--|:--|
| 🔴 **Mobile Pentest** | `Frida hooking` `SSL pinning bypass` `APK reverse engineering` `Insecure storage` `WebView abuse` `Token extraction` `OWASP Mobile Top 10` |
| 🔴 **API / Web Pentest** | `JWT attacks` `IDOR / BOLA` `Broken auth & access control` `Input validation flaws` `Burp Suite` `Traffic analysis` `WordPress auditing` |
| 🔴 **Network Pentest** | `Nmap recon` `Service & port enumeration` `Windows server misconfigs` `Wireshark` `VLAN / firewall review` |
| 🔵 **SOC / Blue Team** | `SIEM log analysis` `Alert triage` `IOC enrichment` `Incident response` `Threat hunting` `MITRE ATT&CK mapping` `Reporting & timelines` |
| 🟣 **Purple Team** | `Attack emulation` `Detection validation` `Gap analysis` `Alert tuning` `MITRE ATT&CK mapping` `Red↔Blue reporting` |
| 🟣 **Secure Engineering** | `Anti-ZipSlip` `Secure WebView` `Least-privilege permissions` `Privacy-first design` `Safe token storage` |
| 🟢 **Infra** | `Linux` `MikroTik (MTCNA)` `Cisco VLAN` `Windows Server / AD / DHCP` `VMware ESXi` `Docker` |

### 🧰 Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=kali,linux,bash,python,go,kotlin,java,androidstudio,docker,git,github,gradle&theme=dark&perline=12" alt="tools"/>

<br/>

`Burp Suite` · `Frida` · `jadx` · `apktool` · `MobSF` · `Nmap` · `Wireshark` · `Postman` · `Python AsyncIO` · `Go CLI`

</div>

---

## 🧬 MITRE ATT&CK — Where I Operate

```text
 RECONNAISSANCE ──── Active scanning · Gather victim host/network info
 INITIAL ACCESS ──── Exploit public-facing apps · Valid accounts (weak auth)
 CREDENTIAL ACCESS ─ Unsecured credentials · Token theft · Brute-force detection
 DISCOVERY ───────── Network service scanning · Account & system discovery
 DEFENSE EVASION ─── Pinning bypass · Obfuscation analysis
 EXFILTRATION ────── API data exposure · Insecure storage review
 DETECTION ───────── Log correlation · IOC triage · Alert tuning
```

---

## 🛰️ Open-Source Systems

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🛡️ [IOC Lens](https://github.com/mr-coder20/ioc-lens)
**`[BLUE TEAM]` Privacy-first threat triage engine**
Aggregates IOCs from VirusTotal, AbuseIPDB, OTX & URLhaus into a single explainable verdict. Zero telemetry — everything stays on-device.

`Kotlin Multiplatform` `Compose` `Android` `iOS` `Desktop`

</td>
<td width="50%" valign="top">

### 🌐 [L7 Resilience Scanner](https://github.com/mr-coder20/L7-Resilience-Scanner)
**`[RED/BLUE]` Layer-7 traffic analysis**
Measures application-layer resilience under micro-burst HTTP/HTTPS workloads with latency profiling and anomaly detection. *Authorized testing only.*

`Python` `AsyncIO` `HTTP/2`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📡 [FireScan / PortX](https://github.com/mr-coder20/FireScan)
**`[RED TEAM]` High-performance recon engine**
Go-powered probing with adaptive socket timing, concurrent worker pools and structured JSON output at minimal memory cost.

`Go` `Concurrency` `Networking CLI`

</td>
<td width="50%" valign="top">

### 🔬 [PCAP Analyzer](https://github.com/mr-coder20/pcap-analyzer)
**`[BLUE TEAM]` Network forensics & packet analysis**
Parses PCAP captures to surface suspicious flows, protocol anomalies and IOCs, turning raw traffic into a clear, investigation-ready summary.

`PCAP` `Network Forensics` `Wireshark` `Traffic Analysis`

</td>
</tr>
</table>

> 📱 **15+ open-source projects** · Android apps live on **Cafe Bazaar & Myket** with thousands of real installs · Python tools for crypto, hashing and data processing.

---

## 📜 Mission Log

| Year | Operation | Role & Findings |
|:--|:--|:--|
| 2025 | **Faragold** | Android dev + security collaborator — WordPress / WebView security review, config issue reports |
| 2024 | **Rayan Pardaz** | Real-time location tracking app, Foreground Services, battery-optimised pipeline |
| 2024 | **Fresh Sizan** | Network security assessment — Nmap, Windows service review, remediation report |
| 2023 | **Snapp** 🚕 | **Mobile security research** — login flow, API traffic, JWT & token storage, auth weaknesses, technical reports |
| 2021–22 | **Delijap** | Mobile API assessment with Frida + Python — access-control & validation flaws |
| 2021 | **Saina Co.** | Windows Server, ESXi, MikroTik firewall/NAT/queues, Cisco VLAN segmentation, traffic monitoring |

---

## 🎓 Training & Courses

`Android Security & Bug Bounty` · `Web Security & Bug Bounty` · `Security+` · `Network+` · `A+` · `MTCNA` · `CCNA` · `MCSA` · `LPIC-1` · `VMware Virtualization` · `Android App Development`

---

## 📺 YouTube Broadcast

```text
┌─────────────────────────────────────────────────────────────────────┐
│  🔴 TECHNICAL TRANSMISSIONS                                         │
│  ◈ SOC OPS        SIEM, triage and incident response walkthroughs   │
│  ◈ MOBILE APPSEC  Frida hooking · JWT attacks · SSL pinning bypass  │
│  ◈ BUG BOUNTY     Recon workflows · report writing                  │
│  ◈ THREAT INTEL   IOC triage automation, privacy-first analysis     │
│  ◈ SYSTEMS ENG    Kotlin KMP internals · Go concurrency             │
└─────────────────────────────────────────────────────────────────────┘
```

<div align="center">

**[📺 WATCH ON YOUTUBE](https://youtube.com)**

</div>

---

## 📊 Live Telemetry

<div align="center">

<img src="https://github-readme-stats-fast.vercel.app/api?username=mr-coder20&show_icons=true&theme=radical&hide_border=true&bg_color=0a0e17&title_color=00FF9D&icon_color=00F0FF&text_color=94A3B8&count_private=true" width="49%" alt="stats"/>
<img src="https://github-readme-stats-fast.vercel.app/api/top-langs?username=mr-coder20&layout=compact&theme=radical&hide_border=true&bg_color=0a0e17&title_color=00F0FF&text_color=94A3B8" width="49%" alt="langs"/>

<br/>

<img src="https://streak-stats.demolab.com?user=mr-coder20&theme=dark&background=0a0e17&border=1e293b&fire=00FF9D&ring=00F0FF&currStreakNum=00FF9D&sideNums=00F0FF&sideLabels=94A3B8&dates=475569" width="70%" alt="streak"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=mr-coder20&theme=radical&no-frame=true&no-bg=true&row=1&column=7&margin-w=8" width="98%" alt="trophies"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mr-coder20&bg_color=0a0e17&color=00FF9D&line=00F0FF&point=A855F7&area=true&area_color=00F0FF&hide_border=true" width="98%" alt="activity"/>

</div>

## 🐍 Contribution Snake

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mr-coder20/mr-coder20/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mr-coder20/mr-coder20/output/github-snake.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/mr-coder20/mr-coder20/output/github-snake-dark.svg" width="100%" />
</picture>
</div>

---

<details>
<summary><b>▶ DECRYPT — HACKER'S CODE</b></summary>
<br/>

```text
01. Scope first, exploit second. Authorized targets only.
02. Never trust the client. Validate everything server-side.
03. Tokens are secrets: store, rotate, revoke.
04. Detect fast, contain faster, document everything.
05. Privacy by design: collect nothing you don't need.
06. A finding without a clear fix is only half a report.
07. Responsible disclosure. Always.
```

</details>

<details>
<summary><b>🇮🇷 فارسی — درباره من</b></summary>

<div dir="rtl" align="right">

<br/>

من **امیرحسین غفاری** هستم؛ تحلیلگر **SOC**، **تستر نفوذ** و **باگ‌بانتی‌هانتر** با تمرکز ویژه روی **امنیت اپلیکیشن‌های موبایل**.

- 🔵 **بلو تیم (SOC):** تحلیل لاگ و SIEM، تریاژ هشدارها، غنی‌سازی IOC، پاسخ به حادثه و شکار تهدید
- 🔴 **رد تیم:** تست نفوذ شبکه، وب، API و اندروید با Frida، Burp Suite، Nmap
- 🟣 **پرپل تیم:** شبیه‌سازی حمله، بررسی اینکه SOC آن را می‌بیند یا نه، و بستن شکاف‌های تشخیص
- 🏆 **بانتی:** ریکان، پیدا کردن ضعف‌های احراز هویت و کنترل دسترسی (JWT، IDOR) و نوشتن گزارش حرفه‌ای
- 🤝 تجربه‌ی همکاری در حوزه‌ی امنیت موبایل با **اسنپ**
- 📫 [تلگرام](https://t.me/a_god_3_6_9) · [پورتفولیو](https://mr-coder20.github.io/my-portfolio/)

</div>

</details>

<div align="center">

<br/>

```text
[✓] ALL SYSTEMS NOMINAL    [✓] ZERO-TRUST ENFORCED    [✓] STAY CURIOUS, STAY ETHICAL
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FF9D,50:00F0FF,100:0a0e17&height=110&section=footer" width="100%" alt="footer"/>

</div>
