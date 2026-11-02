# Validation record

Version 1.0.0 — November 2, 2026.

## Package checks

- All three skills passed the Skill Creator frontmatter and naming validator.
- Root manifest parsed successfully; required schema identifier, name, semantic
  version, supported category, field types, and listing text limits checked.
- All three skill folders have matching names, descriptions, UI metadata, and
  contained references. The listing subtitle is 30 characters.
- Local Markdown references resolved; the package contains no credentials,
  private app bindings, MCP endpoints, executable hooks, or dependencies.
- The final ZIP was inspected after packaging for its expected components,
  relative paths, and byte-for-byte agreement with the source files.

## Independent task runs

Three separate agent runs were given the skill and a realistic request without
an expected answer. The actual outputs were inspected.

| Task | Observed result |
|---|---|
| Find licensed English/Spanish conversational audio for commercial training | Returned three plausible buyer routes, used primary provider sources, labeled provisional alternatives, and identified differences between commercial and academic licenses. No outreach or purchase occurred. |
| Compare three hypothetical offers against a $10,000 cap, training use, and no exclusivity | Excluded the conflicting exclusive offer, calculated the second offer's base price without assuming missing fees were zero, and advanced the third conditionally while preserving missing rights evidence. Used only supplied excerpts. |
| Prepare a brief from an inventory with unreviewed client/employee permissions | Preserved the combined record count, did not claim completed de-identification or licensing authority, proposed a metadata-only first step, and produced an unsent inquiry. Used only the hypothetical inventory. |

These are observed examples, not a guarantee of every future model response.
Live sources can change and the host agent's tool access affects research.

## Checks that require the target environment

- Cursor's own import UI was not exercised; the package uses the currently
  documented Agent Plugins format and local-import layout.
- Repository publication and community-directory moderation are separate from
  functional validation. Consult the live repository and listing for their state.
- No indexing, ranking benefit, or official Cursor Marketplace approval is
  implied by the package or its tests.

