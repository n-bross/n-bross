<div align="center">

<img src="assets/logos/fleet.png" width="82" height="82" alt="Nico Broß — Portfolio Logo" />

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
- 🏗️ **System-Architektur im eigenen Lab:** Produktives Multi-Node-Setup (Linux-VPS, TrueNAS SCALE mit ZFS, dedizierte KI-Jails, Home Assistant OS & Apple-Silicon-Worker), vernetzt über ein Zero-Trust-Mesh (Tailscale) mit zentralem Monitoring, SSO und Secret-Management.
- 🔒 **Hinweis zu Repository-Sichtbarkeiten:** Da viele meiner produktiven Systeme direkt in meine Infrastruktur oder kommunale Umgebungen eingebunden sind, sind diese als `Private / Self-Hosted` markiert. Öffentliche Projekte (`Open Source`) sind direkt verlinkt — **Architektur-Einblicke, Live-Demos und Code-Walkthroughs zeige ich jederzeit gerne im Gespräch!**

---

## ⭐ Ausgewählte Flaggschiff-Projekte

<table>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/logos/soundcore-export.png" width="54" height="54" align="left" alt="Keepsaid Logo" />
      <b>Keepsaid &amp; Soundcore-Export</b><br/>
      <img src="https://img.shields.io/badge/Private-Distributed_Pipeline-6e7681?style=flat-square&logo=github" alt="Private" />
      <br clear="left"/>
      <sub><b>Persönliches Audioarchiv &amp; verteilte Sprach-Pipeline:</b> Automatischer Cloud-Ingest mit <code>AES-256-GCM</code>-Entschlüsselung, Rauschunterdrückung (RNNoise), GPU-Transkription via <code>mlx-whisper</code> auf Apple Silicon, Sprecher-Diarisierung (PyAnnote) und Web-Review-UI zum wortweisen Mitlesen.</sub><br/>
      <sub><code>Python</code> · <code>FastAPI</code> · <code>MLX-Whisper</code> · <code>PyAnnote</code> · <code>Docker</code></sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/logos/speech-lab.png" width="54" height="54" align="left" alt="Speech Lab Logo" />
      <b>Speech Lab</b><br/>
      <img src="https://img.shields.io/badge/Private-Evaluation_Suite-6e7681?style=flat-square&logo=github" alt="Private" />
      <br clear="left"/>
      <sub><b>Reproduzierbare ASR-Benchmark-Suite:</b> Lokales Evaluierungslabor zum systematischen Vergleich von lokalen und Cloud-Sprachmodellen, exakter Wortzeitmarken-Ausrichtung und Mehrsprecher-Erkennung gegen <code>SHA256</code>-verankerte Referenztranskripte.</sub><br/>
      <sub><code>Python</code> · <code>ASR Benchmarking</code> · <code>Diarization</code> · <code>Web UI</code> · <code>pytest</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/logos/fleet.png" width="54" height="54" align="left" alt="Fleet Logo" />
      <b>Fleet</b><br/>
      <img src="https://img.shields.io/badge/Private-Infra_CLI-6e7681?style=flat-square&logo=github" alt="Private" />
      <br clear="left"/>
      <sub><b>Multi-Host-Orchestrierung &amp; Health-Radar:</b> Zentrales CLI (<code>fleet doctor</code>, <code>fleet sync</code>) zur Überwachung und Synchronisation von über 45 Repos und Diensten über Linux-VPS, TrueNAS, Home Assistant und macOS inkl. dynamischer 1Password-Injektion (<code>op://</code>).</sub><br/>
      <sub><code>Python</code> · <code>Bash</code> · <code>1Password CLI</code> · <code>Tailscale</code> · <code>systemd</code></sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/logos/chaxterlog.png" width="54" height="54" align="left" alt="ChaxterLog Logo" />
      <b>ChaxterLog</b><br/>
      <img src="https://img.shields.io/badge/Private-Production_App-6e7681?style=flat-square&logo=github" alt="Private" />
      <br clear="left"/>
      <sub><b>Besucher-Analytics &amp; Verwaltung (Schülercafé Grafing):</b> Für den schnellen Thekenbetrieb am Tablet und Smartphone optimierte Web-App zur tagesaktuellen Besucherzählung, Rollen- und Teamverwaltung sowie statistischen Auswertung.</sub><br/>
      <sub><code>Next.js</code> · <code>TypeScript</code> · <code>Tailwind CSS</code> · <code>Neon PostgreSQL</code> · <code>Better Auth</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/n-bross/JUFO-Web"><img src="assets/logos/jufo-web.png" width="54" height="54" align="left" alt="JUFO-Web Logo" /></a>
      <a href="https://github.com/n-bross/JUFO-Web"><b>JUFO-Web</b></a><br/>
      <a href="https://github.com/n-bross/JUFO-Web"><img src="https://img.shields.io/badge/Open_Source-Public_Repo-2ea043?style=flat-square&logo=github" alt="Open Source" /></a>
      <br clear="left"/>
      <sub><b>Web-Plattform für das Jugendforum Grafing:</b> Full-Stack-Webanwendung mit durchgängiger End-to-End-Typsicherheit vom Datenbankschema bis zum Frontend im modernen T3-Stack.</sub><br/>
      <sub><code>Next.js</code> · <code>TypeScript</code> · <code>tRPC</code> · <code>Prisma ORM</code> · <code>Tailwind CSS</code></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/n-bross/PriceWatch"><img src="assets/logos/pricewatch.png" width="54" height="54" align="left" alt="PriceWatch Logo" /></a>
      <a href="https://github.com/n-bross/PriceWatch"><b>PriceWatch</b></a><br/>
      <a href="https://github.com/n-bross/PriceWatch"><img src="https://img.shields.io/badge/Open_Source-Public_Repo-2ea043?style=flat-square&logo=github" alt="Open Source" /></a>
      <br clear="left"/>
      <sub><b>Native iOS-App für smarte Einkaufslisten &amp; Preisvergleiche:</b> Kombiniert aktuelle Prospekt-Angebote deutscher Einzelhändler mit einer intelligenten Einkaufsliste und Cloud-Synchronisation.</sub><br/>
      <sub><code>Swift</code> · <code>SwiftUI</code> · <code>Supabase</code> · <code>iOS</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/n-bross/where2watch"><img src="assets/logos/where2watch.png" width="54" height="54" align="left" alt="where2watch Logo" /></a>
      <a href="https://github.com/n-bross/where2watch"><b>where2watch</b></a><br/>
      <a href="https://github.com/n-bross/where2watch"><img src="https://img.shields.io/badge/Open_Source-Public_Repo-2ea043?style=flat-square&logo=github" alt="Open Source" /></a>
      <br clear="left"/>
      <sub><b>Open-Source-Streaming-Suchmaschine:</b> Werbefreie Cross-Platform-Alternative zu JustWatch — zeigt sofort, wo Filme &amp; Serien im Abo, zur Leihe oder zum Kauf verfügbar sind, gestützt durch einen eigenen Python-TMDB-Adapter.</sub><br/>
      <sub><code>Flutter</code> · <code>Dart</code> · <code>Python</code> · <code>TMDB API</code></sub>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/n-bross/ha-hermes-conversation"><img src="assets/logos/ha-hermes-conversation.png" width="54" height="54" align="left" alt="Hermes HA Logo" /></a>
      <a href="https://github.com/n-bross/ha-hermes-conversation"><b>Hermes Home Assistant Integration</b></a><br/>
      <a href="https://github.com/n-bross/ha-hermes-conversation"><img src="https://img.shields.io/badge/Open_Source-HACS_Integration-2ea043?style=flat-square&logo=github" alt="Open Source" /></a>
      <br clear="left"/>
      <sub><b>KI-Sprachassistent für Home Assistant Assist:</b> HACS Custom Integration, die Sprachbefehle über eine asynchrone FastAPI-Bridge mit persistentem SQLite-Gedächtnis an einen selbstgehosteten KI-Agenten anbindet.</sub><br/>
      <sub><code>Python</code> · <code>Home Assistant</code> · <code>FastAPI</code> · <code>SQLite</code> · <code>HACS</code></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="assets/logos/orbit.png" width="54" height="54" align="left" alt="Orbit Logo" />
      <b>Orbit // Mission Control</b><br/>
      <img src="https://img.shields.io/badge/Private-Live_Dashboard-6e7681?style=flat-square&logo=github" alt="Private" />
      <br clear="left"/>
      <sub><b>Echtzeit-Service- &amp; Telemetrie-Dashboard:</b> Zentrale Start- und Monitoring-Plattform für alle Dienste im Homelab und Tailnet mit Live-Latenzmessung und Dual-Design-Engine (<i>Stark HUD</i> &amp; <i>Cupertino Glass</i>).</sub><br/>
      <sub><code>Node.js</code> · <code>JavaScript</code> · <code>HTML5 / CSS3</code> · <code>REST API</code></sub>
    </td>
    <td width="50%" valign="top">
      <img src="assets/logos/truenas-setup.png" width="54" height="54" align="left" alt="TrueNAS-Setup Logo" />
      <b>TrueNAS-Setup &amp; Ansible Homelab</b><br/>
      <img src="https://img.shields.io/badge/Private-Infrastructure_as_Code-6e7681?style=flat-square&logo=github" alt="Private" />
      <br clear="left"/>
      <sub><b>Deklarative Server- &amp; Storage-Infrastruktur:</b> Verwaltet 40+ Docker-Container, ZFS-Pools, einen föderierten Matrix-Homeserver (Synapse, MAS, LiveKit), Authentik-SSO und Reverse-Proxies (Caddy) per Ansible &amp; GitOps.</sub><br/>
      <sub><code>Ansible</code> · <code>TrueNAS SCALE</code> · <code>ZFS</code> · <code>Docker</code> · <code>Caddy</code> · <code>Matrix</code></sub>
    </td>
  </tr>
</table>

<details>
<summary><b>📂 Alle weiteren 13 Projekte &amp; Tools anzeigen (KI-Gateways, Smart Home, Workflow-Automation &amp; Hardware)</b></summary>
<br/>

| Logo | Projekt | Status | Kurzbeschreibung & Tech-Stack |
| :---: | :--- | :---: | :--- |
| <img src="assets/logos/iris.png" width="38" height="38" alt="Iris" /> | **Iris** | `Private` | Plattformübergreifender Sync-Daemon (`launchd`/Linux) für KI-Skills zwischen Claude Code, Codex, T3 Code & Cursor (`Python`, `Shell`) |
| <img src="assets/logos/token-maxing.png" width="38" height="38" alt="Token-Maxing" /> | **Token-Maxing** | `Private` | Multi-Account AI Gateway & Telemetrie-Plattform mit SSE-Streaming, Failover & Next.js-Dashboard (`TypeScript`, `Fastify`, `Next.js`, `SQLite`) |
| <img src="assets/logos/cliproxyapi.png" width="38" height="38" alt="CLIProxyAPI" /> | **CLIProxyAPI** | `Private` | Unified AI-Proxy-Server in Go mit Management-Konsole für OpenAI-/Claude-/Gemini-kompatible REST-Endpunkte (`Go`, `REST API`, `OAuth`) |
| <img src="assets/logos/odysseus.png" width="38" height="38" alt="Odysseus" /> | **Odysseus** | `Private` | Selbstgehosteter KI-Wissens- & Recherche-Stack mit Vektordatenbank, Metasuche & Push-Alerts (`Python`, `ChromaDB`, `SearXNG`, `ntfy`) |
| <img src="assets/logos/argus.png" width="38" height="38" alt="Argus" /> | **Argus** | `Private` | Selbstgehosteter Observability- & Metrik-Stack über alle Hosts im Tailnet (`Prometheus`, `Grafana`, `VictoriaMetrics`, `Docker`) |
| <img src="assets/logos/vacuum-room-scheduler.png" width="38" height="38" alt="Vacuum Room Scheduler" /> | [**Vacuum Room Scheduler**](https://github.com/n-bross/vacuum_room_scheduler) | [**`Open Source`**](https://github.com/n-bross/vacuum_room_scheduler) | Home Assistant Custom Integration für raumbasierte Saugroboter-Zeitpläne, Anwesenheitslogik & TTS-Feedback (`Python`, `Home Assistant`) |
| <img src="assets/logos/go60-zmk.png" width="38" height="38" alt="Go60-ZMK" /> | [**Go60-ZMK**](https://github.com/n-bross/Go60-ZMK) | [**`Open Source`**](https://github.com/n-bross/Go60-ZMK) | Custom Split-Keyboard-Firmware, ergonomische Layer-Architektur & lokale Zephyr-Build-Pipeline für das MoErgo Go60 (`C`, `ZMK`, `Zephyr RTOS`) |
| <img src="assets/logos/bewerbung-latex.png" width="38" height="38" alt="Bewerbungsstudio" /> | **Bewerbungsstudio** | `Private` | Datengetriebene LaTeX-Bewerbungsplattform (`moderncv`) mit Kanban-Web-UI und automatischer PDF-Kompilierung (`Python`, `LaTeX`, `Web UI`) |
| <img src="assets/logos/arbeitsamt-pdf-creator.png" width="38" height="38" alt="Arbeitsamt-PDF-Creator" /> | **Arbeitsamt-PDF-Creator** | `Private` | Automatisierte Erstellung, Zusammenführung und Archivierung standardisierter PDF-Nachweise (`Python`, `PDF Automation`) |
| <img src="assets/logos/adhd-task-orchestrator.png" width="38" height="38" alt="ADHD Task Orchestrator" /> | **ADHD Task Orchestrator** | `Private` | Fokus-Timer & Aufgaben-Orchestrierung mit Raycast-Integration und Smart-Home-Licht-/TTS-Feedback (`Python`, `Raycast`, `Home Assistant`) |
| <img src="assets/logos/todo-kalender.png" width="38" height="38" alt="Todo-Kalender" /> | **Todo-Kalender** | `Private` | Bidirektionale CalDAV-/Radicale-Synchronisation zur automatischen Terminierung offener Aufgaben (`Python`, `CalDAV`, `Radicale`) |
| <img src="assets/logos/book-orbit.png" width="38" height="38" alt="Book Orbit" /> | **Book Orbit** | `Private` | Selbstgehosteter Hörbuch- & E-Book-Medienserver auf TrueNAS SCALE mit Fortschrittssynchronisation (`Docker`, `TrueNAS SCALE`) |
| <img src="assets/logos/ai-note-dock.png" width="38" height="38" alt="Ai-Note-Dock" /> | **Ai-Note-Dock** | `Private` | Embedded Hardware-Konzept für einen Raspberry Pi Zero 2 W Bluetooth-Audiorekorder mit Smart-Dock-Upload (`Embedded Linux`, `BlueZ`, `PipeWire`) |

</details>

---

## 🧰 Tech-Stack & Schwerpunkte

| Bereich | Technologien & Werkzeuge |
| :--- | :--- |
| **Sprachen** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Backend & Web** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=flat-square&logo=trpc&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Mobile, Audio & KI** | ![SwiftUI](https://img.shields.io/badge/SwiftUI-0051D5?style=flat-square&logo=swift&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Apple MLX](https://img.shields.io/badge/Apple_MLX_Whisper-000000?style=flat-square&logo=apple&logoColor=white) ![PyAnnote](https://img.shields.io/badge/PyAnnote_Diarization-FF6F00?style=flat-square) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF4F00?style=flat-square) |
| **DevOps, Infra & QA** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![TrueNAS SCALE](https://img.shields.io/badge/TrueNAS_SCALE_%2F_ZFS-0095D5?style=flat-square&logo=truenas&logoColor=white) ![Tailscale](https://img.shields.io/badge/Tailscale_Zero--Trust-242424?style=flat-square&logo=tailscale&logoColor=white) ![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white) ![Grafana](https://img.shields.io/badge/Prometheus_%26_Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins_CI%2FCD-D24939?style=flat-square&logo=jenkins&logoColor=white) |
