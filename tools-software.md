# 🛠️ Tools & software

The software a nuclear engineer actually touches — transport codes, data tools, and utilities. Where a license or registration is needed, it's marked.

## Monte Carlo particle transport

| Tool | Access | Use case |
| --- | --- | --- |
| [OpenMC](https://openmc.org/) | **free, open source** (MIT) | The community's Monte Carlo workhorse: criticality, depletion, shutdown dose rate. Python-scriptable, with [documentation](https://docs.openmc.org/) and active forums. The best tool to learn reactor physics computationally. |
| [Serpent](https://serpent.vtt.fi/) | free for research (VTT license) | Lattice-physics-grade Monte Carlo; the standard for 2D assembly calculations in academia. |
| [MCNP](https://mcnp.lanl.gov/) | free via RSICC registration | The US national-lab general-purpose Monte Carlo code (LANL). Registration required; export-controlled. |
| [Geant4](https://geant4.web.cern.ch/) | **free, open source** (CERN) | Particle transport for particle physics, space, and medical physics; also used for dosimetry. |
| [FLUKA](https://fluka.cern/) | free for research | Multi-purpose transport, strong in dosimetry and shielding applications. |

## Deterministic & lattice codes

| Tool | Access | Use case |
| --- | --- | --- |
| [DRAGON](https://www.polymtl.ca/merlin/) | **free, open source** | Deterministic lattice transport (École Polytechnique de Montréal). |
| [DONJON](https://www.polymtl.ca/merlin/) | **free, open source** | Full-core companion solver to DRAGON. |
| SCALE (ORNL) | free via RSICC registration | The US industry-standard suite: depletion, shielding, criticality safety. |

## Nuclear data & processing

| Tool | Access | Use case |
| --- | --- | --- |
| [JANIS](https://www.oecd-nea.org/tools/abstract/detail/nea-1998/) | **free** (OECD NEA) | Browse and plot evaluated nuclear data (cross sections, spectra) — the fastest way to *see* Module 02's concepts. |
| [NJOY21](https://github.com/njoy/NJOY21) | **free, open source** | Processes ENDF evaluations into usable libraries. |
| ENDF/B-VIII.0, JEFF-3.3, JENDL-5 | **free** | The major evaluated nuclear data libraries (see [data-databases.md](data-databases.md)). |

## Activation, shielding & utilities

| Tool | Access | Use case |
| --- | --- | --- |
| FISPACT-II (UKAEA) | free for research | Activation and transmutation inventory calculations. |
| [PyNE](https://pyne.io/) | **free, open source** | "Python for Nuclear Engineering" — data handling, meshing, activation, glue code. |
| IAEA educational reactor simulators | free on request | Simplified plant simulators used in IAEA training courses. |

## How to choose

- **Learning reactor physics?** OpenMC — open, scriptable, great tutorials.
- **Assembly/lattice homework?** Serpent or DRAGON (academic access).
- **Industry criticality/shielding?** MCNP or SCALE (RSICC registration).
- **Medical/space dosimetry?** Geant4 or FLUKA.

> Note: MCNP, SCALE, and some others involve export-control registration — as a student or researcher you can generally obtain them legitimately; plan a few weeks for paperwork.

[← back to the library](README.md)
