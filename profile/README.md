<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RoperaLabs/.github/main/assets/logo-dark.png">
    <img src="https://raw.githubusercontent.com/RoperaLabs/.github/main/assets/logo-light.png" alt="Ropera Labs" width="280">
  </picture>
</p>

<p align="center"><b>Distributed systems and C4ISR for degraded networks: swarm coordination, command and control, on-premise.</b></p>

---

**Ropera Labs** is an independent R&D lab building open, reproducible software for distributed autonomy and command and control. Our design condition is the network you actually get in the field: **disconnected, intermittent and limited (DIL)**, with no cloud to fall back on. We measure results in mission terms, not lab benchmarks.

### Research lines

- **Distributed control of uncrewed systems**: coordination of swarms and multi-layer teams (hierarchical, heterogeneous UAV/UGV/USV, one operator for many vehicles, human-machine teaming).
- **On-premise and distributed C4ISR**: command and control, data fusion and a common operational picture that keep working without the cloud and over degraded links, speaking open standards (CoT/TAK, C2SIM, MAVLink, ROS 2).

### Latest finding

**[swarm-dil](https://github.com/RoperaLabs/swarm-dil)** v0.3, **GRACE**: a communication protocol derived, not copied, for agents with a vision cone, a few hundred bytes of memory and short, fading radio links that must cross unknown terrain from A to B. Each agent runs it on board, knowing only what it senses and what teammates tell it. It sends only what changes a teammate's decision: the same detour as flooding with **~3× fewer bytes**, and unlimited-memory performance with **64 bytes of map memory**, where flooding becomes worse than silence. [Technical report](https://roperalabs.github.io/swarm-dil/theory/theory.pdf) · [interactive explainer](https://roperalabs.github.io/swarm-dil/).

<p align="center"><img src="https://raw.githubusercontent.com/RoperaLabs/swarm-dil/main/docs/theory/fig/pareto.png" alt="Bytes sent against detour: GRACE, flooding and silence" width="560"></p>

### Open research

| Project | Relevance | Stack |
|---|---|---|
| [swarm-dil](https://github.com/RoperaLabs/swarm-dil) | Coordination and communication of memory- and bandwidth-limited UAV teams over degraded links: GRACE protocol with proofs and on-device simulation (v0.3); area search under a physical radio, terrain and interference (v0.2); Cursor on Target replay for TAK | Python, NumPy, SciPy, LaTeX |
| [boids-flocking](https://github.com/RoperaLabs/boids-flocking) | Decentralised flocking model and order-disorder experiment: a baseline for UxV swarm coordination | Python, NumPy |
| [physarum-network-design](https://github.com/RoperaLabs/physarum-network-design) | Slime-mould-inspired network design benchmarked against classical baselines: resilient, low-cost network topologies | Python |
| [population-dynamics-evolution](https://github.com/RoperaLabs/population-dynamics-evolution) | Agent-based evolutionary simulation with multi-seed experiments: methodology for large-scale ABM studies | Python, NumPy |

### Principles

- **Unclassified by design**: public repositories contain only open research built on synthetic or publicly available data.
- **Human oversight**: autonomy is built to support human decision-makers, not replace them.
- **Compliance**: we operate within applicable law, including export-control and dual-use regulations.
- **Reproducibility**: every result ships with seeds, method and evaluation, and runs on a single laptop.
- **Hardware-agnostic**: software first, standard interfaces, simulation-validated.

### Contact

[roperalabs@gmail.com](mailto:roperalabs@gmail.com)
