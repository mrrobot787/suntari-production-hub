# Cursor agent handoff — Suntari Production Hub

Date: October 30, 2026 (America/New_York).
Purpose: locate and validate existing Suntari information while preserving the current Windows hierarchy.

## Start here

Repository: https://github.com/mrrobot787/suntari-production-hub
Branch: main
Read in this order:
1. AGENTS.md
2. README.md
3. bindings/source-map.json
4. catalog/file-index.json
5. evidence/current-status.md
6. evidence/index-check.json

The initial index commit is a4196217bdb41bb69353cd6fac0e43d7348192f5. It indexes 265 files from three existing project roots. Check current main before working; the count is a dated observation.

This repository currently contains metadata and navigation, not copies of the indexed source documents or artwork. Source-content upload was blocked pending explicit approval; creating this handoff does not approve that upload. No local clone, automatic sync, or source migration was performed.

## Routing map — HSMPLC-Workstation

| Index root | Existing absolute Windows root | Route requests here |
| --- | --- | --- |
| orchestrator | C:\Users\hakee\suntari-universe-orchestrator-plugin | Existing plugin instructions, character locks, source registry, installed approved Solaris image |
| execution | C:\Users\hakee\Downloads\SUNTARI_S01_I01_Execution | Existing page-specific QA, masks, layered-source handoffs and local execution evidence |
| production | C:\Users\hakee\OneDrive\Suntari Shared Production Library - Private\SUNTARI-S01-I01 | Existing production references, panel candidates, page assemblies, QA, exports and evidence |

Resolve an indexed file by joining its root from this table with its relative_path from catalog/file-index.json. File size and timestamp establish inventory metadata only; retrieve and hash actual bytes before relying on a source.

Keep the repository checkout in a NEW separate directory. Never clone, extract or pull this hub over one of the three existing roots. Do not initialize another repository in those roots or copy a new hierarchy over them. A multi-root Cursor workspace may reference the existing absolute paths; reference them without moving the directories. Opening a workspace does not install a skill or prove that an agent has read it.

If running in a cloud Cursor agent, these Windows paths will usually be unavailable. Report that limitation and request the specific source artifact needed, or use an already authorized connector. Do not infer that a cloud checkout has the workstation files.

## Exact Solaris routes

Installed master:
C:\Users\hakee\suntari-universe-orchestrator-plugin\assets\approved\Solaris\SOLARIS-CHARACTER-REFERENCE-v1.0.png

Adjacent provenance:
C:\Users\hakee\suntari-universe-orchestrator-plugin\assets\approved\Solaris\asset-manifest.json

Approved-master SHA-256:
b5dda11cc6ab10d099bf14dc6846940e7afad9ca4a01a79ff3cafc01436fb132

Character ID: SUNTARI-CHAR-SOLARIS-001.
Reference: SOLARIS-CHARACTER-REFERENCE-v1.0.
Existing creator approval: APPROVED_LOCKED, October 18, 2026; visual character identity only.

Plugin instruction entry:
skills/suntari-universe-orchestrator/SKILL.md, relative to the orchestrator root.

Related reference files:
- skills/suntari-universe-orchestrator/references/canon-locks.md
- skills/suntari-universe-orchestrator/references/solaris-identity-lock.md
- skills/suntari-universe-orchestrator/references/visual-assets.md
- skills/suntari-universe-orchestrator/references/production-governance.md

Fresh source/destination hash verification and PNG decoding passed during installation. Four reference documents passed limited static content checks. The visual-assets.md local-path entry is still historical and says NOT VERIFIED; do not treat it as evidence that the installed master is absent. Reconcile through an authorized minimal-diff documentation update, with readback and lineage. Do not silently alter approval or source history.

The production file named SOLARIS-CHARACTER-REFERENCE-v1.0(1).png differs in file bytes but previously matched every decoded RGBA pixel of the approved master. Preserve it; use the exact hash-bound master above for this test.

## Connected records and authority

