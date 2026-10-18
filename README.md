<div align="center">

<img src="assets/logos/fleet.png" width="88" height="88" alt="Nico Broß — Portfolio Logo" />

# Hi, ich bin Nico 👋

**Fachinformatiker für Anwendungsentwicklung · Backend, KI-/Audio-Pipelines, Full-Stack & Self-Hosted Infrastructure**

[![Standort](https://img.shields.io/badge/Standort-Raum_M%C3%BCnchen_%2F_Grafing-0A66C2?style=flat-square)](#)
[![Fokus](https://img.shields.io/badge/Fokus-Python_%C2%B7_TypeScript_%C2%B7_Java_%C2%B7_DevOps-2ea043?style=flat-square)](#)
[![Infrastruktur](https://img.shields.io/badge/Homelab-Multi--Host_Tailscale_Mesh-6e40c9?style=flat-square)](#)

</div>

---

### Über mich

Ich entwickle Software und Infrastruktur, die reale Alltags- und Geschäftsprobleme zuverlässig automatisiert — von **verteilten Audio- und KI-Pipelines** über **moderne Web- und Mobile-Apps** bis hin zu einer **deklarativ verwalteten Multi-Host-Serverlandschaft**.

- 🎓 **Ausbildung & Praxis:** Abgeschlossene Ausbildung zum **Fachinformatiker für Anwendungsentwicklung (IHK)** bei der *Zeppelin Baumaschinen GmbH* (Java/Spring-Boot-Backend, atomare Datenbanktransaktionen, automatisierte PDF-Beleggenerierung sowie Entwicklung eines Python/`pytest`-REST-API-Testframeworks mit **70 % Zeitersparnis** in der Jenkins-CI/CD-Pipeline).
- 🏗️ **System-Architektur im eigenen Lab:** Ich betreibe ein produktives Multi-Node-Setup (Linux-VPS, TrueNAS SCALE mit ZFS, dedizierte KI-Jails, Home Assistant OS & Apple-Silicon-Worker), vernetzt über ein Zero-Trust-Mesh (Tailscale) mit zentralem Monitoring, SSO und Secret-Management.
- 🔒 **Hinweis zu Repository-Sichtbarkeiten:** Da viele meiner produktiven Systeme direkt in meine eigene Infrastruktur oder kommunale Umgebungen eingebunden sind, sind die zugehörigen Repositories als `Private / Self-Hosted` gekennzeichnet. Öffentliche Projekte sind direkt verlinkt (`Open Source`) — **Architektur-Einblicke, Live-Demos und Code-Walkthroughs zeige ich jederzeit gerne im Gespräch!**

---

## 🚀 Projekt-Portfolio

### 🎙️ KI, Audio-Engineering & Developer Tools

<table>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/soundcore-export.png" width="68" height="68" alt="Keepsaid & Soundcore-Export Logo" />
    </td>
    <td valign="top">
      <b>Keepsaid &amp; Soundcore-Export</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Distributed_Pipeline-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Persönliches Audioarchiv &amp; verteilte Sprach-Pipeline:</b> Automatischer Cloud-Ingest mit lokaler <code>AES-256-GCM</code>-Entschlüsselung, mehrstufiger Rauschunterdrückung (RNNoise / FlowSE), GPU-beschleunigter Transkription via <code>mlx-whisper</code> auf Apple Silicon, Sprecher-Diarisierung (PyAnnote), kontextgestützter Stimmzuordnung und interaktivem Web-Review-UI zum wortweisen Mitlesen.<br/>
      <sub><code>Python</code> · <code>FastAPI</code> · <code>MLX-Whisper</code> · <code>PyAnnote</code> · <code>FFmpeg</code> · <code>Docker</code> · <code>Tailscale</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/speech-lab.png" width="68" height="68" alt="Speech Lab Logo" />
    </td>
    <td valign="top">
      <b>Speech Lab</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Evaluation_Suite-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Reproduzierbare Benchmark-Suite für deutsche Spracherkennung (ASR):</b> Lokales Evaluierungslabor zum systematischen Vergleich von lokalen und Cloud-Sprachmodellen, exakter Wortzeitmarken-Ausrichtung (Word-Boundary Timing) und Mehrsprecher-Erkennung gegen <code>SHA256</code>-verankerte Referenztranskripte.<br/>
      <sub><code>Python</code> · <code>ASR Benchmarking</code> · <code>Speaker Diarization</code> · <code>Web UI</code> · <code>pytest</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/fleet.png" width="68" height="68" alt="Fleet Logo" />
    </td>
    <td valign="top">
      <b>Fleet</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Infra_CLI-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Multi-Host-Orchestrierung &amp; Service-Health-Radar:</b> Zentrales CLI-Werkzeug (<code>fleet doctor</code>, <code>fleet sync</code>, <code>fleet portfolio</code>) zur Überwachung und Synchronisation von über 45 Repositories und Diensten über Linux-VPS, TrueNAS, Home Assistant und macOS hinweg — inklusive Zero-Secret-Architektur durch dynamische 1Password-Injektion (<code>op://</code>) zur Laufzeit.<br/>
      <sub><code>Python</code> · <code>Bash</code> · <code>1Password CLI</code> · <code>systemd</code> · <code>Tailscale</code> · <code>Git Worktrees</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/iris.png" width="68" height="68" alt="Iris Logo" />
    </td>
    <td valign="top">
      <b>Iris</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Agent_Daemon-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>„Die Botin für deine Agent-Skills“:</b> Plattformübergreifender Synchronisations-Daemon (macOS <code>launchd</code> &amp; Linux), der eigene KI-Workflows, Regeln und Skills deklarativ und konfliktfrei zwischen Claude Code, Codex, T3 Code, Cursor, Gemini CLI und Antigravity verteilt.<br/>
      <sub><code>Python</code> · <code>Shell</code> · <code>launchd</code> · <code>Developer Experience</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/token-maxing.png" width="68" height="68" alt="Token-Maxing Logo" />
    </td>
    <td valign="top">
      <b>Token-Maxing</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-AI_Gateway-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Multi-Account AI Gateway &amp; Telemetrie-Plattform:</b> Lokaler API-Router für OpenAI- und Anthropic-Workloads mit SSE-Streaming-Parser, automatischem OAuth-Token-Refresh, Rate-Limit-Failover, SQLite-Telemetrie und Next.js-Dashboard zur Echtzeit-Quota-Analyse.<br/>
      <sub><code>TypeScript</code> · <code>Fastify</code> · <code>Next.js</code> · <code>SQLite</code> · <code>SSE Streaming</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/cliproxyapi.png" width="68" height="68" alt="CLIProxyAPI Logo" />
    </td>
    <td valign="top">
      <b>CLIProxyAPI</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Go_Service-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Unified AI-Proxy-Server mit Web-Management-Konsole:</b> Hochperformanter Go-Service, der CLI-basierte KI-Zugänge unter standardisierten OpenAI-, Claude- und Gemini-kompatiblen REST-Endpunkten mit Multi-Account-Load-Balancing bereitstellt.<br/>
      <sub><code>Go</code> · <code>REST API</code> · <code>OAuth</code> · <code>Docker</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/ai-note-dock.png" width="68" height="68" alt="Ai-Note-Dock Logo" />
    </td>
    <td valign="top">
      <b>Ai-Note-Dock</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Hardware_Spec-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Embedded Bluetooth-Audiorekorder &amp; Smart-Dock:</b> Systemarchitektur für einen auf dem Raspberry Pi Zero 2 W basierenden Dual-Mode-Bluetooth-Rekorder (A2DP/HFP via BlueZ &amp; PipeWire) mit automatischem Upload und Lade-Management beim Eindocken.<br/>
      <sub><code>Embedded Linux</code> · <code>Raspberry Pi</code> · <code>BlueZ</code> · <code>PipeWire</code></sub>
    </td>
  </tr>
</table>

---

### 🌐 Full-Stack Web, Mobile & Workflow-Anwendungen

<table>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/orbit.png" width="68" height="68" alt="Orbit Mission Control Logo" />
    </td>
    <td valign="top">
      <b>Orbit // Mission Control</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Live_Dashboard-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Echtzeit-Service- &amp; Telemetrie-Dashboard:</b> Zentrale Start- und Monitoring-Plattform für alle Dienste im Homelab und Tailnet mit serverseitigen Live-Health-Pings, Latenzmessung, Host-Filterung und umschaltbarer Dual-Design-Engine (<i>Stark HUD</i> &amp; <i>Cupertino Glass</i>).<br/>
      <sub><code>Node.js</code> · <code>JavaScript</code> · <code>HTML5 / CSS3</code> · <code>REST API</code> · <code>systemd</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/chaxterlog.png" width="68" height="68" alt="ChaxterLog Logo" />
    </td>
    <td valign="top">
      <b>ChaxterLog</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Production_App-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Besucher-Analytics &amp; Verwaltungsplattform für das Schülercafé Grafing („Chaxter“):</b> Für den schnellen Thekenbetrieb am Tablet und Smartphone optimierte Web-App zur tagesaktuellen Besucherzählung, Rollen- und Teamverwaltung sowie statistischen Auswertung.<br/>
      <sub><code>Next.js (App Router)</code> · <code>TypeScript</code> · <code>Tailwind CSS</code> · <code>Neon PostgreSQL</code> · <code>Better Auth</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <a href="https://github.com/n-bross/JUFO-Web">
        <img src="assets/logos/jufo-web.png" width="68" height="68" alt="JUFO-Web Logo" />
      </a>
    </td>
    <td valign="top">
      <a href="https://github.com/n-bross/JUFO-Web"><b>JUFO-Web</b></a> &nbsp;
      <a href="https://github.com/n-bross/JUFO-Web"><img src="https://img.shields.io/badge/Open_Source-Public_Repo-2ea043?style=flat-square&logo=github" alt="Open Source" /></a><br/>
      <b>Web-Plattform für das Jugendforum Grafing:</b> Full-Stack-Webanwendung mit durchgängiger Typsicherheit vom Datenbankschema bis zum Frontend im modernen T3-Stack.<br/>
      <sub><code>Next.js</code> · <code>TypeScript</code> · <code>tRPC</code> · <code>Prisma ORM</code> · <code>Tailwind CSS</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <a href="https://github.com/n-bross/PriceWatch">
        <img src="assets/logos/pricewatch.png" width="68" height="68" alt="PriceWatch Logo" />
      </a>
    </td>
    <td valign="top">
      <a href="https://github.com/n-bross/PriceWatch"><b>PriceWatch</b></a> &nbsp;
      <a href="https://github.com/n-bross/PriceWatch"><img src="https://img.shields.io/badge/Open_Source-Public_Repo-2ea043?style=flat-square&logo=github" alt="Open Source" /></a><br/>
      <b>Native iOS-App für smarte Einkaufslisten &amp; Supermarkt-Preisvergleiche:</b> Kombiniert aktuelle Prospekt-Angebote deutscher Einzelhändler mit einer intelligenten Einkaufsliste und Cloud-Synchronisation.<br/>
      <sub><code>Swift</code> · <code>SwiftUI</code> · <code>Supabase</code> · <code>iOS</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <a href="https://github.com/n-bross/where2watch">
        <img src="assets/logos/where2watch.png" width="68" height="68" alt="where2watch Logo" />
      </a>
    </td>
    <td valign="top">
      <a href="https://github.com/n-bross/where2watch"><b>where2watch</b></a> &nbsp;
      <a href="https://github.com/n-bross/where2watch"><img src="https://img.shields.io/badge/Open_Source-Public_Repo-2ea043?style=flat-square&logo=github" alt="Open Source" /></a><br/>
      <b>Open-Source-Streaming-Suchmaschine:</b> Werbefreie Cross-Platform-Alternative zu JustWatch — zeigt sofort, bei welchem Anbieter Filme und Serien im Abo, zur Leihe oder zum Kauf verfügbar sind, gestützt durch einen eigenen Python-TMDB-Adapter.<br/>
      <sub><code>Flutter</code> · <code>Dart</code> · <code>Python</code> · <code>TMDB API</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/bewerbung-latex.png" width="68" height="68" alt="Bewerbungsstudio Logo" />
    </td>
    <td valign="top">
      <b>Bewerbungsstudio (bewerbung-latex)</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Workflow_Engine-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Datengetriebene LaTeX-Bewerbungsplattform mit Web-UI:</b> Trennt strukturierte CSV-/Metadaten strikt vom Textsatz (<code>moderncv</code>), bietet ein lokales Kanban-Board zur Prozessverfolgung und kompiliert Anschreiben, Lebenslauf und Zeugnismappen vollautomatisch zu druckfertigen PDFs.<br/>
      <sub><code>Python</code> · <code>LaTeX</code> · <code>Web UI</code> · <code>Document Automation</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/arbeitsamt-pdf-creator.png" width="68" height="68" alt="Arbeitsamt-PDF-Creator Logo" />
    </td>
    <td valign="top">
      <b>Arbeitsamt-PDF-Creator</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Automation_Tool-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Automatisierte Nachweis- &amp; Beleggenerierung:</b> Spezialisiertes Python-Tooling zur datengesteuerten Erstellung, Zusammenführung und Archivierung standardisierter PDF-Nachweise.<br/>
      <sub><code>Python</code> · <code>PDF Processing</code> · <code>CLI Automation</code></sub>
    </td>
  </tr>
</table>

---

### 🏠 Smart Home, Homelab & System-Infrastruktur

<table>
  <tr>
    <td width="84" align="center" valign="middle">
      <a href="https://github.com/n-bross/ha-hermes-conversation">
        <img src="assets/logos/ha-hermes-conversation.png" width="68" height="68" alt="Hermes Home Assistant Conversation Logo" />
      </a>
    </td>
    <td valign="top">
      <a href="https://github.com/n-bross/ha-hermes-conversation"><b>Hermes Home Assistant Conversation</b></a> &nbsp;
      <a href="https://github.com/n-bross/ha-hermes-conversation"><img src="https://img.shields.io/badge/Open_Source-HACS_Integration-2ea043?style=flat-square&logo=github" alt="Open Source" /></a><br/>
      <b>KI-Sprachassistenten-Integration für Home Assistant Assist:</b> HACS-kompatible Custom Integration, die Sprachbefehle und Satz-Trigger über eine asynchrone FastAPI-Bridge mit persistentem SQLite-Konversationsgedächtnis an einen selbstgehosteten KI-Agenten anbindet.<br/>
      <sub><code>Python</code> · <code>Home Assistant</code> · <code>FastAPI</code> · <code>SQLite</code> · <code>HACS</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <a href="https://github.com/n-bross/vacuum_room_scheduler">
        <img src="assets/logos/vacuum-room-scheduler.png" width="68" height="68" alt="Vacuum Room Scheduler Logo" />
      </a>
    </td>
    <td valign="top">
      <a href="https://github.com/n-bross/vacuum_room_scheduler"><b>Vacuum Room Scheduler</b></a> &nbsp;
      <a href="https://github.com/n-bross/vacuum_room_scheduler"><img src="https://img.shields.io/badge/Open_Source-Public_Repo-2ea043?style=flat-square&logo=github" alt="Open Source" /></a><br/>
      <b>Intelligente Raumreinigungs-Steuerung für Home Assistant:</b> Custom Integration für raumbasierte Reinigungsintervalle, Anwesenheitserkennung, Fehler-Recovery und kontextabhängige Sprachbenachrichtigungen.<br/>
      <sub><code>Python</code> · <code>Home Assistant</code> · <code>IoT Automation</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/odysseus.png" width="68" height="68" alt="Odysseus Logo" />
    </td>
    <td valign="top">
      <b>Odysseus</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-AI_Workspace-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Selbstgehosteter KI-Wissens- &amp; Recherche-Stack:</b> Containerisierte Umgebung mit semantischer Vektordatenbank (ChromaDB), datenschutzfreundlicher Metasuchmaschine (SearXNG) und Echtzeit-Push-Benachrichtigungen (ntfy).<br/>
      <sub><code>Python</code> · <code>Docker Compose</code> · <code>ChromaDB</code> · <code>SearXNG</code> · <code>ntfy</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/truenas-setup.png" width="68" height="68" alt="TrueNAS-Setup Logo" />
    </td>
    <td valign="top">
      <b>TrueNAS-Setup &amp; Ansible Homelab</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Infrastructure_as_Code-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Deklarative Server- &amp; Storage-Infrastruktur:</b> Verwaltet über 40 Docker-Container, ZFS-Storage-Pools, einen föderierten Matrix-Homeserver (Synapse, Matrix Authentication Service, LiveKit-RTC &amp; Bridges), Authentik-SSO und Reverse-Proxies (Caddy) per Ansible und GitOps-Workflows.<br/>
      <sub><code>Ansible</code> · <code>TrueNAS SCALE</code> · <code>ZFS</code> · <code>Docker</code> · <code>Caddy</code> · <code>Authentik</code> · <code>Matrix</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/argus.png" width="68" height="68" alt="Argus Logo" />
    </td>
    <td valign="top">
      <b>Argus</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Observability-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Selbstgehosteter Monitoring- &amp; Metrik-Stack:</b> Erfasst und visualisiert System-, Container- und Netzwerkmetriken über alle Hosts im Tailnet hinweg mit Langzeit-Zeitreihenspeicherung und Alerting.<br/>
      <sub><code>Prometheus</code> · <code>Grafana</code> · <code>VictoriaMetrics</code> · <code>Node Exporter</code> · <code>cAdvisor</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/book-orbit.png" width="68" height="68" alt="Book Orbit Logo" />
    </td>
    <td valign="top">
      <b>Book Orbit</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Media_Stack-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Selbstgehosteter Hörbuch- &amp; E-Book-Medienserver:</b> Zentraler Medien-Stack auf TrueNAS SCALE mit automatisierter Metadaten-Aufbereitung, Fortschrittssynchronisation und mobilem Streaming.<br/>
      <sub><code>Docker</code> · <code>TrueNAS SCALE</code> · <code>Self-Hosted</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/adhd-task-orchestrator.png" width="68" height="68" alt="ADHD Task Orchestrator Logo" />
    </td>
    <td valign="top">
      <b>ADHD Task Orchestrator</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-Productivity_Engine-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Fokus-Timer &amp; Aufgaben-Orchestrierung:</b> Verbindet Aufgabenplanung, Raycast-Schnellzugriffe auf macOS und physische Smart-Home-Signale (Licht-/TTS-Feedback über Home Assistant) für fokussierte Deep-Work-Sessions.<br/>
      <sub><code>Python</code> · <code>Raycast</code> · <code>Home Assistant API</code> · <code>REST</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <img src="assets/logos/todo-kalender.png" width="68" height="68" alt="Todo-Kalender Logo" />
    </td>
    <td valign="top">
      <b>Todo-Kalender (CalDAV Sync)</b> &nbsp;
      <img src="https://img.shields.io/badge/Private-CalDAV_Service-6e7681?style=flat-square&logo=github" alt="Private" /><br/>
      <b>Bidirektionale Aufgaben- &amp; Kalender-Synchronisation:</b> Eigener Radicale-CalDAV-Stack mit Python-Synchronisationsdienst, der offene Aufgaben automatisch als terminierte Kalenderblöcke auf iOS und macOS abbildet.<br/>
      <sub><code>Python</code> · <code>CalDAV</code> · <code>Radicale</code> · <code>Docker</code></sub>
    </td>
  </tr>
  <tr>
    <td width="84" align="center" valign="middle">
      <a href="https://github.com/n-bross/Go60-ZMK">
        <img src="assets/logos/go60-zmk.png" width="68" height="68" alt="Go60-ZMK Logo" />
      </a>
    </td>
    <td valign="top">
      <a href="https://github.com/n-bross/Go60-ZMK"><b>Go60-ZMK</b></a> &nbsp;
      <a href="https://github.com/n-bross/Go60-ZMK"><img src="https://img.shields.io/badge/Open_Source-Public_Repo-2ea043?style=flat-square&logo=github" alt="Open Source" /></a><br/>
      <b>Custom Split-Keyboard-Firmware &amp; lokale Build-Pipeline:</b> Maßgeschneiderte ZMK-Konfiguration, ergonomische Layer-Architektur (HRM, Symbol- &amp; Navigation-Layer) und reproduzierbare Zephyr-RTOS-Builds für das MoErgo Go60.<br/>
      <sub><code>C / Devicetree</code> · <code>ZMK Firmware</code> · <code>Zephyr RTOS</code> · <code>GitHub Actions</code></sub>
    </td>
  </tr>
</table>

---

## 🧰 Tech-Stack & Schwerpunkte

| Bereich | Technologien & Werkzeuge |
| :--- | :--- |
| **Sprachen** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Backend & Web** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=flat-square&logo=trpc&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Mobile, Audio & KI** | ![SwiftUI](https://img.shields.io/badge/SwiftUI-0051D5?style=flat-square&logo=swift&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Apple MLX](https://img.shields.io/badge/Apple_MLX_Whisper-000000?style=flat-square&logo=apple&logoColor=white) ![PyAnnote](https://img.shields.io/badge/PyAnnote_Diarization-FF6F00?style=flat-square) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF4F00?style=flat-square) |
| **DevOps, Infra & QA** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![TrueNAS SCALE](https://img.shields.io/badge/TrueNAS_SCALE_%2F_ZFS-0095D5?style=flat-square&logo=truenas&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale_Zero--Trust-242424?style=flat-square&logo=tailscale&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white) ![Grafana](https://img.shields.io/badge/Prometheus_%26_Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins_CI%2FCD-D24939?style=flat-square&logo=jenkins&logoColor=white) |
