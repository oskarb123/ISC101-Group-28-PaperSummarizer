> Change Log (2025-12-02): Added summary_level modes with short and detailed behavior.

- Introduce variable `summary_level` ("short" or "detailed").
- If short → generate a compact 1–2 sentence summary (≤50 words).
- If detailed → generate a short paragraph + 3–5 bullet points.
- Only use section text (no hallucination).
- Skip missing sections and pass to Guardrails.

