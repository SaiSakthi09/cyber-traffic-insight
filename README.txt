# Cyber Traffic Insight — Synthetic Practice Dataset

These five CSV files were generated for the Round 2 EDA and Feature Engineering task in Use Case 27 — Cyber Traffic Insight.

## Files
- `flows.csv`: Network-flow records (flow IDs, timestamps, hosts, protocol, duration, bytes, packets).
- `hosts.csv`: Host reference data (host group and network zone).
- `sessions.csv`: Flow session metadata (source/destination zones, destination port and port category).
- `labels.csv`: Normal/unusual labels.
- `calendar.csv`: Hour, weekday and maintenance-window information.

## Important
This is **synthetic data**, not real network traffic and not evidence of actual cyber incidents. It intentionally contains data-quality issues for practice:
- Missing protocol values
- Duplicate flow IDs in `flows.csv`
- Inconsistent label spellings/casing
- Extreme byte counts
- A small number of flow rows with a host ID that does not match `hosts.csv`

The analysis should document how these issues are detected and handled. Do not describe generated patterns as real-world findings.
