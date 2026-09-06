# Automation Prompt Snippets

Short snippets for the scheduled task UI.

## Daily Briefing

Use this if the automation can read local Markdown files:

```text
Run today's 6:00 AM daily briefing using the instructions in `daily-briefing.md`.
```

Use this if the automation needs a self-contained prompt:

```text
Create today's Korean daily intelligence briefing for me. Focus on GIS, map production, NDS.live/NDAS, OEM map update strategy, SDV, automotive navigation, ADAS, AI/security, semiconductors, Korean/economic context, and useful travel/history items when relevant. Search current sources before writing, use the exact date, avoid repeating yesterday's main topics, and include exactly 5 high-signal items. After the items, add Today's Insight, PARA Candidates, and 1-3 Today Actions. Run Map Update Watch only during the first briefing of each month’s first week; otherwise say it is skipped. If tools are available, create a shareable HTML version, save it to Google Drive folder `Daily Briefing`, and email it to `cwy1226@gmail.com` if Gmail sending is available. If email sending fails, still complete the briefing and Drive save, and clearly report the failure.
```

## Monthly Map Update Watch

```text
Run the monthly Map Update Watch using `monthly-map-update-watch.md`, then summarize only meaningful map-relevant changes with source confidence and suggested handling.
```

## Weekly PARA Review

```text
Run a weekly PARA review using `weekly-para-review.md`. Keep it light, practical, and focused on next actions, active areas, useful resources, and archive candidates.
```

## Suggested Schedule

- Daily Briefing: every day at 6:00 AM.
- Weekly PARA Review: Sunday evening or Monday morning.
- Monthly Map Update Watch: inside the first briefing of each month’s first week.
