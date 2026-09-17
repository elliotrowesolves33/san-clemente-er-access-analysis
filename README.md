Work in progress
# Emergency Access After Closure: San Clemente Hospital Impact Analysis

*A geospatial and operational analysis of ER access and ambulance transport
patterns before and after the 2016 closure of Saddleback Memorial Medical
Center – San Clemente.*

## The Question

In May 2016, the only hospital emergency room in San Clemente, CA closed,
leaving a geographically isolated community (ocean to the west, national
forest to the east, a military base to the south, one congested highway out)
without a local ER. Community members at the time warned this would increase
ambulance transport times, strain neighboring hospitals, and put lives at
risk.

Did it?

**This project asks:**
1. How did average drive-time to the nearest ER change for San Clemente
   residents after the closure?
2. How did ambulance patient offload times and transport patterns to
   South Orange County hospitals change afterward?

## Data Sources

- *(e.g., hospital/ER location data, source, date range)*
- *(e.g., OC-MEDS / APOT data, source, date range)*
- *(e.g., road network / geocoding source)*

## Approach

- *(Brief plain-language walkthrough: cleaning, PostGIS drive-time modeling,
  before/after comparison methodology. 3-5 sentences, not a full log —
  link to PROJECT_LOG.md if readers want the detailed process.)*

## Key Findings

- *(Lead with numbers. e.g., "Average drive-time to nearest ER increased by
  X minutes for ZIP code Y.")*
- *(Visual: before/after map)*
- *(Visual: supporting chart)*

## Limitations

- *(Be upfront: what data wasn't available, what had to be approximated,
  what a fuller analysis with more resources/access would include.)*

## Tools Used

PostgreSQL + PostGIS · DBeaver / pgAdmin · Tableau · Python *(if used)*

## Repo Structure

```
/sql          -- analysis queries
/data         -- raw and cleaned datasets (or links, if data is large/restricted)
/notebooks    -- exploratory work, if any
PROJECT_LOG.md -- full working log of the project process
README.md     -- this file
```

---

*Built by Elliot Rowe as a portfolio project.
[LinkedIn](https://linkedin.com/in/elliot-rowe-4409b02b9)*
