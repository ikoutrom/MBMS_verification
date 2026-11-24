This folder contains the files from Section 4.4, "Analysis of steel frame under earthquake loading with shell elements"

The four subfolders correspond to the following cases:

- F01_implicit_HHT_dt0.0025: Implicit dynamic analysis using HHT method and a solution time-step of 0.0025 sec
- F02_explicit_MBMS_f21: explicit analysis using the proposed MBMS scheme (time-step increase factor f = 21)
- F03_explicit_MS: explicit analysis with uniform mass scaling
- F04_explicit_unscaled_first_second: explicit analysis without any mass scaling, only the first 1 sec of the ground motion (not included in the manuscript, only used internally for benchmarking)