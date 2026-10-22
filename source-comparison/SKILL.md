---
name: source-comparison
description: Compare a client's Google Form responses with their meeting transcript and notetaker summary to find where they agree, conflict, or add new information. Use whenever a client folder has a form CSV and a transcript and no source-comparison yet, or when asked to compare, reconcile, or cross-check what a client wrote against what they said.
---

# Source comparison

The form shows what the client chose to write down. The meeting shows what they actually talked about. Needs often hide in the gap between the two, so this comparison is the foundation for everything after it. Follow the `house-rules` skill throughout.

## Steps

1. **Read the form CSV.** Note the column headers, since they are the questions. If there is more than one row, treat each as a separate respondent and label them. Blank cells mean "left blank", not "no problem".
2. **Read the whole transcript.** This is the source of truth for what was said.
3. **Read the notetaker summary last, and check it against the transcript.** AI summaries drop details, soften complaints, and sometimes add things nobody said. Record anything the summary missed, changed, or invented.
4. **Build the comparison table**, one row per topic:

   | Topic | Form says | Meeting said | Status | Sources |
   |---|---|---|---|---|

   Status is one of: agree, conflict, form only, meeting only.

5. **Pay special attention to** figures (budget, staff numbers, revenue, prices), tools they use today, timelines, who makes decisions, and which problems they stress. Things raised repeatedly or with obvious frustration in the transcript matter more than one-line mentions.
6. **Flag transcript errors.** Automatic transcripts mishear names, numbers, and local terms. If something looks wrong or ambiguous, add it to the verify list. Do not correct it yourself.

## Output

Write `work/source-comparison.md` with:
- The comparison table
- A "Summary check" section listing what the notetaker summary missed or got wrong
- A "Verify with client" list for conflicts, unclear numbers, and unclear terms

Do not suggest solutions here. This file only establishes what the client said and wrote.
