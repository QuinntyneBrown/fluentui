# Fluent UI detailed designs

This tree describes current architecture and conformance gaps against the confirmed requirements. It covers 44 L2 requirements in 19 feature designs across six subsystems. Coverage retains the representative-component limits of the requirements baseline.

The [L1 scope](../specs/L1.md) and [L2 acceptance criteria](../specs/L2.md) remain the sources of truth. The source baseline is commit `6fdc7bd448`. The additional design review occurs on 2026-10-04.

## Feature designs

| Subsystem | Feature | L2 coverage |
| --- | --- | --- |
| `react-ui` | [Activate Button](react-ui/activate-button/README.md) | `L2-001`, `L2-002`, `L2-010` |
| `react-ui` | [Edit Input](react-ui/edit-input/README.md) | `L2-003`, `L2-004` |
| `react-ui` | [Customize controls](react-ui/customize-controls/README.md) | `L2-005`, `L2-006`, `L2-032`, `L2-033` |
| `react-ui` | [Validate accessible controls](react-ui/validate-accessible-controls/README.md) | `L2-011`, `L2-012`, `L2-042` |
| `react-ui` | [Open and dismiss Menu](react-ui/open-and-dismiss-menu/README.md) | `L2-043` |
| `provider` | [Apply theme and document context](provider/apply-theme-and-document-context/README.md) | `L2-007`, `L2-008`, `L2-009`, `L2-013`, `L2-014`, `L2-038` |
| `provider` | [Render and hydrate controls](provider/render-and-hydrate-controls/README.md) | `L2-015`, `L2-016` |
| `web-components` | [Register and theme elements](web-components/register-and-theme-elements/README.md) | `L2-017`, `L2-018`, `L2-020`, `L2-026` |
| `web-components` | [Activate form Button](web-components/activate-form-button/README.md) | `L2-019` |
| `charts` | [Inspect chart data](charts/inspect-chart-data/README.md) | `L2-021`, `L2-022`, `L2-023` |
| `charts` | [Resize chart](charts/resize-chart/README.md) | `L2-044`, `L2-006`, `L2-032` |
| `delivery-tooling` | [Verify React compatibility](delivery-tooling/verify-react-compatibility/README.md) | `L2-024`, `L2-025` |
| `delivery-tooling` | [Publish consumable APIs](delivery-tooling/publish-consumable-apis/README.md) | `L2-027`, `L2-028` |
| `delivery-tooling` | [Measure performance](delivery-tooling/measure-performance/README.md) | `L2-029` |
| `delivery-tooling` | [Verify bundle isolation](delivery-tooling/verify-bundle-isolation/README.md) | `L2-030`, `L2-031`, `L2-038`, `L2-040` |
| `delivery-tooling` | [Validate requirement coverage](delivery-tooling/validate-requirement-coverage/README.md) | `L2-034`, `L2-036` |
| `delivery-tooling` | [Record package changes](delivery-tooling/record-package-changes/README.md) | `L2-035` |
| `consumer-guidance` | [Configure library consumers](consumer-guidance/configure-library-consumers/README.md) | `L2-037` |
| `consumer-guidance` | [Preserve security boundaries](consumer-guidance/preserve-security-boundaries/README.md) | `L2-039`, `L2-040`, `L2-041` |

## Requirement coverage

