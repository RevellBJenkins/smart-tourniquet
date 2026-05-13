Smart Self-Tightening Tourniquet — Prototype 2
Overview

# Smart Self-Tightening Tourniquet — Prototype 2 Overview

This repository documents Prototype 2 of a Smart Self-Tightening Tourniquet concept developed as a collaborative engineering project. Prototype 2 focused on evaluating pressure sensor behavior inside a designed enclosure rather than building a complete automated tightening system.

The purpose of this iteration was to determine whether the selected sensing approach could provide reliable feedback for a future tourniquet control system.

This prototype is a continuation of an earlier design iteration and focuses on system integration and sensor evaluation rather than final device performance.

## Project Scope

This project is an educational and exploratory prototype. It is not a medical device and has not undergone clinical validation, regulatory review, or safety certification. The work presented here is intended solely for academic and engineering learning purposes.

## Prototype Focus

Prototype 2 intentionally excluded mechanical tightening and focused specifically on evaluating pressure sensor behavior within a designed enclosure. The goal of this iteration was to determine whether the selected sensing approach could provide reliable and interpretable feedback for a future self-tightening tourniquet system.

## High-Level Concept

The broader system concept combined a mechanical tightening mechanism with embedded pressure sensing and basic control logic. User feedback was intended to indicate when applied pressure fell within an expected range, with the goal of reducing reliance on subjective user judgment during application.

## Project Status

Prototype 2 is no longer under active development. This repository serves as a record of the design decisions, implementation attempts, and evaluation results associated with this iteration.

Any code present reflects exploratory sensor testing conducted during Prototype 2 and is not intended to represent a complete or deployable system.

## Evaluation Summary

Prototype 2 was intended to evaluate the feasibility of integrating pressure sensing into a self-tightening tourniquet concept. While portions of the enclosure, sensor integration, and control architecture were successfully assembled, the prototype did not meet sensing requirements during testing.

The selected pressure sensor was not suitable for the operational range and resolution required for consistent and interpretable feedback under realistic loading conditions. As a result, sensing reliability became the primary limiting factor for the system.

Because reliable sensing could not be achieved, higher-level control behavior and user feedback logic could not be meaningfully evaluated within this iteration.

## Lessons Learned

Prototype 2 highlighted several important engineering considerations for wearable medical-assistive systems:

- Sensor selection must be validated against expected operating ranges before full system integration.
- Mechanical integration and sensing reliability must be developed together rather than independently.
- Real-world loading conditions introduced significantly more variability than initially expected.
- Early enclosure testing was useful for identifying sensing limitations before investing additional effort into full system automation.
- Future iterations would likely require alternative sensing strategies rather than relying solely on static pressure sensing.

## Future Direction

Future iterations would require a redesigned sensing strategy and additional validation under realistic loading conditions. Potential directions include alternative pressure-sensing methods, motion-based sensing, or Doppler-based approaches capable of providing more reliable physiological feedback during application.

## Repository Structure

/docs  
Contains supporting project documentation, design notes, evaluation summaries, and development references related to Prototype 2.

LIMITATIONS.md  
Documents known technical, mechanical, and validation limitations identified during Prototype 2 evaluation and testing.

README.md  
Provides a high-level overview of Prototype 2, including project scope, evaluation results, lessons learned, and future direction.

Code Files  
Any included source code reflects exploratory sensor testing and early-stage integration experiments performed during Prototype 2 development. The code is not intended to represent a finalized or deployable system.

## Team

This repository reflects a collaborative group engineering effort. Individual contributions correspond to specific design, integration, documentation, and evaluation tasks completed during Prototype 2 development.
