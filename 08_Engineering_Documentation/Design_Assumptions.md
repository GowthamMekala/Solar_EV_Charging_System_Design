# Design Assumptions

## Project Scope

This project is a conceptual portfolio and learning design for a Solar-Powered EV Charging + Battery Energy Storage + EV Battery Pack system.

The design is intended for educational and portfolio demonstration purposes only.

## Design Nature

The complete project is conceptual and intended for portfolio and learning purposes.

The drawings and documentation are not construction-ready engineering documents.

No final equipment procurement, installation, commissioning, or field implementation is intended.

All detailed engineering decisions must be verified by qualified professionals before any real-world implementation.

## Electrical Design Assumptions

The Solar PV system is represented as the conceptual electrical generation source.

The PV combiner / protection stage is represented as a conceptual interface between the PV array and solar inverter.

The solar inverter is represented as the conceptual power-conversion interface between the PV system and AC distribution.

The AC distribution system is represented as the conceptual electrical distribution point for the BESS and EV charger.

The BESS is represented as a stationary energy storage system supporting the conceptual EV charging site.

The EV charger is represented as the conceptual interface between the charging-site AC system and the EV battery.

The EV battery pack is represented as a conceptual high-voltage battery system containing battery modules, BMS, protection / contactor stage, HV DC bus, and HV interface.

## EV Vehicle Architecture Assumptions

The EV battery is represented as the conceptual high-voltage energy source for the vehicle.

The HV vehicle system represents the conceptual high-voltage distribution architecture.

The traction inverter is represented as the conceptual power-conversion interface between the HV vehicle system and traction motor.

The traction motor is represented as the conceptual electric motor used for vehicle propulsion.

The 12V / LV system is represented as the conceptual low-voltage electrical and vehicle-control system.

The vehicle control system is represented as a conceptual control interface within the EV architecture.

## BMS Assumptions

The Battery Management System (BMS) is represented as a conceptual monitoring and control system.

The BMS monitors and manages the conceptual battery modules.

Detailed BMS algorithms, communication protocols, cell balancing methods, sensing circuits, and software implementation are outside the scope of this portfolio project.

## Cable and Rating Assumptions

Cable sizes and electrical ratings are intentionally marked as TBD where detailed engineering calculations are not available.

No cable size, conductor rating, voltage rating, current rating, protection setting, or equipment rating is presented as a final engineering value.

Detailed cable sizing shall require electrical load calculations, installation conditions, applicable standards, voltage-drop calculations, short-circuit calculations, thermal considerations, and protection coordination.

## Protection Assumptions

Protection devices and contactors are represented conceptually in the drawings.

Final protection-device selection and protection settings are outside the scope of this project.

Short-circuit studies, coordination studies, arc-flash studies, grounding studies, and detailed protection calculations are not included.

## Thermal and Safety Assumptions

Detailed thermal calculations are outside the scope of this project.

Battery thermal management is represented conceptually only.

Detailed fire protection, emergency shutdown, electrical safety, battery safety, mechanical safety, and regulatory compliance are outside the scope of this portfolio design.

## Standards and Compliance

The project does not claim compliance with any specific electrical, automotive, battery, charging, or safety standard.

Applicable standards and regulations must be identified and verified by qualified professionals before real-world implementation.

## CAD Drawing Assumptions

All AutoCAD drawings are conceptual representations of the proposed system architecture.

The drawings are intended to demonstrate engineering understanding, system relationships, electrical interfaces, and documentation skills.

The drawings are not fabrication drawings, installation drawings, or construction drawings.

## Engineering Documentation Assumptions

The engineering documentation is intended to demonstrate basic systems-engineering and documentation practices.

The BOM uses illustrative values taken from Design_Calculations.xlsx where a worked example exists, and TBD where specific procurement information is not justified.

The Cable Schedule uses illustrative sizes from Design_Calculations.xlsx for the site power circuits (CBL-001 to CBL-006) and TBD for vehicle-side and communication cables.

The Interface Matrix represents conceptual interfaces between major system elements.

The Requirements Traceability document connects system requirements with relevant conceptual drawings and verification methods.

The Verification Plan defines conceptual review and inspection activities for portfolio demonstration.

## Illustrative Example Values

Design_Calculations.xlsx provides a formula-driven worked example (PV, BESS, EV pack, cable and protection sizing). Its key assumptions are:

- Grid-connected 400 V / 50 Hz three-phase site (the grid interface is not yet drawn).
- 2 AC charging points, 32 A single-phase each; 4 sessions per day at 20 kWh per session (80 kWh/day).
- 50 % of daily charging energy served by PV and 30 % served via the BESS.
- 4.5 peak sun hours, performance ratio 0.80, minimum site temperature 10 degC.
- Module, inverter, battery and cable data are generic illustrative values, not taken from real datasheets or a specific edition of any standard.
- Short-circuit, earthing, protection coordination and thermal studies are not included.

These values exist to make the design traceable and checkable. They do not change the conceptual, non-construction status of the project.

## Project Limitation

This project is not intended to be used directly for construction, installation, procurement, commissioning, vehicle modification, electrical connection, or safety certification.

Any real-world implementation would require detailed engineering calculations, verified equipment specifications, applicable standards, professional review, safety assessment, testing, approvals, and regulatory compliance.

## Portfolio Purpose

The purpose of this project is to demonstrate practical understanding of:

- Electrical system architecture
- Solar PV system concepts
- EV charging system concepts
- Battery Energy Storage Systems
- EV battery pack architecture
- BMS concepts
- High-voltage EV architecture
- AutoCAD electrical layouts
- Single-line diagrams
- Cable and interface documentation
- Requirements traceability
- Verification planning
- Basic systems engineering documentation

## Author

Gowtham Mekala

## Status

CONCEPTUAL DESIGN – FOR PORTFOLIO / LEARNING PURPOSES

Date: 2026