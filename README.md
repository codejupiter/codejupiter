<p align="center">
  <img src="./assets/profile-banner.svg" alt="Zoriah Cocio — Full-Stack Software Engineer and Open-Source Hardware Designer" width="100%" />
</p>

<p align="center">
  <a href="https://zoriahcocio.com"><img src="https://img.shields.io/badge/Portfolio-zoriahcocio.com-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://github.com/codejupiter"><img src="https://img.shields.io/badge/GitHub-codejupiter-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://linkedin.com/in/zoriah-cocio"><img src="https://img.shields.io/badge/LinkedIn-Zoriah_Cocio-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:info@zoriahcocio.com"><img src="https://img.shields.io/badge/Email-Let's_build-334155?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## Full-stack software engineering meets physical hardware

I am a **Full-Stack Software Engineer and Open-Source Hardware Designer** building complete systems—from high-performance web applications and reusable UI foundations to custom PCBs, embedded C++ firmware, and working physical prototypes.

My work does not stop at the browser or the breadboard. I care about the entire path: product architecture, interface performance, device firmware, electrical design, mechanical constraints, manufacturing files, automation, testing, and clear documentation.

<table>
  <tr>
    <td><strong>Core focus</strong></td>
    <td>Full-stack engineering, hardware prototyping, PCB design, embedded firmware, and physical product development</td>
  </tr>
  <tr>
    <td><strong>Software systems</strong></td>
    <td>Product architecture, design systems, analytics interfaces, real-time UX, automation, and developer tooling</td>
  </tr>
  <tr>
    <td><strong>Hardware systems</strong></td>
    <td>Custom PCBs, USB devices, embedded C++, switch matrices, electrical prototyping, and CAD-aware design</td>
  </tr>
</table>

## Hardware & Embedded Systems

### RP2040 Custom 2×2 USB Macropad

<p align="center">
  <a href="https://github.com/codejupiter/rp2040-macropad">
    <img src="./assets/rp2040-macropad-render.png" alt="3D render of the red RP2040 custom 2x2 USB mechanical macropad PCB" width="760" />
  </a>
</p>

