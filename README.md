# CAD-models-project-
Mechanical 3D CAD portfolio featuring manufacturing-ready STEP (AP214) &amp; watertight STL assemblies, DFM/kinematic validation, and photorealistic PBR renders.
# Mechanical CAD & DFM Engineering Portfolio

# Precision Mechanical CAD & DFM Engineering Dossier

**Parametric 3D solid modeling, production-ready `.STEP` (AP214) & watertight `.STL` assemblies, automated geometric interference verification, and photorealistic 4K studio PBR raytracing.**

---

## 📌 Featured Mechanical Assemblies

### 01. Precision 3-Jaw CNC Lathe Power Chuck (Scroll-Actuated Assembly)

* **Directory:** [`./Project1`](./Project1)
* **CAD Deliverables:** [`Assembled.step`](./Project1/Assembled.step), [`Exploded.step`](./Project1/Exploded.step), [`Assembled.stl`](./Project1/Assembled.stl), [`Exploded.stl`](./Project1/Exploded.stl)
* **Envelope & Mass:** $\varnothing\ 160.0\text{ mm} \times 74.0\text{ mm}$ (assembled height), $112.5\text{ mm}$ maximum jaw reach span; `1.842 kg` (AISI 4140 Alloy Steel & C36000 Brass).
* **Engineering Highlights:**
  * **Actuation Mechanism:** Archimedean flat scroll plate driving 3 radial master jaws with self-centering synchronization ($120^\circ$ radial indexing).
  * **Jaw Interface:** Standard serrated master jaw base with stepped reversible soft jaws, secured via counterbored high-tensile socket head cap screws.
  * **Clearances & DFM:** $0.05\text{ mm}$ diametral slide guide clearance; $0.08\text{ mm}$ axial running play on scroll backface; $1.5\text{ mm} \times 45^\circ$ lead-in chamfers on outer periphery; internal bore relief for spindle bar feeder clearance.
* **Validation:** Watertight binary STL; 6 verified solids; **$0.000000\text{ mm}^3$ interference** across all paired components in static clamping configuration.

![Project 1 Exploded Render](./Project1/IMG-20261117-WA0024.jpg)

---

### 02. Precision 6-Slot Maltese Cross Geneva Indexing Drive (6-Solid Assembly)

* **Directory:** [`./Project2`](./Project2)
* **CAD Deliverables:** [`P02_Assembled.step`](./Project2/P02_Assembled.step), [`P02_Exploded.step`](./Project2/P02_Exploded.step), [`P02_Assembled.stl`](./Project2/P02_Assembled.stl), [`P02_Exploded.stl`](./Project2/P02_Exploded.stl)
* **Kinematics & Envelope:** 6-station intermittent motion ($60^\circ$ dwell-to-index ratio); Envelope: $165.0\text{ mm} \times 95.0\text{ mm} \times 42.0\text{ mm}$; `1.667 kg` (6061-T6 Aluminum, 4140 Steel, C36000 Brass, 304 Stainless Steel).
* **Engineering Highlights:**
  * **Intermittent Geneva Kinematics:** Center distance $a = 60.0\text{ mm}$, drive crank radius $r = 30.0\text{ mm}$, driven Maltese cross radius $R = 51.96\text{ mm}$ ($a \times \cos(30^\circ)$).
  * **Pin Engagement:** Hardened $\varnothing\ 6.0\text{ mm}$ alloy drive pin engaging with continuous tangential entry arc ($0.04\text{ mm}$ side-wall clearance per slot, zero impact chatter).
  * **Rigid Top Bridge:** $16.0\text{ mm}$ thickness 304 stainless steel tie-bar maintaining rigid rotor/wheel axis parallelity under dynamic indexing torque, locked via twin M8 dowel shoulder bolts.
* **Validation:** $0.000000\text{ mm}^3$ interference across all 15 solid pairs; complete kinematic sweep verification ($0^\circ \to 360^\circ$ continuous engagement cycle); watertight mesh geometry.

![Project 2 Exploded Render](./Project2/IMG-20261118-WA0009.jpg)

---

### 03. Precision Planetary Epicyclic Gear Reducer (3:1 Reduction Stage)

* **Directory:** [`./Project3`](./Project3)
* **CAD Deliverables:** [`P03_Assembled.step`](./Project3/P03_Assembled.step), [`P03_Exploded.step`](./Project3/P03_Exploded.step), [`P03_Assembled.stl`](./Project3/P03_Assembled.stl), [`P03_Exploded.stl`](./Project3/P03_Exploded.stl)
* **Kinematics & Envelope:** 3:1 Speed Reduction ($Z_{\text{sun}} = 9$, $Z_{\text{planet}} = 9$, $Z_{\text{ring}} = 27$, module $m = 3.778\text{ mm}$); Envelope: $\varnothing\ 124.0\text{ mm} \times 58.0\text{ mm}$; `1.529 kg` total assembly mass.
* **Engineering Highlights:**
  * **Gear Mesh Topography:** Module $m = 3.778\text{ mm}$, pitch radii: Sun $R_p = 17.0\text{ mm}$, Planet $R_p = 17.0\text{ mm}$, Internal Ring $R_p = 51.0\text{ mm}$; Planet orbit pitch circle radius $R_{\text{orbit}} = 34.0\text{ mm}$.
  * **Carrier Architecture:** Rigid 304 Stainless Steel 3-pin carrier triad ($120^\circ$ phase angle) with integrated output shaft and rear thrust shoulder.
  * **DFM Clearance Bands:** $0.60\text{ mm}$ radial root clearance; tooth tip radial overlap band $1.20\text{ mm}$; continuous $18\text{ mm}$ clear Z-tier spacing in exploded state for optical DFM inspection.
* **Validation:** $0.000000\text{ mm}^3$ static clash across all 15 solid pairs; $0.000000\text{ mm}^3$ interference across full coupled kinematic sweep ($-3.0^\circ \to +3.0^\circ$); positive mechanical mesh proof confirmed under deliberate angular half-pitch jam ($12.94\text{ mm}^3$ Sun-to-Planet, $79.56\text{ mm}^3$ Planet-to-Ring).

![Project 3 Exploded Render](./Project3/IMG-20261118-WA0010.jpg)
 
