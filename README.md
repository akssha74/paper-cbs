# paper-cbs immutable package (2026-09-27)

Fail-closed qualification-contract manuscript package and supporting one-shot / post-hoc evidence.

| Archive | SHA-256 |
|---|---|
| `paper-cbs-r25-2026-09-27.tar.gz` | see SHA256SUMS |
| `paper-cbs-r25-2026-09-27-evidence.tar.gz` | see SHA256SUMS |

The main tarball is the `paper-cbs/` tree. The evidence tarball holds the RFC 3161-timestamped 2026-Q3 DYFI confirmatory arm (non-evaluable under pre-specified floors) and post-hoc JSON for sequence-residual ICC, Strack 2014, and encounter-vs-patient splits.

This repository exists so the reviewed files have a public, hash-locked copy. It is not a journal submission.

## 2026-09-27b (R26)

- `paper-cbs-r26-2026-09-27b.tar.gz` — manuscript package including the RFC 3161-timestamped ICU sepsis transfer and both timestamped DYFI windows.
- `paper-cbs-r26-2026-09-27b-evidence.tar.gz` — one-shot study directories: sepsis (plan, FreeTSA token, runner, hashed PhysioNet/CinC 2019 archive redistributed under ODbL 1.0, results), M4 magnitude-shift DYFI window, 2026-Q3 DYFI window.

## 2026-09-27c (R27)

- `paper-cbs-r27-2026-09-27c.tar.gz` — manuscript package; now bundles the sepsis raw archive, released holdout predictions, offline sepsis verifier, post hoc sepsis analyses, and FreeTSA certificates for offline token verification.
- `paper-cbs-r27-2026-09-27c-evidence.tar.gz` — one-shot study directories (sepsis, magnitude-shift DYFI, 2026-Q3 DYFI).

## 2026-09-27d (R28)

Release assets only (not committed to git): `paper-cbs-r28-2026-09-27d.tar.gz` and `paper-cbs-r28-2026-09-27d-evidence.tar.gz`; adds the matched overlap control and ICULOS sensitivity for the sepsis arm. SHA-256 in SHA256SUMS.

## 2026-09-27e (R29)

Release assets only (not committed to git): `paper-cbs-r29-2026-09-27e.tar.gz` and `paper-cbs-r29-2026-09-27e-evidence.tar.gz`; adds a post hoc name-gate audit of eight independently submitted CinC 2019 source archives (not scored). SHA-256 in SHA256SUMS.

## 2026-09-27f (R30)

Release assets only (not committed to git): `paper-cbs-r30-2026-09-27f.tar.gz` and `paper-cbs-r30-2026-09-27f-evidence.tar.gz`; reports the pre-registered row-random test-split evaluation as the case separating the patient-level audit from row identity, and discloses both CinC 2019 archive analyses (text scan and interface schema check; not scored). SHA-256 in SHA256SUMS.

## 2026-09-27g (R31)

Release assets only (not committed to git): `paper-cbs-r31-2026-09-27g.tar.gz` and `paper-cbs-r31-2026-09-27g-evidence.tar.gz`; wording and calibration revision of R30 (no new analyses). SHA-256 in SHA256SUMS.

## 2026-09-27h (R32)

Release assets only (not committed to git): `paper-cbs-r32-2026-09-27h.tar.gz` and `paper-cbs-r32-2026-09-27h-evidence.tar.gz`; corrects the attribution of the sepsis row-random split (author-specified, not a published PhysioNet protocol) and condenses the manuscript. SHA-256 in SHA256SUMS.

## 2026-09-27i (R33)

Release assets only (not committed to git): `paper-cbs-r33-2026-09-27i.tar.gz` and `paper-cbs-r33-2026-09-27i-evidence.tar.gz`; adds an RFC 3161-timestamped audit of 60 public repositories that split the PhysioNet/CinC 2019 table (fetched third-party files are not redistributed; blob SHAs are in fetch_manifest.json). SHA-256 in SHA256SUMS.

## 2026-09-27j (R34)

Release assets only (not committed to git): `paper-cbs-r34-2026-09-27j.tar.gz` and `paper-cbs-r34-2026-09-27j-evidence.tar.gz`; adds a post hoc multi-scale (sequence and region) Holm support rule for the prospective DYFI arm. SHA-256 in SHA256SUMS.

## 2026-09-27k (R35, reframed manuscript)

Release assets only: `paper-cbs2-r35-2026-09-27k.tar.gz` (reframed manuscript package) and `paper-cbs2-r35-2026-09-27k-evidence.tar.gz` (pre-registered eight-dataset split audit with RFC 3161 timestamp, both coders' codes, author check, matched inflation; frozen 2027 multi-scale DYFI plan; earlier arms). Fetched third-party repository files, code snippets, and re-downloadable UCI archives are not redistributed; their hashes are in the manifests. The package tarball's title_page.tex/pdf and frozen public-archive record are the only files that change after release, because they record this release's own hash. SHA-256 in SHA256SUMS.
