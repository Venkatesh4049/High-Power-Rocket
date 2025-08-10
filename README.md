```markdown
# High-Power Rocket Project

**Design and Development of a High-Power Rocket Using Composite Materials**

This repository documents the design, fabrication, and testing of a student-built high-power rocket using kraft-phenolic composite materials and a KNO₃–glucose style solid propellant (research/educational context). It includes CAD models, simulation files, fabrication instructions, test results, and electronics/avionics resources.

> **Important:** This project is for educational and research purposes only. Rocket motors, propellants, and ejection charges are potentially dangerous and may be restricted or illegal in your jurisdiction. Do not attempt propellant manufacture, motor construction, or launches without appropriate training, permissions, and safety procedures.

---

## Repository structure
```

.
├── README.md
├── LICENSE
├── High\_Power\_Rocket.pdf
├── CAD/
│   ├── solidworks/
│   └── blender/
├── Simulations/
│   ├── OpenRocket/
│   └── OpenMotor/
├── Fabrication/
│   ├── build\_instructions.md
│   └── material\_specs/
├── Propulsion/
│   ├── nozzle\_calcs/
│   └── motor\_data/
├── Recovery/
│   ├── parachute\_patterns/
│   └── ejection\_system/
├── Electronics/
│   ├── schematics/
│   └── firmware/
├── Testing/
│   ├── static\_tests/
│   └── flight\_data/
└── docs/
└── diagrams/

````

---

## Features
- Kraft-phenolic composite structural components (body, fins, nose cone)
- Simulation files for aerodynamic & motor performance (OpenRocket, OpenMotor)
- Nozzle design and motor characterization (documentation only)
- Recovery system design (dual-deployment concept, parachute patterns)
- Avionics: avionics bay layout, sensor list, firmware and data-logging examples
- Testing logs: static test results and validation notes

---

## Quick start
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/high-power-rocket.git
   cd high-power-rocket
````

2. Read the full project report:

   * `High_Power_Rocket.pdf`
3. Open simulation files:

   * Load `.ork` files from `Simulations/OpenRocket/` in **OpenRocket**
   * Load motor data in `Simulations/OpenMotor/`
4. Inspect CAD:

   * `CAD/solidworks/` or `CAD/blender/` contain 3D models and exports.
5. Review fabrication steps:

   * `Fabrication/build_instructions.md` (contains tooling, tolerances, and finish steps)

---

## Safety & legal

* Follow national/regional laws for rocket motors and launches.
* Perform propellant or motor work only under qualified supervision & at approved facilities.
* Wear appropriate PPE and follow documented safety protocols for static tests.

---

## Contributing

1. Fork the repo and create a feature branch.
2. Add or update files (keep file naming consistent).
3. Submit a PR with a clear description of changes and test evidence (if applicable).

---

## License

This project is released under the **MIT License**. See `LICENSE` for details.

---

## Authors / Contact

Project team: Venkatesh A M and collaborators (see `High_Power_Rocket.pdf` for full credits).
For repo issues or contribution requests, open an issue or PR on GitHub.

---

```


```
