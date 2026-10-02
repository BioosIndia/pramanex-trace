# Validation Case Matrix

This matrix converts the publication's declared validation cases into repository-ready acceptance specifications.

| Case | Required state | Release rule |
|---|---|---|
| Normal | Expected bounded candidate and explicit release checks | Pass only against frozen expected outcome. |
| Missing source | Evidence gap / request evidence | No unsupported critical field may be released. |
| Contradictory source | Conflict state / HOLD | Do not collapse disagreement into a settled claim. |
| Inaccessible source | Source-health failure | Do not report no-change. |
| Unauthorized retrieval | DENIED / no semantic match | No prohibited content may be laundered through synthesis. |
| Stale review | Reject prior approval | Recheck authority against exact candidate revision. |
| Unsafe tool | Quarantine / no side effect | Write action remains separately scoped and denied. |

## Test execution rule

For every case, preserve expected state, observed state, evidence used, candidate revision, reviewer decision, and terminal outcome. A test passes only when both the candidate behavior and the refusal/failure behavior match the frozen expectation.