| L2 | L1 parent | Feature designs |
| --- | --- | --- |
| `L2-001` | `L1-001` | [Activate Button](react-ui/activate-button/README.md) |
| `L2-002` | `L1-001` | [Activate Button](react-ui/activate-button/README.md) |
| `L2-003` | `L1-001` | [Edit Input](react-ui/edit-input/README.md) |
| `L2-004` | `L1-002` | [Edit Input](react-ui/edit-input/README.md) |
| `L2-005` | `L1-002` | [Customize controls](react-ui/customize-controls/README.md) |
| `L2-006` | `L1-002` | [Customize controls](react-ui/customize-controls/README.md), [Resize chart](charts/resize-chart/README.md) |
| `L2-007` | `L1-003` | [Apply theme and document context](provider/apply-theme-and-document-context/README.md) |
| `L2-008` | `L1-003` | [Apply theme and document context](provider/apply-theme-and-document-context/README.md) |
| `L2-009` | `L1-003` | [Apply theme and document context](provider/apply-theme-and-document-context/README.md) |
| `L2-010` | `L1-004` | [Activate Button](react-ui/activate-button/README.md) |
| `L2-011` | `L1-004` | [Validate accessible controls](react-ui/validate-accessible-controls/README.md) |
| `L2-012` | `L1-004` | [Validate accessible controls](react-ui/validate-accessible-controls/README.md) |
| `L2-013` | `L1-005` | [Apply theme and document context](provider/apply-theme-and-document-context/README.md) |
| `L2-014` | `L1-005` | [Apply theme and document context](provider/apply-theme-and-document-context/README.md) |
| `L2-015` | `L1-006` | [Render and hydrate controls](provider/render-and-hydrate-controls/README.md) |
| `L2-016` | `L1-006` | [Render and hydrate controls](provider/render-and-hydrate-controls/README.md) |
| `L2-017` | `L1-006` | [Register and theme elements](web-components/register-and-theme-elements/README.md) |
| `L2-018` | `L1-007` | [Register and theme elements](web-components/register-and-theme-elements/README.md) |
| `L2-019` | `L1-007` | [Activate form Button](web-components/activate-form-button/README.md) |
| `L2-020` | `L1-007` | [Register and theme elements](web-components/register-and-theme-elements/README.md) |
| `L2-021` | `L1-008` | [Inspect chart data](charts/inspect-chart-data/README.md) |
| `L2-022` | `L1-008` | [Inspect chart data](charts/inspect-chart-data/README.md) |
| `L2-023` | `L1-008` | [Inspect chart data](charts/inspect-chart-data/README.md) |
| `L2-024` | `L1-009` | [Verify React compatibility](delivery-tooling/verify-react-compatibility/README.md) |
| `L2-025` | `L1-009` | [Verify React compatibility](delivery-tooling/verify-react-compatibility/README.md) |
| `L2-026` | `L1-009` | [Register and theme elements](web-components/register-and-theme-elements/README.md) |
| `L2-027` | `L1-010` | [Publish consumable APIs](delivery-tooling/publish-consumable-apis/README.md) |
| `L2-028` | `L1-010` | [Publish consumable APIs](delivery-tooling/publish-consumable-apis/README.md) |
| `L2-029` | `L1-011` | [Measure performance](delivery-tooling/measure-performance/README.md) |
| `L2-030` | `L1-011` | [Verify bundle isolation](delivery-tooling/verify-bundle-isolation/README.md) |
| `L2-031` | `L1-011` | [Verify bundle isolation](delivery-tooling/verify-bundle-isolation/README.md) |
| `L2-032` | `L1-012` | [Customize controls](react-ui/customize-controls/README.md), [Resize chart](charts/resize-chart/README.md) |
| `L2-033` | `L1-012` | [Customize controls](react-ui/customize-controls/README.md) |
| `L2-034` | `L1-013` | [Validate requirement coverage](delivery-tooling/validate-requirement-coverage/README.md) |
| `L2-035` | `L1-013` | [Record package changes](delivery-tooling/record-package-changes/README.md) |
| `L2-036` | `L1-013` | [Validate requirement coverage](delivery-tooling/validate-requirement-coverage/README.md) |
| `L2-037` | `L1-014` | [Configure library consumers](consumer-guidance/configure-library-consumers/README.md) |
| `L2-038` | `L1-014` | [Apply theme and document context](provider/apply-theme-and-document-context/README.md), [Verify bundle isolation](delivery-tooling/verify-bundle-isolation/README.md) |
| `L2-039` | `L1-015` | [Preserve security boundaries](consumer-guidance/preserve-security-boundaries/README.md) |
| `L2-040` | `L1-015` | [Verify bundle isolation](delivery-tooling/verify-bundle-isolation/README.md), [Preserve security boundaries](consumer-guidance/preserve-security-boundaries/README.md) |
| `L2-041` | `L1-015` | [Preserve security boundaries](consumer-guidance/preserve-security-boundaries/README.md) |
| `L2-042` | `L1-016` | [Validate accessible controls](react-ui/validate-accessible-controls/README.md) |
| `L2-043` | `L1-016` | [Open and dismiss Menu](react-ui/open-and-dismiss-menu/README.md) |
| `L2-044` | `L1-016` | [Resize chart](charts/resize-chart/README.md) |

## Architecture interpretation

- Browser libraries execute within consumer applications. No library-owned authentication service, database, or application API is inferred.
- Server-rendering diagrams identify a consumer-owned server process. Tooling sequences use Backend for local or CI processes rather than a deployed service.
- Type diagrams project real records, function modules, platform interfaces, and explicitly proposed artifacts. Hooks remain functions.
- Requirement tables preserve source wording, including `must`. Surrounding prose uses the skill's `shall` convention for obligations.
- Sequence diagrams distinguish observed behavior from acceptance-review targets. Source evidence alone does not establish passing runtime coverage.

## Conformance gaps and unresolved facts

- `ResponsiveContainer` uses `React.FC`, a chart browser utility, and library-last class merging. Required changes follow the agent instructions.
- `Input` imports `react-field`, contrary to the prescribed dependency boundary. Foundation ownership for remediation is `<TO SUPPLY>`.
- `DonutChart` uses `React.FunctionComponent` around `forwardRef`. Typing remediation preserves its public properties and ref.
- React peer declarations, the 17–19 app matrix, and explicit 17/18 PR targets describe different coverage layers. Successful execution is not inferred.
- Numeric latency, throughput, memory, and maximum bundle-byte budgets are `<TO SUPPLY>`. Minimum browser release versions are `<TO SUPPLY>`.
- Full security instrumentation, viewport/visual-mode coverage, coexistence, and isolated tarball consumption remain unverified acceptance targets.

## Artifact validation

The artifact set contains 19 feature READMEs, 115 PlantUML sources, and 115 sibling PNGs. The root index maps all 44 L2 requirements to at least one feature.

Diagram sources use offline C4 includes. Source syntax, requirement quotations, traceability, house style, links, and PNG decoding checks pass. Visual review covers all 19 feature sheets, including all 115 diagrams, with no clipping or layout failures identified.

Application acceptance tests are not executed for this documentation-only change. Repository dependencies remain unchanged. Document tasks use an isolated temporary Nx workspace because repository Nx modules are not installed.

With repository dependencies installed, the renderer runs through the bundled Yarn launcher:

```powershell
node .yarn/releases/yarn-4.18.0.cjs nx exec -- python "C:/Users/quinn/.codex/plugins/cache/agent-toolkit/agent-toolkit/0.2.0/skills/software-design-document/scripts/render_puml.py" docs/detailed-designs
```
