# CERN RPC-BIL Prototype Study
[![DOI](https://img.shields.io/badge/DOI-10.17181%2Fhnh3m--re005-blue)](https://doi.org/10.17181/hnh3m-re005)

**Test of the first RPC-BIL prototype in view of the Mechanics Final Design Review**

CERN Summer Student project investigating the first **RPC-BIL prototype** for the ATLAS Muon Spectrometer upgrade.

> **Author:** Jessica Dichakdjian  
> **Supervisors:** Alessandro Rocchi & Alessia Bruni  
> **CERN Summer Student Programme:** 2023  
> **CERN publication:** CERN-STUDENTS-Note-2023-118

---

## Project Overview

This work was carried out in the context of the **High-Luminosity LHC upgrade** and the corresponding upgrade of the ATLAS muon trigger system.

The new Barrel Inner RPC system introduces new-generation Resistive Plate Chambers intended to improve trigger acceptance, redundancy, tracking performance and timing capability. :chatgpt-content-reference{index="0"}

My Summer Student project focused on experimental characterization of the first **RPC-BIL mechanical prototype** in preparation for the Mechanics Final Design Review.

---

## Study Objectives

The experimental work investigated whether the detector mechanical structure could preserve suitable RPC operation even under abnormal gas-volume conditions.

The study included:

- RPC-BIL prototype testing
- signal propagation along detector strip lines
- time-of-flight based hit-position reconstruction
- spatial-resolution characterization
- detector-uniformity measurements
- comparison of measurements at **0 mbar** and **+2 mbar** gas-volume overpressure
- comparison of experimental hit distributions with simulation

The prototype was intentionally tested with one electrode partially detached from its internal pillars in order to study the effectiveness of the mechanical containment structure. :chatgpt-content-reference{index="1"}

---

## Experimental Setup

The detector was tested using scintillators as the trigger system and a **CAEN V1190A Time-to-Digital Converter** for data acquisition.

The strip-line timing information was used to reconstruct particle-hit positions along the detector. :chatgpt-content-reference{index="2"}

Two principal pressure configurations were investigated:

```text
0 mbar
+2 mbar
```

Hit-rate uniformity was then compared with simulated distributions. :chatgpt-content-reference{index="3"}

---

## Key Results

### Strip-Line Signal Propagation

The measured average signal propagation velocity along the strip lines was:

```text
20.7 cm/ns
```

This value provides the scale factor required to convert timing information into reconstructed hit position. :chatgpt-content-reference{index="4"}

### Spatial Resolution

The measurements established an approximate upper limit on spatial resolution of:

```text
~2 cm
```

:chatgpt-content-reference{index="5"}

### Detector Uniformity

Non-uniformities were observed in the detector hit maps.

However, the measurements indicated that these discrepancies were **not associated with either the trigger configuration or the applied overpressure**. Their origin remained under investigation. :chatgpt-content-reference{index="6"}

---

## Publication

The complete report is publicly available through the CERN Document Server / CERN Repository:

**Test of the first RPC-BIL prototype in view of the Mechanics Final Design Review**

CERN-STUDENTS-Note-2023-118  
Jessica Dichakdjian, 2023

Official CERN record:

https://repository.cern/records/hnh3m-re005

DOI:

https://doi.org/10.17181/hnh3m-re005

Google Scholar:

https://scholar.google.com/citations?view_op=view_citation&hl=en&user=690OirMAAAAJ&citation_for_view=690OirMAAAAJ:u5HHmVD_uO8C

---

## Skills & Topics

This work involved:

- particle-detector instrumentation
- Resistive Plate Chambers (RPC)
- ATLAS Muon Spectrometer
- experimental detector testing
- time-of-flight measurements
- spatial reconstruction
- data acquisition
- detector uniformity analysis
- experimental data analysis
- comparison with simulation
- high-energy physics instrumentation

---

## Context

This repository is intended as a concise portfolio reference for my **2023 CERN Summer Student work**.

The complete technical documentation and results are preserved in the official CERN publication rather than duplicated here.
