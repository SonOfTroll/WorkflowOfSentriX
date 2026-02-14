# WorkflowOfSentriX

```bash
detector/*.py         → Collect structured data
ml_engine/*.py        → Convert event → features → score
decision/risk_engine  → Calls ML or rules
responder/*.py        → Acts on risk
main.py               → Orchestrates
```
