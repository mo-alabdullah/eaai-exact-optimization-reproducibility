# Exact Optimization References for Industrial Wireless Uplinks — Reproducibility Archive

This repository contains the reproducibility archive for the study:

**Exact Optimization References for Joint Radio Resource Allocation in Industrial Wireless Uplinks**

The archive contains the frozen confirmatory results, exact optimization
references, analysis and verification code, deterministic figure-generation
pipeline, integrity records, and supporting reproducibility documentation.

All scientific reproducibility material is contained under:

`journal_eaai/`

See:

- `journal_eaai/README.md`
- `journal_eaai/REPRODUCIBILITY.md`
- `journal_eaai/ARCHIVE_MANIFEST.md`

## Verification

From the repository root:

```bash
python3 journal_eaai/tools/verify_archive.py
python3 journal_eaai/tools/reproduce_endpoints.py

These commands verify or recompute results from the archived frozen evidence.
They do not rerun the confirmatory campaign.
Citation
See CITATION.cff and .zenodo.json.
License
Code and repository tooling are released under the MIT License.
