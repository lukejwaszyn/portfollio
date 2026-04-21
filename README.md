# Luke J. Waszyn II — Portfolio

Hey — if you've stumbled onto this, thanks for looking.

I'm a junior studying **Engineering Science** at Penn State with a minor in Engineering Mechanics and a Certificate in Space Systems Engineering. I care about space, complex systems, and the discipline of taking something from a stakeholder need all the way through verification. The work I'm proudest of lives at the seam between **formal systems engineering** and **hands-on hardware** — writing requirements that trace, building antennas that actually receive signal, leading an SE effort through PDR, and shipping things that work.

This repo is the source for my portfolio site, which you can see live at:

**→ [lukejwaszyn.github.io/portfollio](https://lukejwaszyn.github.io/portfollio/)**

*(Yes, the repo name has two L's. I'm aware. It's staying.)*

## What's on the site

- **RECLAIM** — Co-Lead Systems Engineer on a NASA LunaRecycle team (Phase II winner, competing in Phase III with a $1.2M prize ceiling). Microwave-based in-situ recycling for lunar operations, with a 7-subsystem L0–L1 architecture driving toward PDR.
- **Autonomous Satellite Ground Station** — Solo-built 8,500+ line ground station tracking 11 satellites across 5 constellations, decoding NOAA APT and METEOR LRPT weather imagery through a full pipeline: SGP4 orbital prediction, C++ real-time I/Q capture, custom APT/LRPT decoders, a Three.js 3D mission-operations interface, and an ML pipeline for pass scoring.
- **RTL-SDR Signal Processing & Antenna Systems** — End-to-end FM-band receive system with a custom-fabricated dipole, MATLAB DSP pipeline, and a staged V0–V4 verification campaign run on real hardware.
- **Tone Control / Karaoke Circuit** — Five-block analog audio system with Baxandall tone control, karaoke vocal cancellation, and an LED VU display, designed in Multisim and fabricated onto PCB.
- **Research** — HEATER Lab (thermal systems, frost imaging, supercritical CO₂ instrumentation) and Systems Design Lab (planning senior thesis in space communications and SDR).
- **Experience, coursework, involvement, awards, and how to reach me.**

## Repo structure

```
portfollio/
├── index.html                         ← the whole site (single file, no build step)
└── assets/
    ├── Waszyn_Resume.pdf              ← downloadable from the site
    ├── about/headshot.jpg
    ├── lunarecycle/                   ← RECLAIM imagery
    ├── ground-station/                ← HMI screenshots + hardware
    ├── rtl-sdr/                       ← antenna and SDR
    └── tone-control/                  ← PCB
```

Everything lives in one HTML file — CSS at the top, JavaScript at the bottom, content in between. Deployed via GitHub Pages. No build step, no framework, no dependencies. It's intentional: the site should be as easy to maintain as it was to build.

## Tech used

Plain HTML, CSS, and vanilla JavaScript. Custom starfield canvas. Fonts from Google (Outfit + JetBrains Mono). Aesthetic pulled from NASA mission control and the Artemis program.

## Get in touch

- **Email:** ljw5734@psu.edu · lukejwasz@gmail.com
- **LinkedIn:** [luke-waszyn-6a35592b4](https://www.linkedin.com/in/luke-waszyn-6a35592b4)
- **GitHub:** you're already here

---

*Summer 2026: incoming Spacecraft Systems Engineering Intern at Millennium Space Systems (Boeing) in Chantilly, VA.*
