# Parametric CAD Modeling & Assembly of a Toy Airplane

## Image

| Main Assembly |
|---|
| <img src="/AIRPLANE image.png" width="350" alt="Airplane Assembly"/> |

---

## Overview
This project focuses on the feature-based parametric 3D modeling and mechanical assembly of a multi-part biplane using Onshape. Modeled entirely from technical engineering drawings, the project replicates a classic toy airplane design while adhering to strict manufacturing layout constraints. The workflow transitions from individual part creation across strategic geometric planes to top-level assembly integration, culminating in a functional, animated mechanical system.

---

## Learning Objectives

* **Engineering Literacy:** Read and interpret detailed engineering and assembly drawings.
* **Parametric Modeling:** Practice a structured workflow for feature-based parametric 3D modeling.
* **Multi-Part Modeling:** Design individual, interlocking parts with precise geometric constraints.
* **Top-Down Assembly:** Utilize Onshape mate features to build a functional, multi-part working model.
* **Mechanism Animation:** Implement and animate rotational mates to demonstrate proper propeller operation.

---

## Bill of Materials (BOM)

The final assembly consists of **10 unique items** and a total of **15 individual components**:

| Item | Component Name | Quantity | Primary Sketch Plane | Key Design Notes / Offsets |
| --- | --- | --- | --- | --- |
| **1** | Body | 1 | TOP Plane | Main fuselage core structure |
| **2** | Wheel Block | 1 | RIGHT Plane | Base housing for the landing gear |
| **3** | Wheel | 2 | RIGHT Plane | Fits onto the axle sub-assembly |
| **4** | Axle | 1 | — | Connects the wheels to the wheel block |
| **5** | Wing | 2 | TOP Plane | Main wings; Offset set to **70 mm** |
| **6** | Strut | 4 | — | Vertical supports connecting the biplane wings |
| **7** | Horizontal Stabilizer | 1 | TOP Plane | Rear tail wing stabilizer |
| **8** | Vertical Stabilizer | 1 | RIGHT Plane | Rear tail fin |
| **9** | Propeller | 1 | FRONT Plane | Front rotor designed for rotational animation |
| **10** | Propeller Pin | 1 | FRONT Plane | Secures the propeller to the main body |

---

## Assembly Architecture

The project is structured into two logical sub-assemblies before integrating into the final top-level assembly to maintain a clean parametric workflow:

### 1. Wing Sub-Assembly

* Consists of the upper and lower **Wings (Item 5)** mapped with a precise **70 mm offset**.
* Rigidly locked using the four **Struts (Item 6)** to establish the classic biplane configuration.

### 2. Wheel Sub-Assembly

* Centers the **Wheel Block (Item 2)** with the **Axle (Item 4)**.
* Mounts both **Wheels (Item 3)** using a precise **0.5 mm clearance offset** to allow realistic mechanical play.

### 3. Final Airplane Assembly

* Integrates the Fuselage **Body**, **Tail Stabilizers**, **Wing Sub-Assembly**, and **Wheel Sub-Assembly**.
* Connects the **Propeller** to the nose via the **Propeller Pin** using a **Revolute Mate**.

---

##  Getting Started in Onshape

1. **Part Studio:** Build each component utilizing the specific orientation planes listed in the BOM table to ensure seamless mating later.
2. **Mating:** Use `Fastened Mates` for static joints (Body to Stabilizers, Struts to Wings) and `Revolute Mates` for dynamic parts.
3. **Animation:** * Right-click the **Propeller Revolute Mate** in your Assembly features list.
* Select **Animate**.
* Set your steps and loop style to view the propeller in proper operation!

---

### **Key Takeaways & Next Steps**

* **What went well:** The modular sub-assembly approach saved hours of troubleshooting constraints at the top level.
* **What I learned:** Parametric design isn't just about drawing shapes; it’s about anticipating how those shapes interact mechanically in a 3D coordinate space.

## Author
Pramis Kunwar
