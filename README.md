# Lost Cast Wax 3D Printing

**Fabricating intricate, miniature soft robots in a single shot of molding**, using 3D-printed lost-wax molds instead of machined or multi-part rigid molds.

## Overview

Lost-cast wax molding uses a 3D-printed wax (or wax-like) core to define intricate, often multi-channel internal geometries that would be difficult or impossible to demold conventionally. The wax mold is cast around, then melted/dissolved out, leaving behind a single-shot soft robotic actuator or sensor with fine internal detail and no assembly step.

This repository collects the CAD files, molds, and assemblies developed for this process. **The work is in progress** — these are the basic designs we have so far, covering both single-material and multi-material actuators.

## Repository contents

```
Lost-Cast-Wax-3D-Printing/
└── Mold Designs/
    ├── Single Material/
    │   ├── Antagonistic Actuator/         # 2-channel antagonistic bending actuator
    │   ├── 3 Channel Actuator/            # 3-channel actuator
    │   ├── Twisting Actuators/            # Single- and double-channel twisting actuators
    │   ├── Origami Vacuum Actuator/       # 3-channel origami-based vacuum actuator
    │   ├── Kresling Origami/              # Kresling-pattern origami actuator
    │   ├── Hilbert Fluid Sensor/          # Fluid-based tactile sensor (Hilbert-curve channel)
    │   └── Popping Actuator/              # Snap-through "popping" dome actuator
    └── Multi Materials/
        ├── Bending Actuators/             # Multi-material bending actuator
        ├── Contracting Actuator/          # Multi-material contracting actuator
        ├── Elongating/                    # Multi-material elongating actuator
        └── Twisting Actuator/             # Multi-material twisting actuator
```

Each design folder generally includes:
- The **actuator part** (`.SLDPRT`) — the target geometry to be cast
- The **mold part** (`.SLDPRT` / `.STL`) — the 3D-printable wax mold
- An **assembly file** (`.SLDASM`) showing actuator and mold together

## Requirements

- SolidWorks (to open `.SLDPRT` / `.SLDASM` files)
- A 3D printer capable of printing wax or a sacrificial/dissolvable material (for the mold)
- Standard soft-robotics casting materials (e.g., silicone) for the actuator body

## Status

This is an active, ongoing project. Designs and documentation will continue to be added as the fabrication process is developed further.

## Related work

This process builds on techniques used in our other soft-robotics fabrication project, [Weld n'Cut](https://github.com/Arman-Goshtasbi/Weldn-cut), for automated textile-actuator fabrication.