- Project map and recovery register: https://app.notion.com/p/3fd824335837814eaf19fb7402a74322
- Issue 1 home: https://app.notion.com/p/3ff8243358378167b5beef79971862cd
- Production continuation contract: https://app.notion.com/p/4038243358378171ba33c772b5549c91
- Character Visual Atlas: https://app.notion.com/p/3fe82433583781b48307cdcb65c2bdc5
- Existing cinematic repository: https://github.com/mrrobot787/suntari-cinematic-animation

The new hub is an index, not a replacement canon or a new page-selection manifest. Read current source decisions before any production edit. Source hashes, technical PASS and generated labels never substitute for creator acceptance, visual review or release approval.

## Reported reorganization — not verified

A previous Cursor response reported a repository layout with LanternGateOps/ and SUNTARI_S01_I01_Execution/, plus LanternGateOps-SUNTARI_S01_I01_Execution.code-workspace and Solaris_FiveView_Test/ checklists.

The originating repository URL/commit has not been recovered. Those files were not found in the Windows roots when checked. The supplied Cursor session URL was blocked by security verification in the inspecting browser:
https://cursor.com/agents/bc-01a18dcd-41a1-71ce-bc6e-fc0dcc165f69

If you are that originating agent, return the exact repository owner/name, branch, commit SHA and changed-file list. Do not claim the reported reorganization is mirrored locally. Do not rebuild it from this summary and call it the original.

## First bounded task — validate actual reference loading

Perform this task read-only if the workstation sources are accessible:
1. Resolve the installed master and provenance file.
2. Compute the master SHA-256 and compare it with the approved value above.
3. Read the actual orchestrator instruction and Solaris identity lock.
4. Open the actual PNG through your image-reading tool; do not rely on text alone.
5. Return the actual file paths read, computed hash, image dimensions, tools used and observable loading evidence.
6. Explain the distinction between character visual approval and new scene/issue approval. Report any unavailable file/tool precisely.

Do not edit source files, generate artwork, install software, change model settings, open a PR for unrelated changes, or claim automatic skill discovery through this task. Explicitly instructed loading and automatic plugin activation are different tests.

Earlier availability checks found Cursor editor version 3.27.12. Codex, cursor-agent and agent were not found on PATH; cursor agent --help returned general editor help. This does not prove agent functionality is absent elsewhere. No actual Cursor/Codex reference-loading test has passed.

## Five-view test — preserve authorized configuration

Creator-provided note records authorization for V1–V5, seeds 101–105, with no technical settings changed from ComfyUI workflow revision 2:
- V1: front view, seed 101
- V2: three-quarter view, seed 102
- V3: side profile, seed 103
- V4: rear view, seed 104
- V5: facial close-up, seed 105

Identity input: exact approved Solaris master.
Style input: S01_I01_P03_continuity_revision_v008.png; resolve through the index and verify source bytes.
The actual revision 2 workflow JSON, full frozen settings and referenced workflow-spec results table have not been recovered. This handoff does not reproduce the full frozen prompts or authorize reconstructing the graph.

Do not run until those exact artifacts are bound. Record checkpoint/model/adapter versions, node requirements, dimensions, sampler, scheduler, steps, guidance, denoise and reference weights from the actual workflow. Do not invent missing settings.
Before an authorized run, unload Ollama as specified by keep_alive=0s and define timing/peak-VRAM measurement. Keep recovery runs distinct. Return each output, hash, complete provenance, timing, memory measurements, failures and per-view continuity results.
Outputs remain candidates until exact creator acceptance. IEA-001 remains UNVERIFIED. Animation, paid rendering, automation expansion and issue publication are not authorized by this test.

## Return format

Return one compact record:
- Task ID and exact scope.
- Source locations, versions and hashes actually read.
- Actions actually executed.
- Output locations and evidence.
- PASS/FAIL/PENDING for each tested criterion.
- Source modifications, if any; the first task requires zero.
- Remaining blocker and next bounded action.
- Creator-review and release state.

Work on the first bounded task before expanding scope. Preserve originals, existing folder hierarchy and issue publication HOLD.
