## Parametric CAD Modeling & Assembly of a Toy Airplane

### Overview

This project focuses on the feature-based parametric 3D modeling and mechanical assembly of a multi-part biplane using **Onshape**. Modeled entirely from technical engineering drawings, the project replicates a classic toy airplane design while adhering to strict manufacturing layout constraints. The workflow transitions from individual part creation across strategic geometric planes to top-level assembly integration, culminating in a functional, animated mechanical system.

---

###  Key Learning Objectives & Milestones

* **Engineering Print Reading:** Interpreted detailed engineering blueprints and exploded-view assembly drawings to accurately map dimensions and parts.
* **Parametric Part Design:** Developed 10 unique, interlocking components by selecting optimal primary sketch planes (TOP, RIGHT, and FRONT) to establish seamless assembly alignment.
* **Top-Down & Sub-Assembly Architecture:** Structured the project into modular sub-assemblies (Wing and Wheel systems) to maintain a clean feature tree and simplify top-level integration.
* **Mechanical Kinematics & Animation:** Utilized advanced mating constraints, including `Fastened Mates` for structural rigidity and `Revolute Mates` to simulate and animate realistic propeller rotation.

---

### Technical Specifications & Assembly Architecture

The project encompasses **15 total components** organized into a clean hierarchical structure:

* **The Airframe Core:** The central fuselage (**Body**) serves as the base anchor, rigidly mated to the **Horizontal Stabilizer** (TOP plane) and **Vertical Stabilizer** (RIGHT plane).
* **Wing Sub-Assembly:** Features a biplane configuration utilizing two **Wings** precisely constrained with a **70 mm vertical offset**, structurally locked together by four interlocking **Struts**.
* **Landing Gear Sub-Assembly:** Centers a **Wheel Block** with an **Axle** to mount two independent **Wheels**, incorporating a **0.5 mm clearance offset** to emulate mechanical play and prevent physical interference.
* **Propulsion System:** Houses a front-facing **Propeller** secured to the fuselage nose via a **Propeller Pin**, engineered with a functional rotational axis.

---

### Tools & Technologies Used

* **CAD Platform:** Onshape (Cloud-Based Parametric Modeling)
* **Core Modeling Techniques:** Extrusions, Revolves, Complex Offsets, and Geometric Sketch Constraints.
* **Assembly Mechanics:** Mates (Fastened, Revolute), Sub-Assembly Nesting, and Kinematic Motion Animation.
