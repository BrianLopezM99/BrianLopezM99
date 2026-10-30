<div align="center">

<img src="assets/header.svg" width="100%" alt="Brian López Medina — Pentester, Red Teamer, Reverse Engineer and AI Engineer" />

<br />

<a href="https://www.linkedin.com/in/brian-lm/"><img src="https://img.shields.io/badge/LinkedIn-in%2Fbrian--lm-0A66C2?style=for-the-badge&labelColor=0D1420" alt="LinkedIn" /></a>
<a href="https://brianmedinadev.netlify.app/"><img src="https://img.shields.io/badge/Website_%26_CV-brianmedinadev-22D3EE?style=for-the-badge&logo=netlify&logoColor=white&labelColor=0D1420" alt="Website & CV" /></a>
<img src="https://img.shields.io/badge/Hack_The_Box-BrianM-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=9FEF00&labelColor=0D1420" alt="Hack The Box: BrianM" />
<img src="https://komarev.com/ghpvc/?username=BrianLopezM99&label=profile%20views&color=9FEF00&style=for-the-badge&labelColor=0D1420" alt="Profile views" />

</div>

<br />

## `$ cat about.py`

```python
class BrianLopez:
    roles     = ["Pentester", "Red Teamer", "Reverse Engineer",
                 "AI Engineer", "Software Engineer"]
    location  = "Durango, Mexico 🇲🇽"
    offensive = ["Malware development", "AV evasion", "Process injection",
                 "DLL hijacking", "Reverse engineering (Ghidra)",
                 "Full attack chains"]
    lab       = "Home lab where I build and run complete attacks, end to end"
    studying  = "OSCP — Offensive Security Certified Professional"
    certs     = ["eJPT — eLearnSecurity Junior Penetration Tester"]
    htb       = {"user": "BrianM", "rank": "Hacker", "next": "Pro Hacker"}
    building  = "AI-powered products and agents"
    writes_on = "linkedin.com/in/brian-lm"

    def motto(self):
        return "Build it. Break it. Make it smarter."
```

## `$ ./certs --verify`

<p>
  <a href="https://certs.ine.com/d780244c-b95e-401f-8795-14d4d44f7355#acc.bmktZQau"><img src="https://img.shields.io/badge/eJPT-Passed-9FEF00?style=for-the-badge&logo=securityscorecard&logoColor=9FEF00&labelColor=0D1420" alt="eJPT: passed" /></a>
  <img src="https://img.shields.io/badge/OSCP-In_progress-22D3EE?style=for-the-badge&logo=kalilinux&logoColor=22D3EE&labelColor=0D1420" alt="OSCP: in progress" />
  <img src="https://img.shields.io/badge/HTB_Rank-Hacker_→_Pro_Hacker-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=9FEF00&labelColor=0D1420" alt="Hack The Box rank: Hacker, road to Pro Hacker" />
</p>

## `$ ./lab --run killchain`

<img src="assets/killchain.svg" width="100%" alt="Home lab attack chain: recon, access, payload, evasion, injection, hijack, SYSTEM" />

I build complete attacks in my home lab, from the first scan to full control of the target, and take binaries apart to understand how they really work.

