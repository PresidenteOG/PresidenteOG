![Daniel Adanegbe](./banner.png)

Multiplatform developer, CFGS DAM graduate, looking for a junior developer role. I work across
web, desktop, Android, backend and embedded, and I'd rather ship something small that runs than
leave something big half-finished.

- Built a club-management ERP with two classmates during my DAM work placement — CRUD, roles,
  bulk email — on a Java and Spring Boot stack.
- The projects below are coursework and personal work, cleaned up and made to run from a clean
  clone with no external service behind them: a local database, a stubbed mail sender, a local
  MQTT broker.
- On CI/CD: [incident-tracker](https://github.com/PresidenteOG/incident-tracker) runs its test
  suite and publishes a coverage badge on every push, web-calculator deploys itself to GitHub
  Pages, and every ESP32 exercise in [embedded-systems-lab](https://github.com/PresidenteOG/embedded-systems-lab/actions/workflows/wokwi-ci.yml)
  runs headless in the simulator.
- Terrassa, Catalonia. Spanish and Catalan native, English B2.
- danieladanegbe@gmail.com

#### Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat&logo=tauri&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white)
![MicroPython](https://img.shields.io/badge/MicroPython-2B2728?style=flat&logo=micropython&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

#### Projects

| Project | Stack | What it is |
|---|---|---|
| [tennis-club-manager](https://github.com/PresidenteOG/tennis-club-manager) | Java · Spring Boot · Thymeleaf · Spring Security | Back office for a tennis club — members, leagues, courts, matches, announcements. Team project from the DAM course. |
| [incident-tracker](https://github.com/PresidenteOG/incident-tracker) | Java · Spring Boot · Thymeleaf | Internal IT incident log — controller → service → JPA repository, session login, in-memory H2. Service layer under test, coverage badge, CI on every push. |
| [fiber-device-manager](https://github.com/PresidenteOG/fiber-device-manager) | Kotlin · Jetpack Compose · Room | Android console for a device fleet. Runs entirely on-device — no backend, no `INTERNET` permission. |
| [room-planner-3d](https://github.com/PresidenteOG/room-planner-3d) | Rust · Tauri 2 · React · three.js | Desktop room designer — 2D plan, 3D preview, undo/redo, its own `.roomz` save format. |
| [encrypted-mqtt-chat](https://github.com/PresidenteOG/encrypted-mqtt-chat) | Python · Tkinter · MQTT | Group chat where the broker only sees ciphertext. Honest about what the shared-key model does and doesn't protect. |
| [unity-minigames](https://github.com/PresidenteOG/unity-minigames) | C# · Unity | Two workshop minigames — a physics ball-roller with NavMesh enemy AI and a platform/portal runner. Playable Windows and Linux builds attached. |
| [embedded-systems-lab](https://github.com/PresidenteOG/embedded-systems-lab) | MicroPython · ESP32 · Wokwi | Sensor, actuator and MQTT exercises in the Wokwi simulator. Every one runs headless in CI. |
| [web-calculator](https://github.com/PresidenteOG/web-calculator) · [live](https://presidenteog.github.io/web-calculator/) | HTML · CSS · JavaScript | One HTML file, no build step, no dependencies. Deployed to GitHub Pages by Actions. |
| [learning-lab](https://github.com/PresidenteOG/learning-lab) | Java · Python · JS · CSS · Bash | Two years of small coursework exercises, sorted by language, with a note on what each one practices. |

#### Work placement

Second-year DAM placement at Club de Tennis Terrassa: a club-management ERP in Java, Spring
Boot, Docker and MySQL. CRUD for members and bookings, role-based access, bulk and
category-targeted email. It's a three-person codebase, so what's on GitHub
([tennis-club-manager](https://github.com/PresidenteOG/tennis-club-manager)) is a clean copy
with the real club's data stripped out — I can walk through the original in an interview.

Before that, a first-year SMIX placement at Escola La Nova Electra doing hardware diagnosis and
IT support.
