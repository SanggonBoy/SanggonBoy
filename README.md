<!--
  ███████╗ █████╗ ███╗   ██╗ ██████╗  ██████╗  ██████╗ ███╗   ██╗██████╗  ██████╗ ██╗   ██╗
  ██╔════╝██╔══██╗████╗  ██║██╔════╝ ██╔═══██╗██╔═══██╗████╗  ██║██╔══██╗██╔═══██╗╚██╗ ██╔╝
  ███████╗███████║██╔██╗ ██║██║  ███╗██║   ██║██║   ██║██╔██╗ ██║██████╔╝██║   ██║ ╚████╔╝
  ╚════██║██╔══██║██║╚██╗██║██║   ██║██║   ██║██║   ██║██║╚██╗██║██╔══██╗██║   ██║  ╚██╔╝
  ███████║██║  ██║██║ ╚████║╚██████╔╝╚██████╔╝╚██████╔╝██║ ╚████║██████╔╝╚██████╔╝   ██║
  ╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝  ╚═════╝  ╚═════╝ ╚═╝  ╚═══╝╚═════╝  ╚═════╝    ╚═╝
                             $ whoami  → alexander_jay@github
                             $ cat /etc/profile | tail -1  → "ship code, not slides."
-->

<div align="center">

```ascii
┌──────────────────────────────────────────────────────────────┐
│  $ nmap -sV github.com:SanggonBoy                           │
│  PORT   STATE  SERVICE      VERSION                           │
│  22/tcp open   ssh          OpenSSH 9.x                       │
│  80/tcp open   http         nginx/1.27 (README.md)            │
│  443/tcp open https         TLSv1.3                           │
└──────────────────────────────────────────────────────────────┘
```

</div>

---

## `$ whoami`

> **Alexander Jay** — *Full-Stack Developer* who builds at the intersection of **AI tooling**, **MCP servers**, and **modern web stacks**.
>
> I like things that compile, run, and don't lie about what they do.

```
$ cat /etc/profile.d/kingjay.sh
ROLE=full-stack
STACK=python, typescript, javascript, php, go
FOCUS=ai-agents · mcp · scraping · web-apps
OS=windows + wsl2
```

---

## `~/arsenal`

<table>
<tr>
<td valign="top" width="50%">

**Languages**
<br/>
<img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white" />
<img src="https://img.shields.io/badge/Blade-FF2D20?logo=laravel&logoColor=white" />

**Frameworks & Runtimes**
<br/>
<img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white" />

</td>
<td valign="top" width="50%">

**AI / Tooling**
<br/>
<img src="https://img.shields.io/badge/MCP-000000?logo=modelcontextprotocol&logoColor=white" />
<img src="https://img.shields.io/badge/Pydantic-E92063?logo=pydantic&logoColor=white" />
<img src="https://img.shields.io/badge/scrapling-FF6B35" />
<img src="https://img.shields.io/badge/crawl4ai-0096FF" />
<img src="https://img.shields.io/badge/Hermes_Agent-7C3AED" />

**Infra**
<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-DC244C" />
<img src="https://img.shields.io/badge/FlyEnv-0EA5E9" />
<img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white" />

</td>
</tr>
</table>

---

## `$ ls -la ~/projects`

<div align="center">

<!-- PyreCrawl feature card -->
<table>
<tr>
<td align="center" valign="middle" width="160">

```
╔══════════════╗
║   ▓▓▓▓▓▓▓▓   ║
║   ▓ PYRE ▓   ║
║   ▓▓▓▓▓▓▓▓   ║
╚══════════════╝
```
🔥 v0.2.2 on PyPI

</td>
<td align="left" valign="middle">

### 🔥 [PyreCrawl](https://github.com/SanggonBoy/PyreCrawl) — *Web browsing superpowers for AI agents*

One MCP tool to **scrape, extract, crawl, map, and search** any site — self-hosted, no API keys, with a smart auto-fallback ladder (`crawl4ai` → `scrapling` → `playwright`).

- 🧠 Built for **LLM agents** — structured JSON out, markdown in
- 🔌 Plugs into **Claude Desktop, Hermes, MCP Inspector** out of the box
- 🪜 **Auto-fallback ladder** when one scraper gets blocked
- 📦 `pip install pyrecrawl` — MIT licensed

<br/>

```bash
$ pip install pyrecrawl[all]
$ pyrecrawl --target https://example.com --mode scrape
```

</td>
</tr>
</table>

</div>

---

## `~/.profile.d/`

```bash
# Current interests
INTERESTS=(
  "ai-agents"
  "mcp-protocol"
  "web-scraping"
  "developer-experience"
  "indie-saas"
)

# Active focus
CURRENT_FOCUS=(
  "shipping PyreCrawl v0.3+"
  "MCP server ecosystem"
  "modern web tooling"
)
```

---

## 📊 `netstat -an | grep stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SanggonBoy&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=false&rank_icon=github" height="170" alt="GitHub stats" />
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SanggonBoy&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="170" alt="Top languages" />

<br/>

<img src="https://streak-stats.demolab.com?user=SanggonBoy&theme=tokyonight&hide_border=true" height="170" alt="Streak stats" />

</div>

---

## `cat /etc/contact`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/SanggonBoy)
[![PyPI](https://img.shields.io/badge/PyPI-3776AB?logo=pypi&logoColor=white)](https://pypi.org/project/PyreCrawl/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white)](https://portfolio-fajar-tria-nugraha.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:118122698+SanggonBoy@users.noreply.github.com)

</div>

---

<div align="center">

```bash
$ uptime --pretty
up 24/7 · shipping > talking
```

</div>
