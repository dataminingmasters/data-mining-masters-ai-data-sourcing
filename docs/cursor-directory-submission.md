# Cursor Directory submission draft

Prepared November 2, 2026. Target: https://cursor.directory/plugins/new

## Listing fields

**Name:** AI Data Sourcing

**Publisher:** Data Mining Masters

**Homepage:** https://dataminingmasters.com/

**Description:** Find AI data providers, compare licensing options, and prepare
partnership briefs. Three skills help developers source datasets and help data
owners assess licensing partners using public sources, explicit requirements,
and clear evidence gaps. No API key or hosted server required.

**Keywords:** AI data, data licensing, datasets, training data, data providers,
data partnerships

**Proposed repository name:** data-mining-masters-ai-data-sourcing

**Repository URL:** https://github.com/dataminingmasters/data-mining-masters-ai-data-sourcing

## Components the repository scan should find

- `skills/dmm-find-data-providers/SKILL.md`
- `skills/dmm-compare-data-providers/SKILL.md`
- `skills/dmm-prepare-data-partnership/SKILL.md`

The package is intentionally skills-only. It does not need `.mcp.json` or a
server URL. Its root `plugin.json` uses the Agent Plugins standard.

## Publication sequence

1. Create the public repository under the intended publisher account and upload
   the source contents with `plugin.json` and `skills/` at the repository root.
2. Add the actual repository URL to `plugin.json` and the listing draft.
3. Sign in to Cursor Directory and scan the public repository URL.
4. Check that the scan finds all three skills and the homepage is correct.
5. Submit the listing; record the returned URL and its actual moderation state.
6. Once publicly visible, verify anonymous access, the homepage link destination
   and link attributes, and whether the page permits indexing. Measure referrals
   rather than assuming a ranking or AI-visibility gain.

GitHub publication, directory submission, listing acceptance, indexing, and
official Cursor Marketplace approval are separate states. None is implied by
this package. OpenAI's public plugin directory is not the submission target.
