# PARA Automation Prompts

This folder keeps reusable Markdown prompts for recurring ChatGPT/Codex routines.

## How To Use

Keep the actual automation prompt in the reservation/scheduled task UI short, and point it to the relevant Markdown file.

Use this for the daily briefing:

```text
Run today's briefing using the instructions in `daily-briefing.md`.
```

If the scheduler cannot read local files directly, paste the contents of `daily-briefing.md` into the scheduled prompt and keep this folder as the editable source of truth.

## Files

- `daily-briefing.md`: Main 6:00 AM daily intelligence briefing prompt.
- `monthly-map-update-watch.md`: Monthly map update scan used only during the first briefing of the first week.
- `weekly-para-review.md`: Weekly PARA review prompt for projects, areas, resources, and archives.
- `automation-prompt-snippets.md`: Short copy-paste snippets for the scheduled task UI.

## Maintenance Rhythm

- Update `daily-briefing.md` whenever briefing quality, sections, or source focus changes.
- Update `monthly-map-update-watch.md` when the map regions or change categories shift.
- Update `weekly-para-review.md` after the PARA system becomes more concrete.
- Keep old versions by copying a file into an `archive/` folder with a date suffix.