I engineered [`rp2040-macropad`](https://github.com/codejupiter/rp2040-macropad) from scratch: a compact, open-hardware USB input device built around a header-mounted Raspberry Pi Pico. The **58 × 97 mm, two-layer PCB** was designed and routed in **KiCad**, ordered with a **red solder mask**, and carries four MX-compatible switches with one **1N4148 diode per key** for an anti-ghosting 2×2 matrix.

The firmware is written in **C++17** on the official **Raspberry Pi Pico SDK** and uses **TinyUSB** for driverless USB HID keyboard reports. The repository includes editable KiCad sources, verified Gerber and drill files, a bill of materials, assembly documentation, automated CMake builds, and a `picotool`/BOOTSEL flashing workflow.

<p align="center">
  <a href="https://github.com/codejupiter/rp2040-macropad"><strong>Explore the repository</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/codejupiter/rp2040-macropad/tree/main/hardware"><strong>KiCad & manufacturing files</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/codejupiter/rp2040-macropad/blob/main/main.cpp"><strong>Firmware</strong></a>
</p>

| Hardware | Firmware | Delivery |
| --- | --- | --- |
| Raspberry Pi Pico / RP2040 | C++17 + Pico SDK | CMake + GitHub Actions |
| 2×2 MX switch matrix | TinyUSB HID keyboard | Automated flashing script |
| Four 1N4148 diodes | Debouncing + multi-key input | Gerber, drill, BOM, and assembly docs |
| 58 × 97 mm, two-layer PCB | GP0/GP1 rows · GP6/GP7 columns | Zero-dependency host integration |

## Full-stack software ecosystem

<table>
  <tr>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/codejupiter/Dense-UI">Dense-UI</a></h3>
      <p>A compact, accessible React component library for data-heavy dashboards, admin panels, and operational tools. Built with TypeScript, Radix primitives, CSS variables, Storybook, and tree-shakeable package exports.</p>
      <p><a href="https://dense-ui.vercel.app"><strong>Live documentation →</strong></a></p>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/codejupiter/Spendboard">SpendBoard</a></h3>
      <p>A high-performance spend analytics dashboard with filtering, charts, saved views, keyboard navigation, and a virtualized table handling 50,000+ transactions.</p>
      <p><a href="https://spendboard-beige.vercel.app"><strong>Live demo →</strong></a></p>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/codejupiter/dealbrief">dealbrief</a></h3>
      <p>An agentic deal-intelligence application with a five-stage LLM pipeline, streaming synthesis, embedding-based playbook matching, and structured model handoffs.</p>
      <p><a href="https://dealbrief-codejupiters-projects.vercel.app"><strong>Live demo →</strong></a></p>
    </td>
  </tr>
</table>

Across these projects I build the product surface and the systems behind it: typed application architecture, reusable UI primitives, large-data rendering, AI-assisted workflows, test suites, CI pipelines, deployment automation, and production-focused documentation.

## Engineering stack

### Frontend & product UI

<p>
  <img src="https://img.shields.io/badge/TypeScript-0F172A?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-0F172A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-0F172A?style=for-the-badge&logo=nextdotjs&logoColor=FFFFFF" alt="Next.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Vite-0F172A?style=for-the-badge&logo=vite&logoColor=646CFF" alt="Vite" />
</p>

### Backend & automation

<p>
  <img src="https://img.shields.io/badge/Python-0F172A?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python" />
  <img src="https://img.shields.io/badge/Node.js-0F172A?style=for-the-badge&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-0F172A?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Git-0F172A?style=for-the-badge&logo=git&logoColor=F05032" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub_Actions-0F172A?style=for-the-badge&logo=githubactions&logoColor=2088FF" alt="GitHub Actions" />
</p>

### Embedded & hardware

<p>
  <img src="https://img.shields.io/badge/Embedded_C%2B%2B-0F172A?style=for-the-badge&logo=cplusplus&logoColor=00599C" alt="Embedded C++" />
  <img src="https://img.shields.io/badge/KiCad-0F172A?style=for-the-badge&logo=kicad&logoColor=314CB0" alt="KiCad" />
  <img src="https://img.shields.io/badge/PCB_Design-0F172A?style=for-the-badge&logo=printedcircuitboard&logoColor=22C55E" alt="PCB Design" />
  <img src="https://img.shields.io/badge/RP2040_SDK-0F172A?style=for-the-badge&logo=raspberrypi&logoColor=C51A4A" alt="RP2040 SDK" />
  <img src="https://img.shields.io/badge/TinyUSB-0F172A?style=for-the-badge&logo=usb&logoColor=38BDF8" alt="TinyUSB" />
  <img src="https://img.shields.io/badge/Soldering_%26_Prototyping-0F172A?style=for-the-badge&logoColor=F59E0B" alt="Soldering and Prototyping" />
  <img src="https://img.shields.io/badge/3D_Design_%2F_CAD-0F172A?style=for-the-badge&logo=autodesk&logoColor=0696D7" alt="3D Design and CAD" />
</p>

## What I optimize for

- **End-to-end ownership** — from an interaction model or circuit sketch to a tested, documented release.
- **Performance with evidence** — virtualized data interfaces, measurable bundle decisions, and tight embedded loops.
- **Reproducibility** — automated builds, flashing, checks, and manufacturing outputs that another engineer can use.
- **Open engineering** — readable source, explicit tradeoffs, and documentation that makes the work easier to extend.

## GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=codejupiter&show_icons=true&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=CBD5E1&icon_color=22C55E" alt="Zoriah's GitHub statistics" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=codejupiter&layout=compact&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=CBD5E1" alt="Most used languages" />
</p>

## Let’s build something complete

I am open to full-stack, frontend, product engineering, embedded systems, and cross-disciplinary hardware/software opportunities.

<p>
  <a href="https://zoriahcocio.com"><strong>Portfolio</strong></a>
  &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/zoriah-cocio"><strong>LinkedIn</strong></a>
  &nbsp;·&nbsp;
  <a href="mailto:info@zoriahcocio.com"><strong>Email</strong></a>
</p>
