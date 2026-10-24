# Combustion Measurement — General Workflow

This guide explains a general documentation workflow for flue-gas measurements. It is not a substitute for the analyser manual, appliance instructions, local regulations, or training by a competent combustion technician.

## Before measuring

- Identify the appliance/process, fuel, operating condition, and test objective.
- Confirm the analyser is suitable for the application and its sensors are within service/calibration requirements.
- Inspect the approved probe, tubing, filters, condensate handling, and connectors according to the manual.
- Check the required sampling point and measurement method for the appliance/process.
- Follow site safety rules, ventilation requirements, and any permit or isolation procedure.

## General measurement sequence

~~~mermaid
flowchart TD
  A[Confirm job and instrument suitability] --> B[Inspect instrument and sampling train]
  B --> C[Follow approved startup / zeroing procedure]
  C --> D[Sample at the specified point]
  D --> E[Wait for stable readings as defined by the manual]
  E --> F[Record values and operating conditions]
  F --> G[Check plausibility and applicable limits]
  G --> H[Follow approved shutdown / service procedure]
~~~

## Record context with each reading

| Field | Why it matters |
|---|---|
| Date/time and site identifier | Traceability; avoid exposing confidential customer data publicly |
| Instrument model and service status | Establishes instrument suitability and traceability |
| Fuel/process and operating state | Conditions can materially affect readings |
| Sampling point and method | Supports repeatability and interpretation |
| O₂, CO, CO₂, NO/NO₂ and temperature where measured | The relevant parameter set depends on the analyser and application |
| Units and wet/dry basis where applicable | Prevents invalid comparisons |
| Ambient conditions, alarms, observations | Helps explain anomalous results |

## Interpretation cautions

- Oxygen, carbon monoxide, carbon dioxide, nitrogen oxides, and temperature are not interchangeable indicators; interpret them in context.
- Excess-air estimates and efficiency calculations depend on fuel assumptions, instrument configuration, and the calculation method.
- Compare values only when sampling method, units, basis, operating condition, and applicable standard are compatible.
- A plausible display does not prove calibration or safe combustion.

## After the measurement

Follow the manufacturer's approved shutdown, filter/condensate care, storage, and service instructions. Do not invent calibration intervals or bypass alarms. If a reading suggests unsafe operation, follow the site's approved safety response and qualified-person escalation procedure rather than relying on this guide.

## References

- [ECOM Measurement Technology](https://www.ecom.de/en/)
- [U.S. EPA — Stationary Source Emissions](https://www.epa.gov/emc)

This is a general learning document, not a record of a customer test or a guarantee of compliance.