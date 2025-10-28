## Ethical Statement
- No PII or sensitive data are collected or shared.
- All data are synthetic, generated in a lab/Colab environment.
- No live external systems are accessed.
- Every dataset generated is logged with parameters, timestamps, and hashes in `DATA_README.md`.
- This notebook documents what is simulated and what is omitted for ethical reasons.

### Risks
Bias (synthetic ≠ real), privacy risk if misused with real logs, and security misuse outside isolated labs.

### Mitigations
Use synthetic data only here; isolate real tests; document parameters; don’t store identifiers or real audit logs.

### Limitations
Synthetic data cannot capture full kernel complexity; this demonstrates reproducibility, not EDR performance.
