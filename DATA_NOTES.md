# Data Availability and Methodology Notes

This document records the availability of EMS/ambulance data for the
2014-2018 period surrounding the San Clemente hospital closure (May 31,
2016), the reasons for observed gaps, and the resulting implications for
project scope.

---

## Distinction Between Metrics

Two distinct metrics are relevant to this project. They are tracked by
different agencies and have different reporting histories.

| Metric | Definition | Responsible Entity | Standardization Timeline |
|---|---|---|---|
| Ambulance Patient Offload Time (APOT) | Interval from ambulance arrival at a hospital to formal patient acceptance by the emergency department | Local EMS Agency (LEMSA); in this case, Orange County EMS (OCEMS) | Methodology developed 2015-2016; mandatory statewide reporting began 2019 |
| Ambulance response time | Interval from 9-1-1 call receipt to ambulance arrival at scene | Fire department / ambulance provider, under contract with the municipality | Recorded via CAD (Computer-Aided Dispatch) systems for operational and contractual purposes; not centrally published |

## APOT Data: 2014-2018

Findings, based on a phone consultation with OCEMS (September 2026) and
cross-referenced against California EMS Authority documentation:

- APOT was not a standardized or mandated metric during 2014-2018.
- The California EMS Authority developed a standard methodology for
  APOT calculation and reporting beginning approximately 2015-2016.
  Adoption by LEMSAs was optional prior to statewide mandatory reporting,
  which began in 2019.
- OCEMS confirmed that APOT was not measured in Orange County at the
  time of the closure. The publicly available OCEMS APOT dashboard data
  begins in 2018.

**Implication:** The absence of APOT data for 2014-2018 reflects the
non-existence of the metric in standardized form during that period,
not a data access failure or recordkeeping deficiency.

## Ambulance Response Time Data: 2014-2018

OCEMS does not maintain jurisdiction over ambulance response time data.
Per OCEMS, this data is held by the City of San Clemente, which
contracts directly with the fire department and/or ambulance provider
for emergency medical transport services.

- Response-time compliance is typically established as a contractual
  requirement between a municipality and its ambulance provider,
  including performance thresholds and associated penalties.
- CAD (Computer-Aided Dispatch) records — including call receipt,
  dispatch, and arrival timestamps — are generated as a function of
  standard dispatch operations and are independent of APOT reporting
  requirements.
- Historical CAD data for this period is expected to exist at the level
  of the fire department, ambulance provider, or municipality, rather
  than at the county EMS agency level.

**Implication:** This represents a data routing issue rather than a
data non-existence issue. The applicable next step is a data request
directed to the City of San Clemente or Orange County Fire Authority.

## Supplementary Source: CEMSIS

The California EMS Information System (CEMSIS), built on national
NEMSIS data standards, records response, scene, and transport time
data and predates APOT as a tracked metric. Prior to 2017, data was
collected under NEMSIS standard version 2.2.1.

Limitations of CEMSIS as a data source for this project:

- Reporting to CEMSIS by LEMSAs is voluntary. Coverage is inconsistent;
  Los Angeles County EMS Agency does not report into CEMSIS.
- Available datasets show substantial missing data at the zip-code
  level, even in jurisdictions that do report.
- CEMSIS may provide regional or statewide aggregate context (e.g., via
  published EMSA annual reports) but is not confirmed as a reliable
  source of granular, San Clemente-specific historical data.

## Effect on Project Scope

- **Research Question 1** (change in drive-time to nearest ER following
  closure): Unaffected. This analysis is geospatial and does not depend
  on APOT or response-time datasets.
- **Research Question 2** (change in ambulance transport patterns/offload
  times following closure): Requires modification. A direct 2016-versus-
  present comparison using APOT is not possible due to the absence of
  pre-2018 data. Two alternative approaches are under consideration:
  1. Analysis of available APOT data from 2018 forward, used as a
     post-closure baseline rather than a before/after comparison.
  2. Substitution with historical ambulance response-time data, pending
     data availability from the City of San Clemente or Orange County
     Fire Authority.

## Outstanding Action Item

- [ ] Submit a data request to the City of San Clemente or Orange
      County Fire Authority for historical (2014-2018) ambulance
      response-time or CAD records for the San Clemente service area.
