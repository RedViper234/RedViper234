<!-- ============================================================
     PROFILE README  ·  Niccolò
     Palette  →  slate #0B1622 · cyan #38BDF8 · amber #F59E0B
     Replace every  your-username / your-link  placeholder.
     ============================================================ -->

<div align="center">

<img src="assets/header.svg" alt="Niccolò — Full-stack engineer: graphics, WebAssembly, real-time systems" width="100%"/>

<sub>Florence, Tuscany · Italy</sub>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-0B1622?style=flat-square&logo=github&logoColor=white)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B1622?style=flat-square&logo=linkedin&logoColor=38BDF8)](https://linkedin.com/in/your-link)
[![npm](https://img.shields.io/badge/npm-0B1622?style=flat-square&logo=npm&logoColor=F59E0B)](https://www.npmjs.com/~your-npm)
[![Email](https://img.shields.io/badge/Email-0B1622?style=flat-square&logo=maildotru&logoColor=white)](mailto:you@example.com)

</div>

<br/>

> I build the parts most people call _"not possible in the browser"_ —
> Rust → WASM tooling, WebGPU rendering, and C++ sensor pipelines, wired into production web apps.

---

### What I work on

**Real-time graphics & geospatial.** Three.js + WebGPU naval visualization fed by a C++ radar-spoke backend over WebRTC. DEM tile fetching, PNG decode, bilinear sampling and land/sea elevation merging — done in TypeScript, profiled down to the render loop (IndexedDB cache churn, WebGPU pipeline-compilation stalls).

**WebAssembly tooling.** Browser-side parsers with a Rust/WASM core and a thin TypeScript shell — `wasm-pack` + `wasm-bindgen`, shipped as installable npm packages.

**Production web at scale.** React/TypeScript SPAs on a Node.js backend (Nginx · PM2 · Linux), high-throughput canvas rendering of hundreds of live targets over WebSocket, and data plumbing on PostgreSQL/PostGIS with streaming replication over a private network.

---

### Selected work

**[`@niccolo/idml-parser`](https://www.npmjs.com/package/@niccolo/idml-parser)** — Browser-side Adobe IDML parser & SVG renderer.
<sub>Rust/WASM core (`wasm-pack`, `wasm-bindgen`) · TypeScript shell · zero-server, runs entirely client-side.</sub>

**Real-time naval visualization** — USV sensor data, rendered live.
<sub>Three.js (WebGPU) · Next.js · C++ radar-spoke processing · WebRTC transport.</sub>

**AIS vessel tracking** — Hundreds of simultaneous targets, smooth.
<sub>Custom Leaflet Canvas layer · WebSocket · SVG ship markers tuned to Marine-Traffic style.</sub>

**PDF → editable HTML** — Pixel-perfect, in-browser.
<sub>Node.js · MuPDF (WASM) · contenteditable text spans overlaid on rendered pages.</sub>

<sub>I also maintain GDO / large-scale-retail tooling and distributed retail-data systems (Bun · Hono · PostgreSQL · Redis · Ollama). Most of that is closed-source — happy to talk through it.</sub>

---

### Stack

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-CE412B?style=flat-square&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Graphics & low-level**
![WebGPU](https://img.shields.io/badge/WebGPU-005A9C?style=flat-square&logo=webgpu&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white)

**Web**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-14151A?style=flat-square&logo=bun&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-0B1622?style=flat-square&logo=tailwindcss&logoColor=38BDF8)

**Data & infra**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-0B1622?style=flat-square&logo=linux&logoColor=F59E0B)

---

### Currently

Pushing a real-time naval-drone visualization system: **Three.js WebGPU + Next.js** on the front, **C++** crunching radar spokes on the back, **WebRTC** moving sensor data in between — and chasing every millisecond out of the render loop.

<br/>

<div align="center">
<sub>Built in TypeScript, Rust, and C++. Kept simple on purpose.</sub>
</div>
