# WorkflowOfSentriX

```bash
detector/*.py         → Collect structured data
ml_engine/*.py        → Convert event → features → score
decision/risk_engine  → Calls ML or rules
responder/*.py        → Acts on risk
main.py               → Orchestrates
```
### The /etc/shadow file in Linux stores secure user account information, specifically hashed (encrypted) passwords and password aging policies, to enhance system security.
```bash
What happens if system is compromised before baseline?
The system assumes a trusted initialization phase... baaseline creation must be done on a verified clean system otherwise integrity monitoring cannot detect prior compromise
```
## Privilege Monitor
### Instead of relying solely on static thresholds, the design allows combining privilege level, resource usage, and process metadata. The current implementation uses conservative thresholds to balance false positives and detection sensitivity, with support for future behavioral scoring.

---
### It’s a hybrid detection system combining rule-based thresholds and ML anomaly scoring through an ensemble risk engine.
