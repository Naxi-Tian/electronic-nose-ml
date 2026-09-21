# Electronic Nose: ML-Based Gas and Scent Sensor

This project explored a wearable scent-sensing system that combines an ESP32, a BME688 gas sensor, and a machine-learning classification pipeline. It was created by a three-person team during the University of Pennsylvania ESAP Nanotechnology Program in July–August 2025.

The team used raw scent-sensor data to classify unlabeled food-allergen samples, including peanut and gluten. Tenne Tian served as product manager and helped lead the project from sensor design choices through the ML pipeline.

> This repository contains a documentation structure only. Add the team's real firmware, data, models, and results; no implementation or accuracy is implied by the placeholders.

## Project goals

- Integrate a BME688 scent sensor with an ESP32-based wearable prototype.
- Collect raw sensor responses from food-allergen samples.
- Prepare sensor data for machine-learning classification.
- Classify unlabeled samples within the scope of the course project.

## Technical context

The work was informed by ESAP study in nanotechnology, including microfluidics, lithography, and band-gap theory. Those subjects provided design context; this repository should distinguish clearly between concepts studied and techniques directly implemented in the prototype.

## Suggested repository structure

```text
assets/       Approved prototype photos and result figures
data/
  raw/        Raw exports, only if redistribution is permitted
  processed/  Clean, documented, non-sensitive sample data
docs/         Sensor setup, experiment notes, and data dictionary
firmware/     Actual ESP32/BME688 data-collection firmware
hardware/     Schematics, wiring diagrams, enclosure files
ml/           Preprocessing, training, inference, and evaluation code
```

## What to document with the real files

- Sensor settings, sampling procedure, environmental controls, and labeling process.
- Dataset columns, units, class definitions, and train/test split methodology.
- Preprocessing and feature-extraction steps.
- Model type, training configuration, and evaluation method.
- Verified results, including limitations and possible sources of leakage or confounding.
- Team-member roles and ownership of code, data, and hardware files.

## Before this repository is public

- [ ] Confirm all three team members approve publication.
- [ ] Confirm UPenn/ESAP rules allow the code, course materials, and data to be shared.
- [ ] Remove personal information and device/network credentials.
- [ ] Add a small, documented sample dataset only if sharing is permitted.
- [ ] Add real evaluation figures and metrics; do not estimate missing numbers.
- [ ] Add reproducible setup and run instructions.
- [ ] Select a license after ownership is confirmed.

## Scope and limitations

This was an educational prototype, not a medical diagnostic system. The repository should not claim that it detects allergies in people or determines whether food is safe to consume.

## Credits

Developed during the University of Pennsylvania ESAP Nanotechnology Program, July–August 2025. **TODO:** add teammate and mentor names with permission.

