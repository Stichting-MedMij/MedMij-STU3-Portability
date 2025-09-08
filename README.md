# MedMij-STU3-Portability
This repository contains HL7 FHIR STU3 compliant conformance materials for MedMij STU3 Portability. This project is currently in a pre-publication status and can therefore not be considered stable.

The implementation guide for this project, also in a pre-publication status, can be found on [Simplifier](link Simplifier).

This repository is maintained by MedMij.

### Examples

- [Test data for simulator](examples/testdata-simulator) based on [BgZ 3.0](https://github.com/Nictiz/Nictiz-testscripts/tree/main/output/STU3/BgZ-3-0), matching test scenarios.

Test documents in scenario for use case 1:

1. Resource [port-DocumentReference-XXX_Rijn-1-1.json](examples/port-DocumentReference-XXX_Rijn-1-1.json) on test scenario for use case 1 returning a MedMij portability report as binary content. See [port-Binary-XXX_Rijn-1-1.json](examples/port-Binary-XXX_Rijn-1-1.json).
2. resource [port-DocumentReference-XXX_Rijn-1-2.json](examples/port-DocumentReference-XXX_Rijn-1-2.json) on test scenario 1 for use case 1 referencing an example PDF/A export of health care records by url. The url should match an existing or generated resource.
