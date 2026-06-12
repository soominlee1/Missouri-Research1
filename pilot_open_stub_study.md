# Pilot Open Stub Mode Conversion Study

Date: 2026-05-28

## Objective

Investigate the impact of differential conductor asymmetry on differential-to-common mode conversion.

## Method

A differential transmission structure was created in HFSS.

Eight cases were generated automatically.

The positive and negative conductors were assigned different open-stub lengths.

Mixed-mode S-parameters were extracted from exported Touchstone files.

## Key Results

Symmetric structures showed low mode conversion.

Case A:
Scd21 ≈ -49.6 dB

Case G:
Scd21 ≈ -35.0 dB

Asymmetric structures showed significantly larger mode conversion.

Case E:
Scd21 ≈ -6.6 dB

## Conclusion

The dominant factor was not simply the existence of a stub.

Mode conversion increased primarily due to imbalance between the two conductors.
