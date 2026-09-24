SR-SKILL-07 — OOC Workflow and Command Historian

PURPOSE
Maintain the history of Start Rail OOC workflow skills and conversational slash-command conventions: why each exists, how it originally behaved, how it evolved, what problem drove each revision, dependencies, aliases, replacements, and lifecycle status.

COMMAND
/SROOCHistory [command-or-skill]
Without an argument, audit/list the OOC workflow history. With an argument, explain that command's origin and evolution.

RECORD FOR EACH OOC WORKFLOW
- Canonical command and aliases.
- Backing SR-SKILL document.
- Category.
- Lifecycle: Proposed / Active / Revised / Deprecated / Retired.
- Created date/session when known.
- Triggering problem or failure mode.
- Original behavior and scope.
- Current behavior and scope.
- Version/evolution history.
- Reason for each material change.
- Dependencies and handoffs.
- Supersedes/replaces.
- Examples of intended use.
- Known shortcomings/open improvements.

CHANGE TRIGGERS
Update this history whenever an OOC skill/command is created, renamed, materially revised, split, merged, deprecated, or retired. Cosmetic wording changes do not require a version event unless they alter behavior.

VERSION RULE
Do not overwrite the reason a rule exists. Preserve before → problem/evidence → change → resulting behavior. A current rule without its causal history is incomplete.

NAMESPACE RULE
Distinguish OOC workflow skills (SR-SKILL-##) from in-character Timothy/Living Web abilities (for example SR-WEB and SR-ABILITY records). “Start Rail skills” defaults to OOC workflow skills; “Timothy's skills/abilities” defaults to IC capability records unless context says otherwise.

CURRENT HISTORICAL NOTE
The older Living Web skill registry remains valid as an IC capability record, but the user reports those Living Web skills have not had practical use since the Golden Foundation emerged. Treat them as retained/dormant or not-recently-exercised capabilities, not deleted or invalidated. Do not infer that Golden Foundation removed them without played evidence.

PERSISTENCE
When a command/skill materially changes, update both this historian and SR-SKILL-00 dispatcher. If persistence is requested, verify the write through SR-SKILL-06.

END SKILL

