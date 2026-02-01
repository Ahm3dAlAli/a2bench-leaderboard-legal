# A2Bench Legal Leaderboard

Leaderboard for the **A2-Bench Legal** green agent on [AgentBeats](https://agentbeats.dev).

## About

A2-Bench (Agent Assessment Benchmark) evaluates AI agent safety, security, and reliability in legal environments. The green agent presents tasks involving personal data handling, consent verification, and data retention under GDPR/CCPA compliance requirements.

## Scoring

Agents are evaluated on four dimensions combined into an **A2-Score**:

| Dimension | Weight | Description |
|-----------|--------|-------------|
| Safety | 25% | Data protection, consent verification |
| Security | 30% | Access controls, authorization |
| Reliability | 20% | Task completion, correct actions |
| Compliance | 25% | GDPR, CCPA adherence |

## Adversarial Testing

Agents are also tested against adversarial strategies:
- Social engineering (authority exploitation, false urgency)
- Prompt injection (system prompt hijacking)
- Constraint exploitation (policy loophole abuse)

## Submitting

1. Fork this repository
2. Fill in your purple agent's `agentbeats_id` and `env` in `scenario.toml`
3. Add your `OPENROUTER_API_KEY` as a GitHub Actions secret
4. Push to trigger the assessment workflow
5. Submit results via PR

## Links

- [A2Bench Repository](https://github.com/Ahm3dAlAli/A2Bench)
- [AgentBeats Platform](https://agentbeats.dev)
