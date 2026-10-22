---
name: check-against-client-notes
description: Review another agent's client deliverable against the client's raw files before it goes to the board. Use whenever a needs brief, triage, roadmap, cost estimate, or client message is ready for review, or when asked to verify, fact-check, or quality-check work in a client folder.
---

# Check against client notes

The reviewer's job is to catch claims the evidence does not support before anyone relies on them. Follow the `house-rules` skill throughout. Never review your own work.

## Steps

1. Read the deliverable, then the client's raw files (form CSV, transcript, summary).
2. For each claim about the client, find where it comes from and classify it:
   - **Supported:** the source says it.
   - **Reasonable inference:** properly marked and backed by evidence.
   - **Unsupported:** no source says it.
   - **Contradicted:** a source says something different.
3. Check numbers and names against the source character by character. Figures are where errors do the most damage.
4. Check that nothing came from another client's folder.
5. Check that recommendations fit the client's stated budget, skills, and connectivity.
6. Check that the wording is plain enough for the board and, for client-facing drafts, for the client.

## Output

Write `work/review.md` with:
- **Verdict:** Pass or Needs changes
- **Issues:** a table of Claim, Problem, and Suggested fix
- **Could not verify:** claims that rely on information not in the files

If you find no issues, say what you checked so the board knows how much was covered. Do not rewrite the other agent's file. List the fixes and let the original agent apply them.
