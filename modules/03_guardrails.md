> Change Log (2025-12-02): Added strict evidence mode and standardized warning messages.

- Add `evidence_mode = "strict"`:
  - Only include claims/results explicitly stated in the section text.
  - If insufficient info → say so explicitly.
- Add warning messages:
  - Missing section → “Section skipped: no usable text provided.”
  - Too short section (<50 words) → “Section very short: summary may be incomplete.”
