# Flue-Gas Analysis Fundamentals

A general learning guide to common combustion and flue-gas measurements. It is not manufacturer-specific documentation and does not replace the analyser manual, local regulations, or competent combustion-safety procedures.

## Typical parameters

| Parameter | Common unit | Why it matters | Important caveat |
|---|---|---|---|
| Oxygen (O₂) | % vol | Helps assess residual oxygen and excess air | Interpret with fuel, appliance, and test conditions |
| Carbon monoxide (CO) | ppm or mg/m³ | Indicates incomplete combustion and may be safety-critical | Follow approved safety procedures; do not rely on one reading alone |
| Carbon dioxide (CO₂) | % vol | Supports combustion interpretation | May be measured or calculated depending on instrument/method |
| Nitrogen oxides (NO / NO₂) | ppm or mg/m³ | Relevant to combustion emissions | Sensor capability and sampling method vary |
| Flue-gas temperature | °C | Helps characterise operating conditions | Probe location and response affect results |
| Draught / pressure | Pa or hPa | Helps assess pressure conditions where applicable | Use the correct approved connection and method |

## Conceptual sampling path

~~~mermaid
flowchart LR
  A[Sampling point] --> B[Probe and filter]
  B --> C[Sample conditioning as applicable]
  C --> D[Gas sensors / analyser]
  D --> E[Display and recorded result]
~~~

This is a conceptual diagram, not the internal design of a particular analyser.

## General measurement concepts

- Excess air is air supplied beyond the theoretical amount required for combustion; interpretation depends on fuel and method.
- Sampling position, leaks, condensate, contamination, sensor condition, and operating state can affect readings.
- Compare results only when units, measurement basis, sampling method, and operating conditions are compatible.

## Guide

- [Combustion Measurement Workflow](guides/combustion-measurement-workflow.md) — pre-checks, recording context, interpretation cautions, and safe close-out

## Safe high-level workflow

Use the instrument's approved startup, zeroing, sampling, and shutdown procedure. Check the service status and sampling train before measurement. Record instrument identity, operating conditions, units, sampling point, and relevant alarms. Follow the manufacturer's maintenance instructions after use.

## References

- [ECOM Measurement Technology](https://www.ecom.de/en/)
- [U.S. EPA — Stationary Source Emissions](https://www.epa.gov/emc)

This repository is educational. No customer measurement, physical analyser test, or compliance determination is claimed.