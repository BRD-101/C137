
**Student:** Brian Dillion  
**Course:** Intro Artificial Intelligence (11122) 
**Institution:** Columbus State Community College  
**Date:** March 2026

---

## AI and Emerging Technologies

### a. What emerging technology did you choose? How is AI being used to support it?

The emerging technology I chose is **AI-powered predictive maintenance in commercial aviation**.
Airlines and MRO (Maintenance, Repair & Overhaul) operators are now using machine learning
models trained on engine sensor data, flight cycles, and historical fault records to predict
component failures before they occur. Platforms receives real-time data from sources like ACARS
and onboard health monitoring systems to flag anomalies and recommend maintenance actions
shifting the industry from scheduled maintenance intervals toward true condition-based maintenance.
The data is typically transmitted via satellite data link but also through ground based transponding.

---

### b. What previous solutions were being used in place of AI? How has AI replaced or will soon replace these solutions?

Prior to AI, aviation maintenance relied almost entirely on **hard-time and on-condition
maintenance programs** defined by the aircraft manufacturer's Maintenance Planning Document (MPD).
Technicians and engineers manually reviewed component life tracking spreadsheets, squawk logs,
and scheduled inspection intervals to make go/no-go decisions. These systems were reactive by
design a component was replaced when it hit a calendar limit or showed a measurable defect,
not because a failure was anticipated.

AI is replacing this model by continuously analyzing thousands of data points per flight and
surfacing patterns invisible to human review, enabling operators to:

- Reduce unscheduled component removals
- Lower AOG (Aircraft on Ground) events and associated revenue losses
- Optimize parts inventory with far greater precision than traditional reliability programs
- Shift maintenance planning from fixed intervals to true condition-based actions

---

### c. Briefly describe the type of AI being used for this technology

The primary AI type used in aviation predictive maintenance is **Machine Learning (ML)**,
specifically supervised and unsupervised learning models trained on historical engine and
airframe sensor data.

**Supervised learning** models are trained on labeled datasets of known failure events,
teaching the system to recognize the data signatures that precede a specific fault
for example, rising exhaust gas temperature (EGT) trends preceding a hot section
inspection requirement on a turbofan engine. This is my primary focus.

**Unsupervised learning** is used for anomaly detection, identifying sensor patterns
that deviate from normal operating parameters without needing a pre-labeled failure
event as a reference point. This is particularly valuable for novel fault modes not
well represented in historical data.

Some platforms also incorporate **Natural Language Processing (NLP)** to mine
unstructured data sources such as pilot squawks, maintenance logbook entries, and
technical dispatch reports, extracting failure signals from free-text records that
would otherwise be invisible to numeric models alone.
