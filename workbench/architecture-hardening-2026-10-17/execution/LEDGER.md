# Reliability migration execution ledger

**Current scope: the streamlined [authoritative plan](../FINAL-MIGRATION-CONTRACT.md) and [continuation](CONTINUE.md), revised at Aram's request on 18 October 2026. Earlier entries below are chronological evidence; their superseded extraction, audit, S9b and live-rollout obligations are not current requirements.**

Execution requested by Aram on 18 October 2026 in the current chat. The final contract is [FINAL-MIGRATION-CONTRACT.md](../FINAL-MIGRATION-CONTRACT.md); it supersedes conflicting execution details in MIGRATION-PLAN.md. The historical planning-only limitation does not restrict the source implementation now requested. Installation, publication, live content changes and exact candidate surface approvals retain their explicit gates.

## Historical entry baseline

- Implementer: this Codex chat; no delegated reviewer role assigned.
- Core: `074f4717e14527798752de84b3c9c4e88348b658`, clean at entry.
- UI: `a88b1188ad54439b4df32813904de182c06a105c`, clean at entry.
- Process inspection: no LearningOS, Obsidian, Muse or pytest process found; inspection itself excluded.
- Disk: 208 GiB available at entry.
- Outer dirty work is unrelated and excluded. See baseline receipt for exact byte inventory.
- Correction: **five** existing lineage writers (including source revision); evidence-bearing route.patch will be the sixth. Earlier four-writer statements are superseded.

## Acceptance status under the revised plan