| Phase | What I do in the lab | MITRE ATT&CK |
| --- | --- | --- |
| 🔍 **Recon** | OSINT, network and service enumeration | [T1595](https://attack.mitre.org/techniques/T1595/) · [T1593](https://attack.mitre.org/techniques/T1593/) |
| 🚪 **Initial access** | Web exploitation (CVE-2025-55182) and HID keystroke-injection attacks with a Raspberry Pi Zero | [T1190](https://attack.mitre.org/techniques/T1190/) · [T1200](https://attack.mitre.org/techniques/T1200/) |
| 🧪 **Weaponization** | Custom, controlled malware written from scratch | [T1587.001](https://attack.mitre.org/techniques/T1587/001/) |
| 🥷 **Defense evasion** | Antivirus evasion and payload obfuscation | [T1027](https://attack.mitre.org/techniques/T1027/) |
| 💉 **Process injection** | Running code inside other processes | [T1055](https://attack.mitre.org/techniques/T1055/) |
| 🪝 **DLL hijacking** | Hijacking execution flow through DLL loading | [T1574.001](https://attack.mitre.org/techniques/T1574/001/) |
| 🔬 **Reverse engineering** | Static analysis and decompilation of binaries with Ghidra | — |

> [!NOTE]
> Everything offensive here lives in my own isolated lab: my machines, my VMs, my targets. It's research to learn how real attacks work and how to defend against them.

## `$ ls ~/arsenal --featured`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/BrianLopezM99/react2shell-CVE-2025-55182">🧨 react2shell · CVE-2025-55182</a></h3>
      Exploitation tool for the Next.js vulnerability that allows remote command execution through prototype poisoning in React Server Components.
      <br /><br />
      <img src="https://img.shields.io/badge/Python-0D1420?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" />
      <img src="https://img.shields.io/badge/RCE_Exploit-0D1420?style=flat-square&logo=hackthebox&logoColor=9FEF00" alt="RCE exploit" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/BrianLopezM99/raspberry-zero-HID-Keyboard-Emulation-Attack">⌨️ Pi Zero HID Attack</a></h3>
      A Raspberry Pi Zero 2 W programmed to act as a keyboard and run attacks against Windows devices.
      <br /><br />
      <img src="https://img.shields.io/badge/Raspberry_Pi-0D1420?style=flat-square&logo=raspberrypi&logoColor=C51A4A" alt="Raspberry Pi" />
      <img src="https://img.shields.io/badge/Hardware_Hacking-0D1420?style=flat-square&logo=hackthebox&logoColor=9FEF00" alt="Hardware hacking" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/BrianLopezM99/instagram-scrapper-and-recon">🕵️ Instagram Scraper & Recon</a></h3>
      OSINT toolkit for scraping and recon of public Instagram profiles.
      <br /><br />
      <img src="https://img.shields.io/badge/Python-0D1420?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" />
      <img src="https://img.shields.io/badge/OSINT-0D1420?style=flat-square&logo=searxng&logoColor=22D3EE" alt="OSINT" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/BrianLopezM99/flutter-google-vision">👁️ Flutter × Google Vision</a></h3>
      Computer vision in a Flutter app powered by the Google Cloud Vision API.
      <br /><br />
      <img src="https://img.shields.io/badge/Flutter-0D1420?style=flat-square&logo=flutter&logoColor=02569B" alt="Flutter" />
      <img src="https://img.shields.io/badge/Google_Cloud-0D1420?style=flat-square&logo=googlecloud&logoColor=4285F4" alt="Google Cloud" />
    </td>
  </tr>
</table>

## `$ which --all stack`

**Offensive Security & Reverse Engineering**

<img src="https://skillicons.dev/icons?i=kali,linux,windows,raspberrypi&perline=10" alt="Kali Linux, Linux, Windows, Raspberry Pi" />

<p>
  <img src="https://img.shields.io/badge/Ghidra-C8102E?style=for-the-badge" alt="Ghidra" />
  <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" alt="Burp Suite" />
  <img src="https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge&logo=gnubash&logoColor=white" alt="Nmap" />
  <img src="https://img.shields.io/badge/Hack_The_Box-111927?style=for-the-badge&logo=hackthebox&logoColor=9FEF00" alt="Hack The Box" />
  <img src="https://img.shields.io/badge/OSINT-111927?style=for-the-badge&logo=searxng&logoColor=22D3EE" alt="OSINT" />
</p>
<p>
  <img src="https://img.shields.io/badge/Malware_Dev-111927?style=for-the-badge" alt="Malware development" />
  <img src="https://img.shields.io/badge/AV_Evasion-111927?style=for-the-badge" alt="AV evasion" />
  <img src="https://img.shields.io/badge/Process_Injection-111927?style=for-the-badge" alt="Process injection" />
  <img src="https://img.shields.io/badge/DLL_Hijacking-111927?style=for-the-badge" alt="DLL hijacking" />
</p>

**Languages**

<img src="https://skillicons.dev/icons?i=python,bash,ts,js,dart,kotlin,php&perline=10" alt="Python, Bash, TypeScript, JavaScript, Dart, Kotlin, PHP" />

**Frameworks & Backend**

<img src="https://skillicons.dev/icons?i=flutter,react,nextjs,nodejs,flask,fastapi,laravel,supabase,mongodb,html,css,git&perline=12" alt="Flutter, React, Next.js, Node.js, Flask, FastAPI, Laravel, Supabase, MongoDB, HTML, CSS, Git" />

## `$ git log --stats`

<div align="center">

<img src="https://streak-stats.demolab.com?user=BrianLopezM99&background=0D1420&border=1F2A3A&stroke=1F2A3A&ring=9FEF00&fire=9FEF00&currStreakNum=E6EDF3&sideNums=22D3EE&currStreakLabel=9FEF00&sideLabels=E6EDF3&dates=8B949E&border_radius=14" width="100%" alt="GitHub streak stats" />

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/BrianLopezM99/BrianLopezM99/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/BrianLopezM99/BrianLopezM99/output/snake-light.svg" />
  <img src="https://raw.githubusercontent.com/BrianLopezM99/BrianLopezM99/output/snake-dark.svg" alt="Snake eating my contribution graph" />
</picture>

<br /><br />

<img src="assets/footer.svg" width="100%" alt="Build it. Break it. Make it smarter." />

</div>
