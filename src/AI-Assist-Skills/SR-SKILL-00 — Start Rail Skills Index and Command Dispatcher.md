SR-SKILL-00 — Start Rail Skills Index and Command Dispatcher

PURPOSE
Master index for Start Rail-adjacent reusable workflows. These are persistent skill specifications stored in Google Drive; they are not native-installed ChatGPT slash commands. Use the command aliases below as conversational dispatch shortcuts.

COMMAND ALIASES
/StartRailSkills — List all Start Rail skill specs and what each one does.
/SRSkills — Alias for /StartRailSkills.
/SRContinuity — Run the continuity curator over supplied/recent play logs.
/SRCanonDiff — Compare new evidence against existing continuity and classify confidence.
/SRMechanics — Audit abilities, resources, powers, theory, and mechanical limits.
/SRRelations — Audit relationship changes, agreements, protocols, and open threads.
/SRSeed — Produce a continuity seed for a new RP session.
/SRValidate — Validate a proposed RP post against continuity and posting rules.
/SRLog — Persist the current audit/results into Google Drive and verify the write.

SKILL CATALOG
SR-SKILL-01 — Continuity Curator
Turns raw play logs into chronology, major/minor events, state changes, unresolved seams, and Drive-ready continuity records.

SR-SKILL-02 — Canon Diff and Evidence Classifier
Compares new material against established state and labels claims as confirmed, interpretation, character belief, hypothesis, UI/system claim, OOC correction, or non-canon.

SR-SKILL-03 — Ability, Resource, and Mechanics Reconciler
Tracks powers, learned theory, first-use demonstrations, repeatability, Mana/CE, structural load, processing load, channel/core condition, and continuity-safe resource reconciliation.

SR-SKILL-04 — Relationship, Agreement, Doctrine, and Thread Extractor
Tracks relationship deltas, agreements, consent boundaries, faction accords, doctrine/maxims, and unresolved investigations.

SR-SKILL-05 — RP Seed and Post Validator
Creates compact continuity seeds and checks proposed Timothy posts for canon, character knowledge, 2,000-character limit, Timothy-only rules, and accidental power promotion.

SR-SKILL-06 — Drive Persistence Logger
Defines naming, persistence, verification, and update rules for SR-LOG, SR-REL, SR-ABILITY, SR-THREAD, and skill documents. A task is not complete when persistence is requested until the Drive write is verified.

DISPATCH RULE
When a user invokes a command alias, locate this index and the named skill spec(s), then apply them together as needed. /SRContinuity should normally call 01 + 02 + 03 + 04 + 06. /SRSeed should use 02 + 05 and current Drive continuity. /SRLog should use 06 after any audit.

GLOBAL INVARIANTS
- Assistant draft is not canon until posted and the game responds.
- Player/OOC correction outranks generated narration and UI.
- Never promote hypothesis to fact.
- Never promote theory/discussion to acquired ability.
- Do not silently change resource maxima because a UI denominator changes.
- Preserve collaboration credit and consent boundaries.
- Timothy remains 1st Year until an actual advancement occurs.
- If the user asks to log/persist/update Drive, chat-only output is incomplete.

REVISION — SANITY CHECK EXPANSION

ADDITIONAL COMMANDS
/SRRelations [relationships|agreements|doctrine|threads] — Filter SR-SKILL-04 output to one concern.
/SRThreads — Dedicated unresolved-thread audit using SR-SKILL-04 + SR-SKILL-02.
/SRStatus — Compact latest confirmed playable-state snapshot using SR-SKILL-08.
/SROOCHistory [command-or-skill] — Explain why an OOC workflow exists and how it evolved using SR-SKILL-07.

ADDITIONAL SKILLS
SR-SKILL-07 — OOC Workflow and Command Historian
Tracks command purpose, origin problem, original/current behavior, version history, reasons for change, dependencies, aliases, lifecycle, and deprecation. Keeps OOC workflow skills distinct from Timothy's IC abilities.

SR-SKILL-08 — Current State Snapshot
Produces the latest confirmed playable edge: time/location, condition, resources, active packages, people present, relevant relationships/agreements, immediate objectives, inventory/artifacts, threats, and unknowns.

NAMESPACE DISTINCTION
- SR-SKILL-## = OOC workflow/tooling skills.
- SR-ABILITY / SR-WEB and similar records = Timothy/in-character capabilities.
- The older Living Web skill registry remains retained IC capability history. User reports those skills have not had practical use since Golden Foundation; treat as dormant/not-recently-exercised, NOT removed or invalidated unless play establishes that.

CROSS-SKILL SANITY RULES
- Canon Diff must distinguish PLAYER/OOC INTENT from OOC CORRECTION; intent/plans are not canon.
- Mechanics must preserve capability provenance: Timothy-created, learned, collaborative, borrowed/external, or autonomous Web behavior.
- RP validation must report character count, detect accidental NPC control, and check new powers/knowledge against ability continuity.
- Seeds/status must identify the last confirmed playable edge.
- Persistence records should retain source-log provenance for newly created continuity records.
- Every skill output is one of descriptive analysis, canon/state update, or persistent write; do not blur these modes.

LEARNING & MANIFESTATION EXTRACTOR
/SRExtract — Run SR-SKILL-09 over supplied Start Rail text logs. Extract reviewable learning and demonstrated manifestations, preserve source provenance and confidence, merge repeated manifestations, and persist results into the dedicated StartRail learning/abilities folders when Drive persistence is requested.
SR-SKILL-09 — Learning & Manifestation Extractor
Separates classes, textbooks, articles, papers, theories, demonstrated abilities, artifact-assisted effects, passive effects, and unresolved hypotheses. Never invents source contents or promotes theory into acquired capability.

END INDEX

