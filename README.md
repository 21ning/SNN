# SNN Release Assets

This repository contains release staging files for DVS Gesture Spikformer experiments.

The large `dvs_gesture_spikformer_full_with_deps_20260610.tar.gz` package is staged as split parts under:

```text
release-assets/dvs_gesture_spikformer_full_with_deps_20260610/
```

A GitHub Actions workflow merges the split parts, verifies SHA256, and uploads the full archive to a GitHub Release.
