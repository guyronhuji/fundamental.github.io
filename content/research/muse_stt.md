# MUSE (MUon Scattering Experiment)
<img style="float: right;" src="/images/MUSE/Platform.jpg" alt="The MUSE Platform" width="200"/>

## Why MUSE?
The **MUSE** experiment measures elastic scattering of **muons and electrons (both charges)** from protons at low momenta. By comparing $ \mu^\pm p $ and $ e^\pm p $ cross sections and angular distributions in a common apparatus, MUSE tests **lepton universality**, quantifies **two‑photon–exchange** effects, and extracts the **proton charge radius** from space‑like momentum transfers. This precision, low‑energy approach complements high‑energy collider searches by probing tiny deviations from the Standard Model through nucleon structure.

## Where and how
- **Facility.** Paul Scherrer Institute (PSI), using mixed secondary beams that deliver $e^\pm$ and $\mu^\pm$ at multiple settings (order‑100–200 MeV/$c$).  
- **Method.** Simultaneous running with positive/negative **muons and electrons** on a hydrogen target. Common detectors and shared systematics enable direct $\mu/e$ and $+/−$ comparisons to isolate two‑photon exchange and radiative effects.  
- **Key observables.** Differential cross sections vs. scattering angle; global fits to electric form factor $G_E(Q^2)$ and the **slope at $Q^2\!\to\!0$** to extract the proton radius.

---

## Detector overview
A simplified view of the MUSE detector stack:
1. **Beam definition and identification.** Scintillators and Cherenkov detectors tag particle species and timing; beamline trackers (e.g., GEMs) measure incident trajectories.
2. **Hydrogen target.** Thin‑walled cryogenic **liquid‑hydrogen (LH$_2$)** cell minimizes multiple scattering while providing adequate luminosity.
3. **Scattered‑particle tracking.** **Straw Tube Trackers (STTs)** arranged cylindrically around the target reconstruct angles and vertices with high efficiency at low material budget.
4. **Trigger & PID.** Segmented scintillator hodoscopes and time‑of‑flight; auxiliary Cherenkov as needed for $e/\mu/\pi$ control.

---

## Highlight: HUJI Straw Tube Tracker (STT)

The **Hebrew University of Jerusalem (HUJI)** group led the **design, prototyping, construction, and integration** of the cylindrical **STT** system for MUSE. The STT is central to achieving sub‑mrad angular precision at very low $Q^2$.

### Design principles
- **Low mass, high rate capability.** Thin **Mylar straws** with light support frames limit multiple scattering while sustaining PSI rates.  
- **3D reconstruction.** **Multiple concentric layers** with axial and **stereo** orientations provide precise polar/azimuthal angle measurement and vertexing at the target.  
- **Robust operations.** Common gas (e.g., Ar/CO$_2$–based), stable high‑voltage distribution, and modular front‑end readout (time‑over‑threshold and drift time) for reliable calibration.

### Mechanical & electronics implementation (HUJI)
- **Module fabrication.** HUJI designed the **end‑plates**, jigs, and stringing procedures for uniform wire tension and straightness; modules are **pre‑aligned** on precision fixtures to ease integration around the LH$_2$ cryostat.  
- **Quality control.** Each straw underwent **leak‑rate**, dark‑current, and gain‑uniformity tests; cosmic‑ray stands validated single‑hit efficiency and drift‑time linearity before shipment.  
- **Readout & DAQ integration.** HUJI implemented the **front‑end boards**, timing/trigger interfaces, and slow‑controls for **gas and HV**, integrating the STT into the experiment‑wide DAQ and run‑control.  
- **Commissioning.** At PSI, HUJI coordinated survey/alignment, established **space‑time (x–t) calibrations**, and performed early‑physics validation with elastic peaks and vertex distributions.

### Performance (typical for well‑tuned STTs)
- **Single‑hit efficiency:** $>\!95\%$ across active area under nominal beam conditions.  
- **Spatial (drift) resolution:** order **100–150 µm** per straw; multi‑layer fits achieve **sub‑mrad** angular precision.  
- **Material budget:** a **few $10^{-3}\,X_0$** per layer to control multiple scattering at low momenta.

These capabilities are essential for the small‑angle, low‑$Q^2$ regime where the proton‑radius sensitivity is maximized and where systematic control—alignment, multiple scattering, and radiative tails—dominates the error budget.

---

## Analysis strategy
1. **Track & vertex fits** from STT hits; beam‑track extrapolation to the target for vertex matching.  
2. **Acceptance & resolution corrections** from detailed GEANT‑based simulations and STT $x$–$t$ calibrations.  
3. **Radiative corrections & two‑photon exchange** evaluated comparatively with $\mu^\pm$ vs. $e^\pm$; common‑mode systematics cancel in ratios.  
4. **Global form‑factor fits** at low $Q^2$ to extract $r_E$ and to test lepton‑universality and TPE hypotheses.

---

## HUJI roles in MUSE
- **STT system**: concept, mechanical design, construction, QC, and operations.
- **Run coordination & calibrations** for tracking and alignment.
- **Simulation and systematics**: multiple scattering studies, acceptance modeling, and cross‑checks for the radius extraction.

---

