# Continue the streamlined LearningOS migration

Paused at Aram's explicit request on 18 October 2026 after publishing the current WIP. The authoritative [migration contract](../FINAL-MIGRATION-CONTRACT.md) remains frozen: improve and streamline existing owners, avoid bloat, and preserve completed work. Do not start another planning round.

## Exact state

- GitHub branch: `review/architecture-hardening-2026-10-18` in `Aram164/LearningOS`. This checkpoint follows `d4ac02e6924ec0dac075e13e48d704f8656023fd`; use the actual checkpoint branch tip when resuming.
- Local execution root: `/Users/aramaljanadi/Desktop/semestercontext/LearningOS/workbench/architecture-hardening-2026-10-17/execution`.
- Core implementation: `execution/candidate/repository`; UI: sibling `execution/candidate/obsidian-ui`, unchanged at `a88b1188ad54439b4df32813904de182c06a105c`.
- Original Core remains `074f4717e14527798752de84b3c9c4e88348b658`. Original Core/UI are clean; authored/operational/vault bytes and unrelated outer dirty bytes were independently verified unchanged in `continuation-state.json` on 18 October 2026.
- The active gate was deliberately interrupted at Aram's stopping request. It is finished, not a background job to await. Do not infer acceptance from its green partial output.

## Completed implementation and evidence

The existing scan/ranking/handler path shares one immutable request-local goal-ledger observation. Actual byte-read interpositions prove one read and coherent full/brief results despite a subsequent ledger change. Ordinary freshness and plan/dossier inspection survive isolated malformed audit enrichment, explicitly marking it unavailable. Audit-dependent scans, authorization and rejudgments validate current relevant evidence and refuse malformed/revoked audits. No new production module or persistent cache was added.

- Focused integrated claim/admission/interposition checks: **279 passed** (`C1-observation-integrated`).
- Final focused architecture/contract/engine controls: **86 passed** (`C1-frozen-engine-fixture-recheck`). Historical engine baseline remains byte-for-byte unchanged; its fixture contracts are pinned to the original inputs. Exact later C1 changes are checked against the immutable approval packet by the existing shared schema-delta helper.
- All 29 historical procedure differences classified. Two positive material-edit examples now provide exact fixture quotations. First corrected comparison: **36/36 passed**. Later contract-input correction required final output rebinding; **36/36 final proposals executed**, with original commands, heredocs and expected exit codes preserved. Final comparison still required.
- Full scenario recording: **1,107 passed**. Reviewed all **190** refreshed cases: no exit/outcome/canonical-effect differences; revisions and authority grants unchanged. Recording is not comparison acceptance.
- Final alternating performance measurement: 20 pairs per command against the retained same-world baseline. Brief p95 **1.7301 → 1.7066 s**, route **0.9599 → 0.9491 s**, dossier **1.1286 → 1.1259 s**. All budgets passed.
- Latest full paired gate `C1-paired-frozen-inputs`: lint/types/reachability/validation/warning baseline passed; **1,920 tests passed, 1 deselected**, then deliberate interruption (exit **2**, source unchanged). Full scenarios/A19/procedures/UI and pair stamp were not completed by this run.
- Exact five-key C1 approval already verified and applied. Preserve packet SHA256 `8e7781d6d10071e25eb0bc51cc0d068bbecffd51340946f1d82a7c107c31d2cf` and historical approval receipt unchanged; do not ask again.

The [checkpoint evidence](checkpoint-2026-10-18/CHECKPOINT.json) contains portable summaries/raw outputs and hashes/locations for fuller local evidence. Full raw receipts, immutable before copies, private runtime and captured world remain under the local execution root. They were not replaced by the published summary.

## Continue in this order

1. Read the frozen contract, this continuation and latest [ledger](LEDGER.md) entries. Reconcile branch tip, dirty files, processes, current usage, private-runtime imports and original-state preservation. No competing owner or delegation is assumed. Do not reset/rebuild the candidate or recapture the original baseline.
2. Run the complete comparison-mode paired gate once against the checkpoint. On the retained local checkout:

   ```sh
   cd /Users/aramaljanadi/Desktop/semestercontext/LearningOS/workbench/architecture-hardening-2026-10-17/execution/candidate/repository
   .venv/bin/python ../../run_receipt.py C1-paired-after-checkpoint -- env PYTEST_ADDOPTS='-m "not live_install" --maxfail=1 --tb=short' make system-check
   ```

   On another checkout, use the same `make system-check` with the sibling UI at the exact listed revision and the documented test runtime. The local receipt wrapper is execution evidence tooling, not a required production component. Diagnose any first failure and pass a focused reproduction before another broad run. Do not blindly re-record expectations or change historical baselines.
3. Accept **C1 only after** complete scenario population/A19, all procedure comparisons and the full paired gate actually pass. Then record S0 as the accepted claim source/input baseline, retaining source hashes and the current source bytes before transaction edits.
4. Add the production S1 regression first. `S1-receipt-parent-production-red-witness.json` reproduced an actual receipt-visible parent-fsync EIO that rolls data backward while retaining the receipt. Fix it in the existing transaction run with the three publication states specified by the contract. Preserve forward state/journal on uncertainty and prove the actual Gateway/UI keeps the original envelope/draft unresolved until safe replay/reconciliation. Then complete S2 guarded mutation/undo, version-aware receipt–journal–effects verification and namespace/macOS durability evidence. No second verifier or transaction engine.
5. Complete C2 before S3/S4/S5 and the bounded compact-edit/UI/S9a work. Reuse existing owners and evidence. At C3 rerun C2's complete serialized uncertainty/replay cases after outcome/UI/recovery changes. Ordinary recoverable interruption should reconcile automatically or through one deliberate Diagnostics action; contradictory evidence stays blocked. Stale unresolved identity retirement requires proof of future execution prevention, with only the smallest durable fence if demonstrated necessary.

## Boundaries

**C1, S0, C2 and C3 are not accepted.** The demonstrated durability defect is reproduced but not fixed. This is a published WIP checkpoint, not a release or installation approval. No original/live learner data, vault installation or main-branch merge was authorized or performed. S9b remains deferred. Agent roles/delegation are Aram's decision. Preserve the existing 5% usage stop unless Aram changes it. Further implementation awaits a new instruction to resume.
