# teco-industry-insights-sales-activation

A Codex skill that turns verified B2B industry intelligence into commercial opportunities and buyer-relevant sales content.

## What it does

The skill can establish a company and product baseline, monitor a weekly market window, analyze consumer shifts, regulation, supply chains and major-brand activity, score commercial opportunities, apply SCRP and draft:

- Cold email
- LinkedIn message
- WhatsApp message
- LinkedIn post
- Internal intelligence report

It separates facts, company claims, weak signals, inference and recommendations. It does not automatically send or publish content.

## Inputs

Provide the industry, company, products, target countries, buyer roles and desired outputs. For repeated use, copy `references/configuration-template.md` into a private project file and complete it.

## Outputs

A report leads with decision implications and ranked opportunities, followed by evidence, SCRP analysis and the requested outreach drafts. Significant claims include direct sources and limitations.

## Installation

Copy or clone this repository into your Codex skills directory:

```bash
git clone https://github.com/tecoatwork/teco-industry-insights-sales-activation.git ~/.codex/skills/teco-industry-insights-sales-activation
```

Restart or reload Codex if the skill is not discovered immediately.

## Example prompts

```text
Use teco-industry-insights-sales-activation in baseline mode to understand our company, products, buyers and priority markets.
```

```text
Run weekly mode for the past seven days. Identify no more than three validated opportunities and draft a LinkedIn post and buyer message.
```

```text
Use full mode for our professional beauty-equipment business in Germany and the UAE. Separate current law from proposals and label all company claims.
```

## Dependencies

The skill does not require a specific research provider. Use the web-search, browser or public-data tools available in the current environment. Private company configuration should remain outside this repository.

## Validation scope

The package is structurally validated with Codex's skill validator. That check covers skill naming, frontmatter and scaffold completeness; it does not independently validate every future market claim. Each research run must perform its own source and claim audit.

## License

MIT. See `LICENSE`.
