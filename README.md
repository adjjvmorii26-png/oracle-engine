# Oracle Engine

**Autonomous multi-perspective research engine**

A question enters. Six analysts examine it from different angles — strategic, empirical, philosophical, creative, adversarial, and integrative. The Oracle synthesizes their findings into a consensus with confidence scores.

## How It Works

1. **Question** — you ask anything
2. **Dispatch** — 6 perspectives analyze independently
3. **Synthesize** — find agreement, disagreement, and the underlying truth
4. **Report** — multi-perspective analysis with consensus scoring

## Perspectives

| Perspective | Lens | Strengths |
|-------------|------|-----------|
| **Strategist** | Systems thinking | Logic, evidence |
| **Scientist** | Empirical | Evidence, logic |
| **Philosopher** | Analytical | Logic, critique |
| **Poet** | Creative | Creativity, metaphor |
| **Critic** | Adversarial | Critique, edge cases |
| **Synthesizer** | Integrative | Balance, unity |

## Quick Start

```python
from oracle_engine import OracleEngine

engine = OracleEngine()
result = engine.query("What is the future of autonomous systems?")

print(f"Confidence: {result['total_confidence']}")
print(f"Consensus: {result['consensus']}")
print(f"Synthesis: {result['synthesis_text']}")

for a in result["analyses"]:
    print(f"  {a['name']}: {a['insight'][:80]}")
```

## Run Tests

```bash
python -m pytest test_oracle.py -v
```

## Philosophy

The Oracle doesn't give you one answer. It gives you the truth as seen from six different angles, and the consensus where they agree.

> "The unexamined answer is not worth having." — The Philosopher

## License

MIT
