**Student:** Brian Dillion  
**Course:** WIIT-7810 - Introduction to Artificial Intelligence  
**Institution:** Columbus State Community College  
**Date:** March 2026

---

## The Seven Steps of Machine Learning

Machine learning follows a seven-step process to turn raw data into useful predictions. Two of the most critical steps are:

**Step 1: Data Collection**

The system needs raw material to learn from. In aviation terms, this is every sensor reading, maintenance log, and flight record from your fleet. Quality matters. Poor data produces unreliable results. Autonomous data links to the aircraft systems allow this data in a standard format with no human error, as was the case prior to the availability of digital data.    

**Step 4: Training**

The algorithm processes the collected data, identifies patterns, and adjusts itself repeatedly until its accuracy reaches an acceptable level. Think of it as the system reviewing thousands of past engine failures to learn which sensor readings preceded each event. the system can recognize those patterns in real time going forward. The inclusion of sensors in component designs in the current generation of aircraft allows for the monitoring of vast number of components on the aircaft such as hydraulic pumps and actuators, and valve motor health.   

> Source: WIIT-7810 Course Slides, Machine Learning Part 1, Columbus State Community College

---

## Machine Learning Application: Predictive Maintenance in Commercial Aviation

Traditional aviation maintenance follows fixed time or cycle based intervals, "HARD TIME". The component reaches the prescribed limit and it is a "hard stop" for that component. Conservative by design but costly and inefficient. Machine learning replaces this with condition-based intervention driven by live sensor data.

Delta TechOps' APEX (Advanced Predictive Engine) system demonstrates the impact at scale. With a success rate of over 95% for pending failure predictions, the results are measurable:

| Year | Maintenance-Related Cancellations |
|------|----------------------------------|
| 2010 | 5,600+ |
| 2018 | 55 |

This application is actively deployed across the industry. Air France-KLM partnered with Google Cloud in December 2024, reducing data analysis time for predictive maintenance from hours to minutes.

---

## Ethical Concern

Accountability is unresolved. When an ML model recommends deferring a maintenance action and a failure follows, liability is unclear, was it the algorithm, the data, the operator, or the MRO provider? FAA and EASA regulations were not designed for algorithmic decision-making and are slow to change. This gap remains open. Incorporating AI into aviation requires collaboration with regulatory bodies to align these applications with existing safety frameworks and also drive for regulatory change to include this evolution of mainteance philosphy.

---

## References

1. Delta TechOps. (2019). *Delta TechOps expanding predictive maintenance capabilities with new Airbus partnership.* https://deltatechops.com/delta-techops-expanding-predictive-maintenance-capabilities-with-new-airbus-partnership/
2. Acumen Aviation. (2024). *The role of AI in aircraft maintenance.* https://www.acumen.aero/blogs/the-role-of-ai-and-predictive-analytics-in-aircraft-maintenance
3. WIIT-7810 Course Slides. (2025). *Machine Learning Part 1.* Columbus State Community College.

---
