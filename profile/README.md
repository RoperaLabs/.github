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

**[swarm-dil](https://github.com/RoperaLabs/swarm-dil)**: across 3,600 simulated search missions with 20 UAVs, losing half of all messages in 10-second bursts makes a centrally coordinated swarm **3.6× slower** to find every target, while a mesh-coordinated swarm slows by only **1.16×**. Beyond 10-20 % message loss, central coordination is already slower than not communicating at all.

<p align="center"><img src="https://raw.githubusercontent.com/RoperaLabs/swarm-dil/main/results/search_dil.gif" alt="Three swarm coordination strategies searching an area over a degraded network" width="720"></p>

### Open research

| Project | Relevance | Stack |
|---|---|---|
| [swarm-dil](https://github.com/RoperaLabs/swarm-dil) | UAV swarm search over DIL links: centralised, decentralised and no-comms coordination compared on mission metrics; Cursor on Target replay for TAK | Python, NumPy |
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
