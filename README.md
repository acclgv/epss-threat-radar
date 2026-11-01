# EPSS Threat Radar: Predictive Vulnerability Scoring

[![CISA KEV Integrated](https://img.shields.io/badge/Feed-CISA_KEV-blue?style=flat-square)](https://www.cisa.gov/known-exploited-vulnerabilities-catalog)
[![FIRST.org EPSS](https://img.shields.io/badge/Scoring-FIRST_EPSS_v3-red?style=flat-square)](https://www.first.org/epss/)
[![Status](https://img.shields.io/badge/Pipeline-Operational-brightgreen?style=flat-square)](https://github.com/acclgv/epss-threat-radar)

Real-time correlation engine mapping actively exploited vulnerabilities (**CISA KEV**) against **FIRST.org EPSS** (Exploit Prediction Scoring System) probability percentiles.

## What is EPSS?
The Exploit Prediction Scoring System (EPSS) estimates the probability (0-1) that a software vulnerability will be exploited in the wild within 30 days. Combining EPSS with CISA KEV enables data-driven vulnerability prioritization for enterprise CSIRTs.

## Automated Intelligence Feed
The radar correlates active telemetry feeds and identifies high-velocity CVEs exceeding risk thresholds (>0.85 EPSS). See [telemetry/radar_status.json](telemetry/radar_status.json).
