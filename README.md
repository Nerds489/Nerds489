<!-- ═══════════════════════════════ HEADER: follows the viewer's light or dark theme ═══════════════════════════════ -->
<a name="top"></a>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:3a0ca3,75:7209b7,100:00f5d4&height=240&section=header&text=NERDS489&fontSize=86&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=offensive%20security%20%E2%80%A2%20automation%20%E2%80%A2%20linux&descSize=20&descAlignY=60&descAlign=50">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:f8f9fa,45:b5179e,75:7209b7,100:3a0ca3&height=240&section=header&text=NERDS489&fontSize=86&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=offensive%20security%20%E2%80%A2%20automation%20%E2%80%A2%20linux&descSize=20&descAlignY=60&descAlign=50">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:3a0ca3,75:7209b7,100:00f5d4&height=240&section=header&text=NERDS489&fontSize=86&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=offensive%20security%20%E2%80%A2%20automation%20%E2%80%A2%20linux&descSize=20&descAlignY=60&descAlign=50" alt="NERDS489" width="100%">
</picture>

<p align="center">
  <a href="https://github.com/Nerds489">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=00F5D4&center=true&vCenter=true&multiline=false&width=760&height=48&lines=%3E+whoami;Builder+of+tools+that+run+themselves.;Red+team+tooling%2C+behind+a+scope+gate.;Windows%2C+debloated+and+tuned.;Linux+by+default.+Terminal+always+open.;%3E+exit+0" alt="typing intro"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Nerds489&label=PROFILE%20VIEWS&color=7209b7&style=for-the-badge" alt="profile views"/>
  <a href="https://github.com/Nerds489?tab=followers"><img src="https://img.shields.io/github/followers/Nerds489?label=FOLLOWERS&style=for-the-badge&color=3a0ca3&labelColor=0d1117" alt="followers"/></a>
  <img src="https://img.shields.io/badge/STATUS-BUILDING-00f5d4?style=for-the-badge&labelColor=0d1117" alt="status building"/>
</p>

<p align="center">
  <a href="#about"><kbd> 👤 about </kbd></a>&nbsp;
  <a href="#projects"><kbd> ⚔️ projects </kbd></a>&nbsp;
  <a href="#releases"><kbd> 🚀 releases </kbd></a>&nbsp;
  <a href="#arsenal"><kbd> 🧰 arsenal </kbd></a>&nbsp;
  <a href="#stats"><kbd> 📈 stats </kbd></a>&nbsp;
  <a href="#support"><kbd> 💜 support </kbd></a>&nbsp;
  <a href="#rules"><kbd> 📜 rules </kbd></a>
</p>

---

<a name="about"></a>
## :bust_in_silhouette: `$ cat about.md`

```yaml
handle:      Nerds489
builds:      tools that plan, run and log themselves
main_lane:   offensive security, for authorised engagements only
side_lanes:  Windows automation · Linux · self-hosting · multi-agent tooling
stack:       Python · PowerShell · Bash
believes_in: scope gates, audit trails, and fixing it properly the first time
off_hours:   writing bars when the terminal goes quiet
```

> [!NOTE]
> Everything public here is free to use. The security tooling is built for **authorised testing only**[^scope].

---

<a name="projects"></a>
## :crossed_swords: `$ ls ./projects --featured`

<p align="center">
  <a href="https://github.com/Nerds489/NETREAPER">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Nerds489&repo=NETREAPER&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f5d4&icon_color=7209b7&text_color=c9d1d9" alt="NETREAPER"/>
  </a>
  <a href="https://github.com/Nerds489/unified-windows-suite">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Nerds489&repo=unified-windows-suite&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f5d4&icon_color=7209b7&text_color=c9d1d9" alt="unified-windows-suite"/>
  </a>
</p>

<table>
<tr>
<td width="50%" valign="top">

### ⚔️ [NETREAPER](https://github.com/Nerds489/NETREAPER)

Name a goal and an interface; it works out which tools are needed, puts them in order, and runs them behind a **scope gate** with a **hash-chained audit trail**.

- **102** tools across **9** categories
- **16** native adapters
- a full **Textual TUI**
- Python 3.11+ · Linux · GPL-3.0

</td>
<td width="50%" valign="top">

### 🪟 [unified-windows-suite](https://github.com/Nerds489/unified-windows-suite)

Two Windows toolkits merged into one: tweaks, debloat, app installs, hardware profiling, drivers and performance tuning for **Windows 10 and 11**.

- per-feature <ins>undo</ins> and structured backups
- winget · Chocolatey · Scoop
- hardware info and drivers
- PowerShell · MIT · no activation tooling

</td>
</tr>
</table>

<details>
<summary><b>⚔️ NETREAPER, opened up</b></summary>
<br>

| | |
|---|---|
| **What you give it** | a goal and an interface |
| **What it works out** | which tools the job needs, and the order to run them in |
| **What stops it** | a scope gate: nothing runs against a target outside the engagement |
| **What it leaves behind** | a hash-chained audit trail, so the record can't be quietly edited |
| **How you drive it** | a Textual TUI, or the command line |

> [!TIP]
> Start with the README's quick start, define your scope, then let it plan the run.

</details>

<details>
<summary><b>🪟 unified-windows-suite, opened up</b></summary>
<br>

