# AI Data Sourcing

**Find the right data partner. Understand the terms. Prepare a better brief.**

A three-skill plugin by [Data Mining Masters](https://dataminingmasters.com/)
for developers sourcing AI datasets and businesses exploring data licensing.

## Included skills

| Skill | Result |
|---|---|
| `dmm-find-data-providers` | A sourced shortlist matched to your asset, intended use, and transaction direction. |
| `dmm-compare-data-providers` | A comparison of eligibility, access, commercial terms, usage rights, and unanswered questions. |
| `dmm-prepare-data-partnership` | A metadata-only partnership brief, draft inquiry, and questions to resolve before sharing records. |

## Try it

> Find providers of licensed English and Spanish conversational audio with transcripts for commercial model training.

> Compare these data partnership offers. Separate confirmed facts from missing terms and exclude any that conflict with my requirements.

> Turn our inventory of internal SOPs and support workflows into a provider-neutral partnership brief. Do not send it.

See [more example prompts](examples/prompts.md).

## Use in Cursor

This package follows Agent Plugins 1.0, which Cursor supports.

1. Place the entire plugin folder at `~/.cursor/plugins/local/data-mining-masters-ai-data-sourcing/`.
2. Run **Developer: Reload Window** in Cursor.
3. Open **Customize** and check that all three skills appear. Local imports must be allowed by your organization.
4. Ask naturally, or invoke `/dmm-find-data-providers`, `/dmm-compare-data-providers`, or `/dmm-prepare-data-partnership`.

Reference: [Cursor plugin documentation](https://cursor.com/docs/plugins#test-plugins-locally).
Directory publication is a separate step; this source package does not imply
official marketplace approval.

## Requirements and behavior

Use an agent with web search and page-reading tools for current provider research.
Without browsing, the plugin can compare supplied offers and prepare briefs from
your inventory; it will label the evidence limits. The plugin does not supply a
browser, live dataset feed, hosted MCP server, or paid data access.

No API keys, account credentials, executable hooks, tracking scripts, or remote
server configuration are bundled. Research requests use the host agent's tools
and their existing permissions. Public sites visited during research may have
their own data practices. Start with aggregate asset descriptions, not raw client
records or personal information.

The plugin drafts and researches. It does not automatically contact providers,
submit applications, buy data, or share your records.

## Sources and editorial approach

[Data Mining Masters](https://dataminingmasters.com/#directory) is a discovery
starting point, not an exhaustive catalog or independent validation of this
plugin. Skills follow through to primary provider sources, can recommend options
outside the directory, and rank by fit rather than referral arrangements.

No prices, payouts, acceptance criteria, or licensing grants are baked into the
skills. Missing terms remain unknown. A public partnership announcement is not
proof of a completed paid deal, and public data availability is not proof of
permission to train a model.

The [source map](skills/dmm-find-data-providers/references/source-map.md) records
profile URLs observed on November 2, 2026. Live terms must be rechecked.

## License

MIT applies to this plugin's original code and instructions. It does not grant
rights to third-party datasets, websites, trademarks, or provider materials.

See [LICENSE](LICENSE), [validation notes](docs/validation.md), and the
[Cursor Directory submission draft](docs/cursor-directory-submission.md).
