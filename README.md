<div align="center">

<a href="https://bakasura.im"><img src="assets/banner.svg" width="780" alt="bakasura — reverse engineer / programmer. root@bakasura:~$ cat name.txt" /></a>

<p><strong>Reverse Engineer / Programmer</strong><br />
<em>Everything else is a target.</em></p>

<p>
<a href="https://bakasura.im"><img src="https://img.shields.io/badge/bakasura.im-050505?style=for-the-badge&amp;logo=firefox&amp;logoColor=00FF41" alt="Website" /></a>
<a href="https://github.com/BakasuraRCE"><img src="https://img.shields.io/badge/GitHub-BakasuraRCE-050505?style=for-the-badge&amp;logo=github&amp;logoColor=00FF41" alt="GitHub" /></a>
<a href="https://x.com/BakasuraRCE"><img src="https://img.shields.io/badge/X-@BakasuraRCE-050505?style=for-the-badge&amp;logo=x&amp;logoColor=00FF41" alt="X" /></a>
<a href="mailto:contact@bakasura.im"><img src="https://img.shields.io/badge/contact@bakasura.im-050505?style=for-the-badge&amp;logo=protonmail&amp;logoColor=00FF41" alt="Email" /></a>
</p>

</div>

## // ABOUT

I take binaries apart and build the tools that put them back together. Mostly Windows PE and game-console
formats, mostly in Python, C and C++ — plus a long-running affair with Delphi, phpBB and self-hosted
infrastructure. I also built and currently maintain **[crackslatinos.org](https://crackslatinos.org)**,
the website that publishes the work of the Spanish-speaking **CrackSLatinoS** group.

- **Reversing** — unpacking, PE internals, static & dynamic analysis, patch tooling
- **Scene work** — preservation tooling for Xbox 360, Usenet and IRC
- **Building** — Python / C / C++ / PHP / Delphi, from CLI utilities to Dockerized services
- **Open to** — collaboration on RE tooling, scene preservation and network protocol work

<div align="center">

<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=python&amp;sort="><img src="https://img.shields.io/badge/Python-050505?style=flat-square&amp;logo=python&amp;logoColor=00FF41" alt="Python" /></a>
<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=c&amp;sort="><img src="https://img.shields.io/badge/C-050505?style=flat-square&amp;logo=c&amp;logoColor=00FF41" alt="C" /></a>
<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=c%2B%2B&amp;sort="><img src="https://img.shields.io/badge/C++-050505?style=flat-square&amp;logo=cplusplus&amp;logoColor=00FF41" alt="C++" /></a>
<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=php&amp;sort="><img src="https://img.shields.io/badge/PHP-050505?style=flat-square&amp;logo=php&amp;logoColor=00FF41" alt="PHP" /></a>
<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=pascal&amp;sort="><img src="https://img.shields.io/badge/Delphi-050505?style=flat-square&amp;logo=delphi&amp;logoColor=00FF41" alt="Delphi" /></a>
<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=c%2B%2B&amp;sort="><img src="https://img.shields.io/badge/Qt-050505?style=flat-square&amp;logo=qt&amp;logoColor=00FF41" alt="Qt" /></a>
<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=dockerfile&amp;sort="><img src="https://img.shields.io/badge/Docker-050505?style=flat-square&amp;logo=docker&amp;logoColor=00FF41" alt="Docker" /></a>
<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=&amp;sort="><img src="https://img.shields.io/badge/Linux-050505?style=flat-square&amp;logo=linux&amp;logoColor=00FF41" alt="Linux" /></a>
<a href="https://github.com/BakasuraRCE?tab=repositories&amp;q=&amp;type=&amp;language=&amp;sort="><img src="https://img.shields.io/badge/Git-050505?style=flat-square&amp;logo=git&amp;logoColor=00FF41" alt="Git" /></a>

</div>

---

## // SELECTED WORK

### REVERSING & COMMUNITY

| Project | What it does | Stack |
| --- | --- | --- |
| **[UNdUP2](https://github.com/BakasuraRCE/UNdUP2)** | Unpacker and decompiler for the dUP2 patcher: pulls the encrypted DLL out of PE `RCDATA` and decrypts it with a rotative XOR keyed by `0xDEADBEEF`. | `Python` `PE` `XOR` |
| **[crackslatinos.org](https://crackslatinos.org)** | Site I created and currently maintain for the CrackSLatinoS group: courses, tutorials and shared practice of the craft in Spanish. Non-commercial, community around since 2000. | `Web` `Community` `RE` |

### SCENE & PRESERVATION

| Project | What it does | Stack |
| --- | --- | --- |
| **[abgx360 Reloaded](https://abgx360.bakasura.im)** | Hard fork of Seacrest's abgx360. Verifies the integrity of Xbox 360 game backups; HTTPS and Hadzz DB integration in progress. | `C` `Xbox 360` |
| **[steamworks-tracker](https://steamworks.scene.re)** | Indexes every Steamworks SDK release from 1.00 onwards, with SHA-1 and MD5 hashes per binary for verification. | `JSON` `Steam` |
| **[ngPostEx](https://github.com/BakasuraRCE/ngPostEx)** | Fork of ngPost — Usenet binary poster with full article obfuscation, PAR2, folder monitoring and a more reliable `--check`. | `C++` `Qt` |
| **[znc-fishlim-reloaded](https://github.com/BakasuraRCE/znc-fishlim-reloaded)** | FiSHLiM IRC encryption for the ZNC bouncer: CBC and ECB modes, DH1080 key exchange, per-message state indicators. | `Python` `Crypto` |

### INFRASTRUCTURE & WEB

| Project | What it does | Stack |
| --- | --- | --- |
| **[spotweb-docker](https://github.com/BakasuraRCE/spotweb-docker)** | Rootless Spotweb container on OpenLiteSpeed + PHP 8.2, with automatic database schema migration at startup. | `Docker` `PHP` |
| **[phpbb-image-compressor](https://github.com/BakasuraRCE/phpbb-ext-image-compressor)** | Hooks the phpBB upload event and runs PNG attachments through pngquant transparently, updating stored size metadata. | `PHP` `phpBB` |
| **[phpbb-xforwardedfor](https://github.com/BakasuraRCE/phpbb-ext-xforwardedfor)** | Real client IP logging behind reverse proxies — Cloudflare `CF-Connecting-IP` and `X-Forwarded-For` per RFC 7239. | `PHP` `phpBB` |

### DEMOSCENE & DELPHI

| Project | What it does | Stack |
| --- | --- | --- |
| **[pyansilove](https://github.com/BakasuraRCE/pyansilove)** | Python port of libansilove: renders ANSi and ASCII art (ANSI X3.64) to PNG. | `Python` `ANSI` |
| **[TSizeCtrl](https://github.com/BakasuraRCE/TSizeCtrl)** | Non-visual VCL component for runtime move and resize of controls. Fork of Angus Johnson's original. | `Delphi` `VCL` |
| **[LTWaterEffect](https://github.com/BakasuraRCE/LTWaterEffect)** | Water simulation component with 32-bit canvas rendering, ripple physics and StartRain / StopRain control. | `Delphi` `VCL` |
| **[TEditableListView](https://github.com/BakasuraRCE/TEditableListView)** | Extends `TListView` with in-place field editing for Delphi applications. | `Delphi` `VCL` |

<details>
<summary><b>// UPSTREAM & ARCHIVED</b></summary>

| Project | What it does | Stack |
| --- | --- | --- |
| **[hexchat / fishlim #2347](https://github.com/hexchat/hexchat/pull/2347)** | Added CBC mode and extended commands to HexChat's native FiSHLiM plugin. Merged upstream in October 2020; repository archived in 2024. | `C` `IRC` `Crypto` |

</details>

---

## // TELEMETRY

<div align="center">

<img height="160" src="https://github-stats-extended.vercel.app/api?username=BakasuraRCE&amp;show_icons=true&amp;hide_rank=true&amp;include_all_commits=true&amp;count_private=true&amp;bg_color=050505&amp;title_color=00FF41&amp;icon_color=00FF41&amp;text_color=C8FFC8&amp;border_color=2A4A2A" alt="GitHub stats" />
<img height="160" src="https://github-stats-extended.vercel.app/api/top-langs/?username=BakasuraRCE&amp;layout=compact&amp;langs_count=8&amp;bg_color=050505&amp;title_color=00FF41&amp;text_color=C8FFC8&amp;border_color=2A4A2A" alt="Top languages" />

</div>

---

## // OPEN PORTS

<div align="center">

<a href="https://github.com/BakasuraRCE"><img src="https://img.shields.io/badge/github-/BakasuraRCE-050505?style=for-the-badge&amp;logo=github&amp;logoColor=00FF41" alt="GitHub" /></a>
<a href="https://x.com/BakasuraRCE"><img src="https://img.shields.io/badge/x-@BakasuraRCE-050505?style=for-the-badge&amp;logo=x&amp;logoColor=00FF41" alt="X" /></a>
<a href="https://discord.com/users/bakasurarce"><img src="https://img.shields.io/badge/discord-bakasurarce-050505?style=for-the-badge&amp;logo=discord&amp;logoColor=00FF41" alt="Discord" /></a>
<a href="mailto:contact@bakasura.im"><img src="https://img.shields.io/badge/mail-contact@bakasura.im-050505?style=for-the-badge&amp;logo=protonmail&amp;logoColor=00FF41" alt="Email" /></a>

</div>

```text
; built with: markdown + a terminal addiction
; -- EOF --
```
