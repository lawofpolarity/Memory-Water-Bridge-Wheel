# MWB Minimal Falsifiable Experimental Protocol v0.1

## Research question
Does a fully specified aqueous/iontronic device exhibit reproducible history-dependent electrical state beyond instrument drift and control effects, with measurable write/read/retention behavior?

## Pre-registration variables
Specify before data collection:
- device geometry and materials;
- electrolyte composition/concentration and water purity;
- electrode material and spacing;
- temperature;
- voltage/current waveform and limits;
- sampling rate;
- measured current/conductance/state variable;
- write, read, reset and retention intervals;
- number of independent devices and repeated cycles;
- exclusion/failure criteria.

## Controls
At minimum compare against:
1. instrument/open/short controls as appropriate;
2. matched device without the hypothesized active geometry/material feature;
3. randomized stimulus ordering;
4. repeated no-write readouts to estimate drift;
5. temperature monitoring/control.

## Primary measurable endpoints
- hysteresis area under declared sweep protocol;
- state separation after write conditions;
- retention curve versus time;
- cycle-to-cycle variability;
- reset/reversibility;
- energy per write/read measured from voltage-current-time data.

## Falsification criteria
The candidate memory claim is not supported if state separation is indistinguishable from controls/drift, fails blinded repeatability, disappears under matched controls, or cannot be read after the declared retention interval.

## Interpretation boundary
Even a positive device-memory result supports only the specified device/material system. It does not establish persistent symbolic memory in ordinary bulk water, biological memory transfer, holographic storage, consciousness, or medical efficacy.

## Data obligations
Commit raw machine-readable data, calibration metadata, analysis code, hashes, protocol version and negative/failed runs. Preserve raw observations before derived plots.

## Constitutional route
A successful experiment creates evidence for a reconstruction candidate. It does not itself close G1–G4.