The finite acceptance inventory is maintained only in the [current plan, §5](../FINAL-MIGRATION-CONTRACT.md#5-verification-and-finite-acceptance).

| Gate | Status |
|---|---|
| Baseline/completed claim work | Preserved; reconcile historical receipts with actual WIP before resumption. |
| C1 | Bounded read/audit isolation implemented; all 29 procedure differences classified; exact A11 applied. Refreshed 1,107 scenarios execute successfully and outputs reviewed; comparison-mode full paired gate remains pending. |
| C2 | Pending production transaction durability/conflict fixes and real fault/restart evidence. |
| C3 | Pending bounded simplification, compact workflow, UI/simple recovery and final acceptance. |
| S9b | Deferred; not an acceptance blocker absent a demonstrated required failure and separate review. |
| Live content/install/release | Outside revised migration scope; separate authorization required. |

## Historical execution entries

### Initial execution position

Persisted final amendments before implementation. Establish E0, then E1; no live learner state mutation.

## E1 decisions

- Freeze the 213 pre-migration production module paths. Every newly introduced module must appear in the maintained strict-mypy files list; imported typed values retain their types (`follow_imports=silent`, never `skip`). Reason: a one-time check does not maintain the boundary.
- Retain the raw innermost writer and allow helper attribution only through the immediate production caller. Reason: an unrelated engine stack frame must not authorize callback effects.
- Derive operational backup obligations from the existing capability catalogue, including internal commands, even before their first write. Reason: loader reads and an on-disk inventory both miss a newly declared handler-owned destination.
- Begin the finite persistence model with separate receipt visibility and durability. Reason: the reproduced failure occupies precisely that intermediate state; model and production crash witnesses remain distinct evidence.

E0 evidence: [baseline-receipt.json](baseline-receipt.json), [independent-inputs.json](independent-inputs.json), [outer-dirty-inputs.json](outer-dirty-inputs.json), captured `world/`, and raw settings under `vault-safety-baseline/`. Candidate data were populated from this frozen world, including ignored authored artifacts. Materials remain externally pinned by the captured per-file inventory; any later drift invalidates dependent evidence.

Focused checks before the retained E1 gate: 113 passed / one failed negative backup control exposed an omitted internal-command catalogue family in the new check; corrected it. The corrected targeted run passed 52 tests. No acceptance is inferred from the failed run.

## Progress after claim foundations

- E1 retained gate: [receipts/E1-enforcement/receipt.json](receipts/E1-enforcement/receipt.json), 128 passed / 1 skipped. The skip is the population-wide A19 witness check in a focused local run; it must execute with the full scenario population at C1.
- Maintained strict gate initially passed; it now covers five modules (transaction result, quotation matcher, immutable PDF reader, anchor reader and shared admission service). No stub/runtime dependency was added: the shared admission uses the existing rooted YAML loader.
- Initial candidate validation failed only on this task's initial mypy cache and a symlinked .venv that did not match the directory ignore rule. Removed the task-created cache and made .venv a real ignored directory containing runtime links. Regenerated disposable views through the generator. [receipts/E1-validation-clean/receipt.json](receipts/E1-validation-clean/receipt.json) proves 0 errors / the same 3 operational advisories.
- Implemented quotation normalization/bounds/language, a shared PDF byte reader, explicit parser/extraction refusals and immutable extraction in initial/continuation slices. The continuation call-site omission was caught and corrected; the corrected matcher/slices/types/layers run passed 99 tests.
- Implemented request-local exact material observations, no-text/unsupported fallbacks, transcript identity/grid/range checks, local-to-unresolved refusal and material replacement detection. [receipts/V2-real-inventory.json](receipts/V2-real-inventory.json): 894 active routes = 538 local / 70 local-unresolved / 286 remote-unanchored; all 382 transcripts parsed, zero failures. This classification is deliberately stricter than resolver existence buckets.
- Removed the former Phase B implementation from app/handlers/plan.py; shared typed app/claim_admission.py now admits edits and unchanged stale/contested judgments and renders digest-only lineage. Full audit-defect eligibility and shared read annotations remain pending with the scan slice.
- Added identical prospective lineage file guards to plan check/apply, source revision check/apply and synthesis publication; restamp already uses that exact fallback artifact. Narrowed the receipt verifier's empty ordinary-hash allowance to a correctly bound, exclusively ledger-only revision.
- Added both locator validation constraints and their controls. Captured real-world validation remains 0 errors / 3 existing advisories: [receipts/CLAIM-V4-validation/receipt.json](receipts/CLAIM-V4-validation/receipt.json).
- Latest focused ledger-only/receipt/acceptance run: 16 passed, including ledger-only check/apply/replay/receipt verification, authored-byte preservation, no excerpt persistence, ordinary-write missing-hash negative controls and shared-guard interposition under all five existing grants. This interposition drives the engine under those grants; actual handler-specific guard/application coverage remains required, including the sixth route.patch writer.
- The last broader run before correcting the synthetic acceptance fixture's duplicate locators had 145 passing / 2 failing tests, both that same now-forbidden fixture shape. Corrected that fixture's locators/placements/dossier references rather than exempting it. Its two affected scenarios pass in the latest focused run.
- Code reachability: 271/271 modules classified, 11 historical allowances; no new allowance. No C1 milestone claimed, no surface approval invented, no commit/push/install/live content write.

### Next work

Finish the remaining claim slice (route.patch evidence authority, complete goal occurrence/audit lifecycle and shared read annotations), source/material authority seam tests, historical broadcast controls, documentation and combined regeneration. Re-run affected focused seams, then prepare the exact combined A11 approval packet and C1 evidence. Durability S0/S1/S2 remain after C1 as ordered; the serious receipt-barrier production defect is modeled but **not yet fixed**.


## 5-percent usage handoff

Reached 95% used / 5% remaining in the five-hour window; stopped new implementation at Aram's requested threshold. Continuation authority, exact paths/HEADs, decisions, known seams, required order and paste-ready instruction are in [CONTINUE.md](CONTINUE.md). Exact candidate file hashes, statuses and preservation comparisons are in [continuation-state.json](continuation-state.json), with tracked patch and new-source archive alongside it.

Implemented candidate V7 route.patch evidence/schema/write grant and shared admission/check/apply lineage guard without inventing A11 approval. Its focused check/apply/refusal/replay tests passed. Broad integration exposed one real legacy-route compatibility issue and one obsolete material-evidence fixture: the former shared map helper omitted id-less routes, falsely making a descriptive edit a new claim. Admission now uses the existing route identity owner; fixtures use real PDF bytes, complete manifest rows and exact quote evidence.

Retained failed receipts: CLAIM-integration-before-scan (318 passed / 2 failed) and CLAIM-legacy-route-regressions (8 passed / 1 failed). Final corrected receipt: [CLAIM-corrected-integration](receipts/CLAIM-corrected-integration/receipt.json), **321 passed**, 72.37 seconds, exit 0 and source unchanged. Includes all six grants in the engine interposition test; actual all-six handler interleavings still remain. Maintained mypy gate passed five modules; touched-file ruff passed before the final fixture-only correction.

All command sessions completed. Original Core/UI clean, independently inventoried original inputs and unrelated dirty bytes unchanged. Candidate remains uncommitted and uninstalled. No C1/C2/C3 claimed. Serious production receipt-barrier defect still modeled only, not fixed. Estimated full migration work remaining: about 80% (75–85% uncertainty); this is engineering judgment, not test-count arithmetic.

## 18 October continuation: combined claim/status/audit implementation

Resumed from CONTINUE.md under Aram's current instruction to continue. Verified the original Core/UI clean, the independent authored/operational/vault inventory unchanged, unrelated outer dirty bytes unchanged, candidate HEADs/statuses preserved, no competing migration process, 207 GiB free, and account five-hour use 2% at resumption. No reset, delegation, commit, push, install or live write.

Decisions and reasons:

- Observe proposed source patches using an immutable shallow Repo replacement and retain the original registry separately for downgrade classification. Source-material changes re-admit affected positive claims even when the route row did not change. Reason: admission against the old binding can prove the wrong material.
- Pin the declared source material as `source-material:SOURCE_ID` on new positive judgments. The shared evidence observer resolves that key from the current registry. Reason: a later source revision must stale the judgment even if the route row and quoted file remain byte-identical.
- `derive/semantics/claim_status.py` owns bounded status observations and pure interpretation. Focused reads resolve only selected claims plus their assumption closure, once per evidence key. The scan, restamp, admission, plan reads and dossier use this owner; the duplicated scan freshness calculation and two obsolete staleness detectors were removed. Prior detector assertions are migrated to shared-status/merged-emitter tests; this is behavior migration, not campaign test thinning.
- Judgment basis excludes read shape/restamp/review metadata; stale occurrence includes the stable judgment and exact relevant current drift, recursively including blocking assumptions. Full 64-digit digests are retained. Reason: A → fresh → B must not reuse A's rejection; identical A deliberately reuses it.
- Immutable audits live in a separate `audits` map beside mutable decisions. Authorization binds the full current pool, supplied random seed, versioned seeded shuffle and exact sample; closure binds the preserved sample, report digest, actual reviewer and exact-basis defects. Server-retained review digests permit an exact no-effect replay without erasing later attention decisions. Reason: reject/defer/re-authorize cannot redraw or delete audit evidence.
- A failed audit certifies nothing and suppresses a new draw on the identical pool. Its exact-basis defects emit disputed goals; a repaired basis changes the eligible pool and can create the next audit. Historical closure verifies every frozen pair against current lineage or its supersedes history.
- Authorization measures intent and stays visible; rejection requires a note. Quieting uses one latest explicit non-deferred decision per occurrence, last 30 since the named detector reset, minimum 10 and Wilson 95% lower bound > 0.10. Only attention groups/resume suppress quiet detectors; full output retains them, marked quiet.
- Preserve the existing staged `route.patch` validation exit 2; new lineage admission refusals use exit 1. The detailed V5 draft assumed exit 1 for every branch, but changing the existing structural-validation outcome would be an unrelated behavior change. Tests require the observed branch and both named validation codes.

Evidence so far:

- `CLAIM-source-authority`: 58 passed; source unchanged. Source replacement/removal and malformed-input refusals.
- `CLAIM-status-owner`: 138 passed / 2 failed, observation spies still imported the former owner. Retained as failure; updated their imports.
- `CLAIM-status-reads`: 133 passed / 1 failed, batch/scalar assertion omitted the new sibling claim field. Source changed during this early run, so it is explicitly not reusable acceptance evidence.
- `CLAIM-audit-lifecycle`: 13 passed / 1 failed, below-threshold fixture incorrectly tried to sample 29 claims. Fixed fixture.
- `CLAIM-merged-scan-audit`: 146 passed / 3 failed, old output/required-note expectations. Fixed expectations without loosening the new rules.
- `CLAIM-combined-regressions`: 465 passed / 10 failed, callers still imported moved observation helpers and manual evidence maps omitted the new source-material pin. Source unchanged. Updated callers and explicit pin assertions.
- `CLAIM-corrected-owner-integration`: **312 passed**, 79.75 seconds, exit 0, source unchanged. Includes audits, lineage, restamp, module/unit plan revisions, source revision and dossier publication.
- Maintained strict mypy passes seven modules, including both new claim owners. Candidate captured-world scan now yields 25 goals: 21 lineage-stale, 3 study-map obligations and 1 claims-audit.
- Exact historical broadcast fixture extracted from damaged `51b0c5d3ae7baf69f58cbeb3f84d95c0b71da6f6` and repaired `074f4717e14527798752de84b3c9c4e88348b658`; origin/source-map hashes included. The real rows produce precisely 2 duplicate groups / 6 routes and 3 file mismatches; repaired rows produce none.

Still pending: complete historical/disabled controls, actual-handler all-six-writer interleavings, source-attach/dossier rebase coverage, docs and one combined schema/surface/parity/transcript refresh, bounded-read/admission timings, exact surface approval and C1. No C1/C2/C3 acceptance; the production visible-receipt rollback defect remains unfixed as required by the milestone order.

### Audited-child provenance correction (mandatory evidence limitation)

A startup probe confirmed that `PYTHONPATH=tests/arch_site` plus the shared editable Python environment loaded `learning_os.app._plan_gate` from the original checkout before the candidate script started. The installer in `sitecustomize` imports production modules early. Earlier audited-child scenario/procedure observations therefore cannot establish candidate behavior, regardless of their test result. This does not imply a live write: those processes used disposable fixture roots; original preservation remains independently checked.

Fixed the harness to prepend its own checkout's `tools/` before importing/installing the audit hook. A new child-process regression runs from an unrelated temporary cwd, checks the loaded production file against the exact candidate path, and requires installed/completed capture witnesses. `CLAIM-audit-source-provenance`: 19 passed, exit 0, source unchanged. Ordinary non-audited CLI and parent pytest observations remain focused evidence; fresh C1 must rerun the complete audited population with this correction.

`CLAIM-scenario-diff` (185 passed / 48 failed) was collected before that fix and is diagnostic only. `CLAIM-candidate-scenario-smoke` ran afterward: 28 passed / 11 recording differences, including intentional claim fields and corrected id-less route counts. Its source was unchanged; it is not acceptance. The goal batch's reviewed hash was recomputed through the actual candidate under the fixture's pinned clock after adding its required rejection note. Prior selected recordings were preserved under `recording-before-claim-slice/` before regeneration. Record mode now refuses a failed declared-success case or a successful declared-refusal case; regeneration is still followed by explicit effect/output diff review and comparison mode.

The actual five-key A11 packet is [C1-SURFACE-PACKET.md](C1-SURFACE-PACKET.md), with exact before/after objects in JSON. Aram was asked for dated approval asynchronously; no answer or approval row has been inferred. Preparation, fixtures and verification continue while it is pending. Source approval, C1 acceptance and rollout authorization remain distinct.

Other completed evidence: `CLAIM-broadcast-production-controls` 78 passed, including actual validator reruns with protections disabled; `CLAIM-cli-parity-corrected` 70 passed. The historical 1,786-case primary and 265-case supplement pins remain intact; only the affected primary command observations changed, while supplemental old-source bytes are preserved through a narrowly tested normalization of the three added defaults and two affected usage prefixes. New flags have separate tests rather than being appended to the frozen corpus.


## Final resumed checkpoint at 5%

Stopped implementation at 95% used / 5% remaining (weekly 45%); all started checks collected. See the final resumed checkpoint in CONTINUE.md and resumed-checkpoint.json. Original Core/UI clean and independent authored/operational/vault/outer-dirty comparisons unchanged. No commit, push, install, live write, delegation or reset. About 75% of the full migration remains (70–80% engineering estimate); C1/C2/C3 are unaccepted.

Actual-handler interpositions now pass all six writers, with source replacement and rebase and disabled-protection controls (7 tests). Real PDF evidence and 20-claim cache timing pass. Read budgets pass all 20 paired runs; source type/lint/layer/reachability/validation/warning/UI contract controls pass. Selected candidate scenario comparison passes 233 with 874 deselected. Full population/A19 and C1 remain pending.

Private runtime and audit-startup provenance were repaired; prior audited-child observations and the stopped recursive-prefix procedure attempt are not acceptance evidence. The corrected procedure run attempted 36: 7 passed, 29 failed expectation comparisons. Inspected examples have stale snapshot outputs; every remaining diff must be classified before update. No transcript was blindly re-recorded.

The five-key surface packet remains awaiting Aram's dated approval. No approval row was fabricated. Durability S0/S1/S2 have not begun and the visible-receipt production rollback defect remains. Exact receipts, source digests, preservation and next steps are in CONTINUE.md.


## C1 surface approval — 18 October 2026

Aram explicitly replied “Approve this exact C1 surface packet”. Recorded at `2026-10-18T12:33:40.070403+00:00` in [C1-SURFACE-APPROVAL.json](C1-SURFACE-APPROVAL.json), bound to immutable packet SHA256 `8e7781d6d10071e25eb0bc51cc0d068bbecffd51340946f1d82a7c107c31d2cf` and its five exact before/after keys. This supersedes earlier pending-approval notes. Candidate A11 baseline entries remain to be applied and verified at authorized resumption; source and implementation stay paused at the usage boundary. C1 remains unaccepted, with no rollout or live-content authorization.


## Scope simplification and plan publication — 18 October 2026

Aram supplied the revised v2 and explicitly directed improvement/maximization/streamlining of existing architecture without bloat, then authorized pushing updated planning documents to the migration branch. Replaced the authoritative contract, retired competing entry plans, preserved their exact originals/hashes, and rewrote the continuation. Audit expansion, unnecessary extraction and default S9b protocols are removed from required scope. C1/C2/C3 remain finite gates; production transaction correctness takes priority. Existing compact multi-unit revisions are verified to exist and must be reused.

Observed the preserved implementation at Core `300a04a920a31f62734b7e367b618dca3faeb1bf` on `review/architecture-hardening-2026-10-18`; UI `a88b1188ad54439b4df32813904de182c06a105c`. Earlier tips and estimates remain historical. This plan revision changes no production code, data or acceptance result; implementation remains paused at the recorded usage boundary. Publishing plan documents is authorized; deployment, live writes and broader code commits are not authorized by this turn.


## Targeted audit amendments and plan freeze — 18 October 2026

Checked the audit's source claims against Core `c0365af0f2ca2b8f04e76cc17cb427a0011a8d7d` and UI `a88b1188ad54439b4df32813904de182c06a105c`. `_inspect_commit_receipt` validates schema/transaction/status but does not bind the effects before journal removal; UI recovery transitions operate on current state without an expected-request argument; the definitive-no-commit classification crosses existing Core/UI layers. These observations justify stronger tests/requirements, not claims that new failures were reproduced or fixed.

Amended only the authoritative plan and continuation: exact recovery-evidence consistency, C2 wire/UI uncertainty, practical S9a recovery and stale-result ownership; focused macOS capability evidence, write-boundary revalidation of request-local observations, measurable compact-editing friction and cheaper focused-before-broad verification. Permit only a frozen disposable S1 investigation if procedure analysis becomes prolonged; C1 reconciliation still precedes integration/C2 acceptance. No new framework or default S9b expansion. The plan is frozen for implementation, not another broad redesign.

This turn changes planning documents only; the existing usage pause, C1 approval and release/live-write boundaries remain. No production acceptance tests were run and no new acceptance result is asserted. Publish these three planning documents to the already authorized migration branch.


## Tested implementation resumed after the final commit review — 18 October 2026

Aram's attached final review directs implementation while preserving `d4ac02e6`, without another plan revision. Resumed at 24% used / 76% remaining in the five-hour window; retain the stop at 5% remaining. Original authored/operational/vault inventory and unrelated outer dirty bytes exactly match retained baselines; 206 GiB free; scoped process inspection found no competing migration job. Candidate imports resolve to its private venv and own production path. Evidence: resumption-review-implementation-20261018.json.

Carry five implementation clarifications into the existing test families: retirement requires durable prevention of future execution of the original identity, not receipt/process absence; recovery verification is version-aware (conservative V1, stronger V2, no invented historical hashes); final C3 reruns complete C2 wire/UI uncertainty and exact replay after S4/S8/S9a; successful acknowledgment requires a stated platform persistence minimum, with unsupported requirements failing acceptance unless an explicitly weaker guarantee is chosen before deployment; ordinary recoverable interruptions reconcile automatically or through one deliberate Diagnostics action, without manual transaction-file edits. Reuse store/evidence.py verification primitives only where their evidence requirements fit; no second verifier framework. These are acceptance clarifications, not a new architecture plan.

Implemented one immutable request-local ledger observation shared through scan, ranking, hidden decisions and brief metrics; basic claim evidence has no audit dependency. Ordinary plan/dossier reads enrich opportunistically and mark unavailable membership explicitly. Complete audit-queue scans remain strict, and a fresh supported rejudgment reads current audit authority independently of any old observation. Added actual read interposition, immutable-value, malformed/invalid-UTF8 inspection and independent-write check regressions.

C1-ledger-observation-first: 95 passed / 1 failed (new fixture omitted its parent directory), source unchanged; retained. C1-audit-boundary-focused: 1 passed after fixing the fixture. C1-observation-integrated: 279 passed in 96.92 seconds, source unchanged. Strict mypy (7 files) and full ruff pass. C1-architecture-and-types: 138 passed / 1 failed (old alias-purity test omitted the exact later approved schema changes). The narrowly byte-bound approval check now passes all 3 affected tests in C1-approved-request-ratchet. No generalized schema allowance was added.

Verified current live surface equals exactly all five approved packet before/after values, and applied only those dated A11 rows. Packet and approval receipt remain immutable. Classified all 29 retained procedure differences in receipts/C1-procedure-diff-classification.json: most are contract/snapshot digests; two positive material-edit examples need admitted fixture quotations; one reports added claim impacts; the merged detector count changes three groups to two; backup population adds the explicitly declared goal ledger. Positive inputs are being repaired before proposing output refreshes; update mode is not acceptance. C1/C2/C3 remain pending. No production commit/push, installation, live mutation or delegation.

## C1 comparison preparation — 18 October 2026

Implemented one immutable request-local goal-ledger observation through base/ranked scans and actual full/brief handlers. Tests interpose the actual byte read, mutate the ledger after it, and verify one read and coherent results; a later independent request sees the change. Basic evidence freshness does not read audit storage. Ordinary plan/dossier inspection exposes unavailable audit enrichment, while audit-dependent scans/authorization/rejudgments validate their current relevant state and refuse malformed/revoked evidence. The integrated focused receipt retains 279 passes; no new production module or persistent cache was added.

Classified all 29 historical procedure failures before refreshing expectations. Two positive material-edit examples now supply exact quotations from the real fixture lecture; their locator and immutable file identity agree. The corrected first comparison passed all 36 transcripts. Plan publication itself exposed an undeclared `workbench` root; declared it in the existing tree contract, regenerated architecture/views, and obtained zero validation errors with the same three operational advisories. This contract change invalidated old fixture snapshot assertions, so old comparison receipts are retained but do not prove the final source.

Rebound only known stale initial fixture snapshots, valid approval subjects, and dependent delivery-file hashes; intentionally incorrect guards stay incorrect. The two exact documented envelope-byte assertions were derived from freshly sealed envelopes, not removed. Final procedure proposals executed 36/36; reviewed merge changed 28 output expectations only, with all original commands/heredoc bytes and expected exit statuses preserved. Details: receipts/C1-document-envelope-rebindings.json and C1-final-procedure-expectations-applied.json. Proposal mode is not acceptance.

Full scenario recording: 1,107 passed in 698.97 seconds (C1-full-scenario-recording). Recording intentionally changed goldens and overlapped only procedure-output/comment cleanup; its source-unchanged flag is false and it is not comparison acceptance. Compared all refreshed recordings against the immutable before-c1-contract-rebind copy: 190 changed cases, no exit/outcome/canonical-effect changes, unchanged revisions/authority grants. All nine structural-change families are classified; backup adds only the fixture goal ledger, capability output reflects the exact approved route.patch packet, and source/judgment commits reflect deterministic fixture provenance. Changed receipt-effect digests are confined to rebound AI request metadata; authored delivery effects are identical. Details: C1-full-recording-review.json, C1-full-recording-delta-classification.json and C1-recording-review-conclusion.json.

Read-performance remeasurement against the retained baseline is underway in C1-final-read-performance. Next: freeze the final source and run the complete comparison-mode paired gate (including all scenarios, A19 and procedures). C1/S0/C2/C3 remain unaccepted until their actual required evidence exists. No source commit/push, installation or live learner mutation occurred.

Final alternating read measurement (20 pairs per command, retained same-world baseline): brief p95 1.7301 → 1.7066 seconds, route 0.9599 → 0.9491, dossier 1.1286 → 1.1259. All budgets met; receipt C1-final-read-performance has unchanged source. Starting C1-paired-final in comparison mode against settled source. Its completion receipt, not this entry, determines acceptance.

C1-paired-final stopped after seven early historical-control failures: 873 passed, 7 failed, 1 deselected in 87.36 seconds; unchanged source, no acceptance. Six engine records differed only in seven current contract/schema input hashes and their bound snapshot digests; retained the exact prior engine baseline, actual records and recursive deltas before refreshing these expectations. Historical D16/D4 comparisons now share the existing schema-delta helper and undo only exact byte-bound later C1 changes using the immutable approved packet. No arbitrary field/schema allowance. Focused C1-historical-contract-controls passes all 86 tests, including existing mutation negatives, source unchanged. Starting C1-paired-recheck with stop-on-first-failure; a successful run still executes the entire population.

Correction: preserving historical baselines means the S03 engine oracle itself must remain byte-identical. Restored tests/architecture/engine-baseline.json exactly to HEAD, and pinned only the existing disposable fixture contract/schema inputs to the original 074f4717 source. The first archive trial accidentally restored the deliberately omitted host-local attachment policy (6 failed/80 passed); restricted extraction to the fixture files already present. C1-frozen-engine-fixture-recheck: 86 passed in 6.81 seconds, source unchanged; lint passes. The prior proposed engine expectation refresh is superseded, with all its evidence retained. C1-paired-recheck was deliberately interrupted before this correction (1,147 passed, 1 deselected, exit 2, unchanged); it is not acceptance. Starting C1-paired-frozen-inputs against corrected settled source.

Read-only disposable production witness S1-receipt-parent-production-red-witness.json reproduces receipt-visible parent-fsync EIO causing backward data rollback behind a retained receipt. This does not modify candidate source or establish C2 acceptance. It identifies the first regression to implement after C1/S0.

## Published WIP stop requested — 18 October 2026

Aram explicitly requested publication of the current state and continuation, then stopping. This authorizes this checkpoint source commit/push to the existing migration branch. Deliberately interrupted only this chat's pytest child; C1-paired-frozen-inputs completed with exit 2, 1,920 passed / 1 deselected in 483.74 seconds, source unchanged. Lint, types, reachability, validation and warning baseline passed first; no complete paired acceptance or UI stamp. Full C1/S0/C2/C3 remain pending. No source work follows publication. Original Core/UI and unrelated dirty bytes were independently unchanged at the latest preservation capture. Checkpoint evidence is published beside this ledger; full raw/local evidence remains intact. The source checkpoint does not authorize installation, live mutation, main merge or delegation.
