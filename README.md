# Creative handoff kit

A small, tool-independent set of briefs, acceptance checks and CSV logs for handing AI-generated creative assets to an editor or teammate. Start with a voiceover, then adapt the same fields for an image or video. No account, package installation, API key or proprietary project file is needed to use the templates.

## Download or copy

- [Voiceover handoff sheet](templates/voiceover-handoff.md): approved script, pronunciation, timing, source and final decision.
- [Asset acceptance checklist](templates/asset-acceptance-checklist.md): check the actual deliverable against its intended placement.
- [Generation log CSV](templates/generation-log.csv): track attempts, estimates and observed usage separately.
- [Revision log CSV](templates/revision-log.csv): connect a requested correction to the take that replaced it.
- [Worked handoff example](examples/hypothetical-product-demo.md) and [example generation log](examples/generation-log.csv): hypothetical production data, not a benchmark or customer case study.

Open a CSV file and choose **Raw** to download it, or use GitHub's **Code → Download ZIP** for the whole kit. The Markdown sheets can be copied into your editor or project notes. Keep each working copy with the assets it describes.

## Use the kit in one short review

1. Define the output before generating it: placement, audience, duration or dimensions, required details and hard limits.
2. Freeze the script or brief. Assign a revision such as `script-v03`; directions and spoken words belong in different fields.
3. Give each attempt a stable ID. Record the exact model label and relevant settings shown in your tool; leave unavailable fields blank.
4. Review the full output in its destination. Listen to audio, watch the complete clip, or inspect the image in the intended crop.
5. Record **pass**, **revise** or **not_checked** for each acceptance check. Add an actionable note for any failed requirement.
6. Hand off the approved filename and attempt ID together. Record which earlier file the new take supersedes.

A technical success message means a job returned an output. Approval is a separate production decision. The kit does not score tools, promise a particular result or determine whether you have the rights to an asset.

## CSV conventions

`generation-log.csv` has one row per attempt. Keep `estimated_usage` and `recorded_usage` distinct and put the unit in the adjacent field. Do not copy an estimate into the recorded field when final usage is unavailable. Keep both empty when no usage information was observed. Units may differ by tool; do not sum unlike units.

`revision-log.csv` has one row per requested correction. Use project-relative filenames and labels rather than private cloud links or customer contact details. The templates contain headers only; files in `examples/` contain clearly hypothetical sample rows.

CSV files use UTF-8, comma delimiters, a single header row and ordinary quoted fields. They contain no formulas or macros. Your spreadsheet may display empty fields differently; an empty field means **unknown or not recorded**, not zero.

## Scope and privacy

Use only recordings, voices and reference assets you are entitled to use. Do not imitate a real person without the necessary permission. Keep passwords, tokens, personal contact information and private customer details out of a public copy. A public template is a blank starting point; completed project logs usually belong in your private project storage.

## Maintainer

Prepared by [QuestStudio](https://queststudio.io/), a browser-based workspace for AI image, video, voice and music production. These templates work independently of the product. QuestStudio is a paid subscription; its 7-day, 100-credit trial requires a card, with monthly billing afterward unless canceled.
