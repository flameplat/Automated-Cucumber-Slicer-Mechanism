  # Automated Cucumber Slicer Mechanism
  ### Mechatronics Lab Project | German University in Cairo | Winter 2025

  > A fully automated electro-pneumatic food processing machine — designed,
  modeled, and physically built from scratch.

  ---

  ## Overview

  This project is an **industrial-grade automated cucumber slicer** developed as
   part of the Mechatronics Lab course (MCTR704) at GUC. The machine detects,
  positions, slices, and ejects cucumbers without any manual intervention —
  driven entirely by pneumatic actuators and a relay-based electro-pneumatic
  control circuit.

  The project covered the **full engineering lifecycle**: concept → 3D CAD
  design → 2D manufacturing drawings → control logic → physical hardware
  assembly and final operation.

  ---

  ## Media

  > Photos, videos, and CAD screenshots of the build process and final working
  machine.

  **[View Project Media on Google Drive](https://drive.google.com/drive/folders/1exFpOgrfdLZzJ8KUXEO8ME1OVfXH9eRG?usp=share_link)**

  ---

  ## How It Works

  The system operates in a continuous, sensor-triggered loop:

  1. **Detect** — A photoelectric sensor detects a cucumber at the bottom of the
   magazine
  2. **Feed** — Cylinder A (250mm stroke) pushes the cucumber into the slicing
  position
  3. **Slice** — Cylinder B (150mm stroke) drives a multi-blade plate vertically
   through the cucumber
  4. **Eject** — Cylinder C (100mm stroke) pushes the sliced pieces onto the
  collection tray
  5. **Reset** — All cylinders retract and the cycle repeats automatically

  The timing and sequencing of all three cylinders is governed by a **relay 
  ladder circuit** operating at 24V DC.

  ---

  ## Technical Highlights

  | Domain | Tools & Techniques |
  |---|---|
  | 3D Modeling | SolidWorks (full assembly + individual parts) |
  | 2D Manufacturing Drawings | SolidWorks Drawings with dimensions |
  | Small Part Fabrication | Laser cutting (DXF/DWG files) |
  | Frame Construction | Custom-built wooden frame (carpenter workshop) |
  | Control Logic | Electro-pneumatic relay circuit (FluidSim) |
  | Sensing | Photoelectric Sensor |
  | Actuation | 3× Double-acting pneumatic cylinders |

  ---

  ## System Components

  | # | Component | Function |
  |---|---|---|
  | 1 | Piston Cylinder — 250mm | Feeds cucumber from magazine to cutting zone |
  | 2 | Piston Cylinder — 150mm | Drives the vertical cutting blade |
  | 4 | Photoelectric Sensor | Detects cucumber presence at magazine exit |
  | 5 | Solenoid Valves (×3) | Control airflow to each cylinder |
  | 6 | Relay Control Panel | Classic ladder-logic sequencing at 24V DC |
  | 7 | Wooden Structural Frame | Carpenter-built housing for all components |
  
  ---
  
  ## Project Deliverables
  
  - [x] SolidWorks 3D Assembly Model
  - [x] 2D Engineering Drawings with Full Dimensions
  - [x] Pneumatic Step Diagram (A+/A-/B+/B-/C+/C- sequence)
  - [x] Electro-Pneumatic Circuit (FluidSim)
  - [x] Laser Cut Files for Small Parts (DXF/DWG)
  - [x] Physical Hardware Build — Fully Operational
  
  ---
  
  ## Skills Demonstrated
  
  `SolidWorks` `AutoCAD` `Pneumatic Systems` `Electro-Pneumatic Control` `Relay
  Logic` `FluidSim` `Laser Cutting` `Mechanical Design` `Systems Integration`
  `Hardware Prototyping`
  
  ---
  
  ## Team
  
  **Ahmed Reda Ebada** — German University in Cairo, Mechatronics Engineering
  **Ahmed Elafandy** — German University in Cairo, Mechatronics Engineering
  Group 36 | MCTR704 | Winter 2025

  ---
