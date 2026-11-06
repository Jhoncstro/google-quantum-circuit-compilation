# Google Quantum AI — Verifiable Quantum Circuit Compilation

This repository stores the team's best officially scored submission artifact as
of 2026-11-06. It is the Kaggle package itself, not the source code used to
produce the public-source circuit portfolio.

## Best confirmed artifact

- Package: `submission-v8.zip`
- Kaggle submission: `58048237`
- Official public score: **24.94090**
- Kaggle status: **COMPLETE**
- ZIP SHA-256: `f99fba9d7c93a5202039cca8023c6fe70bb6f07c1e30adf26c4168b02b6b70e5`
- Archive validation: 18 files, CRC check passed

The v8 candidate changed only `dfthcsos/submission.npz` from the v6 package.
Its source notebook reported PASS for chemistry, DQI, and inverse square root.
The official Kaggle score is authoritative; local/public notebook measurements
are recorded separately in `release.json`.

## Verification measurements

| Task | Cost |
|---|---:|
| Inverse square root | 97,746.895516 |
| DQI | 374,771,517,851.6414 |
| DF-THC | 299,671,079.533169 |
| Source-reported geometric mean | 24.94091 |

These are source-notebook verifier measurements and can differ slightly from
the official Kaggle score.

## Files

- `submission-v8.zip` — exact archive uploaded to Kaggle
- `release.json` — provenance, official score, checksums, and verifier metrics

This repository is private because the package contains competition submission
artifacts. No credentials or Kaggle tokens are included.
