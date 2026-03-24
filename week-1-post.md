# GitHub Learning Portfolio
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
component failures before they occur. Platforms ingest real-time data from sources like ACARS
and onboard health monitoring systems to flag anomalies and recommend maintenance actions —
shifting the industry from scheduled maintenance intervals toward true condition-based maintenance.

---

### b. What previous solutions were being used in place of AI? How has AI replaced or will soon replace these solutions?

Prior to AI, aviation maintenance relied almost entirely on **hard-time and on-condition
maintenance programs** defined by the aircraft manufacturer's Maintenance Planning Document (MPD).
Technicians and engineers manually reviewed component life tracking spreadsheets, squawk logs,
and scheduled inspection intervals to make go/no-go decisions. These systems were reactive by
design — a component was replaced when it hit a calendar limit or showed a measurable defect,
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
teaching the system to recognize the data signatures that precede a specific fault —
for example, rising exhaust gas temperature (EGT) trends preceding a hot section
inspection requirement on a turbofan engine.

**Unsupervised learning** is used for anomaly detection — identifying sensor patterns
that deviate from normal operating parameters without needing a pre-labeled failure
event as a reference point. This is particularly valuable for novel fault modes not
well represented in historical data.

Some platforms also incorporate **Natural Language Processing (NLP)** to mine
unstructured data sources such as pilot squawks, maintenance logbook entries, and
technical dispatch reports — extracting failure signals from free-text records that
would otherwise be invisible to numeric models alone.

---

### d. How does the use of AI and this technology affect everyday life?

The impact of AI-driven aviation maintenance extends well beyond the hangar:

**For passengers**, the most direct effect is improved safety and reliability. Fewer
mechanical delays, reduced cancellations, and lower risk of in-flight anomalies all
trace back to better component monitoring. Aviation already has an exceptional safety
record — AI is pushing that standard even higher.

**For airline employees**, AI tools are changing the nature of maintenance work.
Technicians increasingly work alongside AI-generated work orders and fault predictions
rather than relying solely on scheduled inspection cards. This demands new skills —
data literacy alongside traditional mechanical expertise.

**For the broader economy**, aviation is a critical infrastructure layer. Reduced AOG
events and optimized maintenance scheduling translate directly into fewer disrupted
supply chains, lower cargo delays, and more predictable air travel — effects that
ripple across industries dependent on reliable air transport.

**For developing aviation markets**, AI lowers the barrier to sophisticated maintenance
operations. Smaller carriers in regions with limited MRO infrastructure can access
fleet health intelligence that previously required large engineering departments.

---

### e. Are there any concerns with using AI for this application?

Yes — several significant concerns exist and deserve serious consideration:

**Data quality and bias**: AI models are only as good as the data they are trained on.
Historical maintenance records in aviation are often incomplete, inconsistently coded,
or biased toward well-documented failure modes. A model trained on incomplete data may
generate false confidence in fleet health or miss failure signatures for rare but
catastrophic fault types.

**Regulatory and certification challenges**: Aviation is one of the most heavily
regulated industries in the world. AI-generated maintenance recommendations currently
operate in a gray zone — FAA and EASA frameworks were not designed with autonomous
AI decision-making in mind. Certification pathways for AI-assisted airworthiness
decisions are still being developed, creating compliance uncertainty for operators.

**Over-reliance and skill erosion**: As AI systems become more capable, there is a
genuine risk that human technicians and engineers lose the deep diagnostic intuition
built through years of hands-on experience. If an AI system fails or produces an
erroneous recommendation, the human backstop must still be capable of independent
judgment — that capability must be actively maintained.

**Cybersecurity**: Aviation maintenance platforms connected to real-time aircraft data
streams represent high-value targets. A compromised predictive maintenance system could
suppress legitimate fault alerts or generate false ones — with potentially serious
safety consequences.

**Transparency and explainability**: Many high-performance ML models operate as
"black boxes," producing recommendations without clear reasoning. In an industry where
every maintenance action must be documented and defensible under regulatory audit,
explainability is not optional — it is a compliance requirement.

---

> *"The goal is not to replace the experienced aviation professional — it is to give them
> tools that make their expertise more powerful, their decisions better informed, and the
> traveling public safer."*

---