Neither parent project covered the whole job: one only ever *removed* things, the other could install and tune but had no undo that worked. Merged, they take a machine from first boot to tuned.

| Stage | What happens |
|---|---|
| **Strip** | debloat, telemetry off, app removal |
| **Install** | your apps, through winget, Chocolatey or Scoop |
| **Profile** | hardware read, drivers matched |
| **Tune** | performance tweaks, each one undoable |

> [!IMPORTANT]
> Try before you commit: every tweak path honours `-WhatIf`, and `.\Unified.ps1 scan` is read-only.

</details>

---

<a name="releases"></a>
## :rocket: `$ git tag --list --sort=-creatordate`

- [x] **NETREAPER v12.2.1**, 1 Oct 2026
- [x] **NETREAPER v12.0.2**, 22 Sep 2026
- [x] **NETREAPER v12.0.0**, 22 Sep 2026
- [x] **unified-windows-suite v4.0.0**, 19 Sep 2026
- [x] **NETREAPER v11.0.0**, the Python rebuild, 11 Sep 2026

---

<a name="arsenal"></a>
## :toolbox: `$ which --all arsenal`

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,powershell,bash,linux,ubuntu,windows,git,github,githubactions,docker,vscode,vim&perline=12&theme=dark" alt="tech stack"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Linux_Mint-0d1117?style=for-the-badge&logo=linuxmint&logoColor=00f5d4" alt="Linux Mint"/>
  <img src="https://img.shields.io/badge/Textual_TUI-0d1117?style=for-the-badge&logo=python&logoColor=00f5d4" alt="Textual"/>
  <img src="https://img.shields.io/badge/Self--hosted-0d1117?style=for-the-badge&logo=homeassistant&logoColor=00f5d4" alt="Self-hosted"/>
  <img src="https://img.shields.io/badge/Jellyfin-0d1117?style=for-the-badge&logo=jellyfin&logoColor=00f5d4" alt="Jellyfin"/>
</p>

---

<a name="stats"></a>
## :chart_with_upwards_trend: `$ git log --stat --all`

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Nerds489&show_icons=true&hide=stars&count_private=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f5d4&icon_color=7209b7&text_color=c9d1d9&rank_icon=github" alt="GitHub stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nerds489&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00f5d4&text_color=c9d1d9" alt="top languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Nerds489&theme=tokyonight&hide_border=true&background=0d1117&ring=7209b7&fire=00f5d4&currStreakLabel=00f5d4&sideLabels=c9d1d9&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff" alt="contribution streak"/>
</p>

<p align="center">
  <img src="https://ghchart.rshah.org/7209b7/Nerds489" alt="contribution chart" width="100%"/>
</p>

---

<a name="support"></a>
## :purple_heart: `$ ./support.sh`

<p align="center">
  <a href="https://github.com/sponsors/Nerds489"><img src="https://img.shields.io/badge/GitHub_Sponsors-0d1117?style=for-the-badge&logo=githubsponsors&logoColor=ea4aaa" alt="GitHub Sponsors"/></a>
  <a href="https://liberapay.com/Nerds489"><img src="https://img.shields.io/badge/Liberapay-0d1117?style=for-the-badge&logo=liberapay&logoColor=f6c915" alt="Liberapay"/></a>
  <a href="https://buymeacoffee.com/abbeyandlaf"><img src="https://img.shields.io/badge/Buy_Me_a_Coffee-0d1117?style=for-the-badge&logo=buymeacoffee&logoColor=ffdd00" alt="Buy Me a Coffee"/></a>
</p>

<p align="center"><sub>Everything here is built in spare hours. If a tool saved you one, that's how to say so.</sub></p>

---

<a name="rules"></a>
## :scroll: `$ cat ./rules.txt`

```text
01  scope first. nothing runs that wasn't authorised.
02  log everything. if it isn't in the audit trail, it didn't happen.
03  measure, don't guess. the number wins the argument.
04  fix the cause, not the symptom.
05  ship it working, or don't ship it.
```

> [!WARNING]
> ~~move fast and break things~~ &nbsp;move deliberately and leave a log.

> [!CAUTION]
> Pointing offensive tooling at systems you don't own or aren't authorised to test is illegal almost everywhere. Get it in writing first.

---

<p align="center">
  <a href="https://github.com/Nerds489?tab=repositories"><img src="https://img.shields.io/badge/SEE_ALL_REPOS-0d1117?style=for-the-badge&logo=github&logoColor=00f5d4" alt="repositories"/></a>
  <a href="#top"><img src="https://img.shields.io/badge/BACK_TO_TOP-0d1117?style=for-the-badge&logo=githubactions&logoColor=7209b7" alt="back to top"/></a>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:00f5d4,25:7209b7,55:3a0ca3,100:0d1117&height=130&section=footer">
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:3a0ca3,45:7209b7,100:b5179e&height=130&section=footer">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00f5d4,25:7209b7,55:3a0ca3,100:0d1117&height=130&section=footer" alt="footer" width="100%">
</picture>

<p align="center"><sub>Text on this page © 2026 Nerds489, shared under <a href="LICENSE">CC BY 4.0</a>.<sup>v2</sup></sub></p>

[^scope]: Authorised means written permission from whoever owns the system, with the targets and the time window agreed before anything runs. NETREAPER enforces that scope; it can't create the permission for you.
