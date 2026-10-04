# Technical Whitepaper — TZ_DATA

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/transitionzero/tz-data
**Category:** CARBON_CAPTURE

## Abstract

This whitepaper describes the Anticloud integration of `TZ_DATA` (Energy transition carbon data)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local process optimization for DAC — air-gapped plant
2. AIOSS tamper-evident carbon credit audit chain (Verra/Gold Standard aligned)
3. AES-256 encryption for all monitoring and reporting data
4. Single-binary plant management system for remote deployments
5. Zero-cloud: all sensor analytics and optimization run locally
6. GPU/CPU equalizer: real-time control on embedded CPU, simulation on GPU
7. Open MRV protocol: machine-readable verification reports without third-party auditor API
8. Offline atmospheric CO2 measurement calibration pipeline

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.