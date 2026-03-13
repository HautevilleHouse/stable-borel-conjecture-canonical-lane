# Third-Party Rerun Protocol

1. Clone the repository.
2. Run `bash repro/run_repro.sh`.
3. Confirm that `repro/certificate_runtime.json` reports `SBOR_G1` through `SBOR_G6` and `SBOR_GM` as `PASS`.
4. Confirm that `scripts/release_gate.py --mode fully_extracted` returns `ok = true`.
5. Confirm that all tracked hashes in `repro/repro_manifest.json` match.
