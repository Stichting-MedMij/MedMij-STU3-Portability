# MedMij-STU3-Portability
This repository contains HL7 FHIR STU3 compliant conformance materials for MedMij STU3 Portability. This project is currently in a pre-publication status and can therefore not be considered stable.

The implementation guide for this project, also in a pre-publication status, can be found on [Simplifier](link Simplifier).

This repository is maintained by MedMij.

### Examples

The [simulator test data](examples/testdata-simulator) is based on [BgZ 3.0](https://github.com/Nictiz/Nictiz-testscripts/tree/main/output/STU3/BgZ-3-0) and the matching test scenarios.

The following resources are used as test material for [use case 1](https://changemanagement.medmij.nl/pgo-koppelvlak-publicatie/Working-version/bijlage-testscripts-2025-pgok-v0-5-4#Bijlagetestscripts(2025-PGOK-v0.5.4)-Usecase1.OverstapservicePGO-leverancier):

- Resource [port-DocumentReference-XXX_Rijn-1-1.json](examples/port-DocumentReference-XXX_Rijn-1-1.json) represents a MedMij portability report, which is conveyed via a Binary resource, namely [port-Binary-XXX_Rijn-1-1.json](examples/port-Binary-XXX_Rijn-1-1.json).
- Resource [port-DocumentReference-XXX_Rijn-1-2.json](examples/port-DocumentReference-XXX_Rijn-1-2.json) represents an export of health care records in PDF/A format, which is referenced by its url. The url should match an existing or generated resource.

Note that the two DocumentReference resources (and the referenced Binary resource) are used in both use case [1.1](https://changemanagement.medmij.nl/pgo-koppelvlak-publicatie/Working-version/bijlage-testscripts-2025-pgok-v0-5-4#Bijlagetestscripts(2025-PGOK-v0.5.4)-Usecase1.1Overstapservice:verzamelendocumentenoverPGO-koppelvlak) and [1.2](https://changemanagement.medmij.nl/pgo-koppelvlak-publicatie/Working-version/bijlage-testscripts-2025-pgok-v0-5-4#Bijlagetestscripts(2025-PGOK-v0.5.4)-Usecase1.2Overstapservice:beschikbaarstellendocumentenoverPGO-koppelvlak).