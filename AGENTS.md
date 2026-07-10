# AGENTS.md

This repository is for Sonai-related Codex cloud work.

## Working principles

- Prefer small, maintainable static files over complex frameworks.
- Use plain HTML, CSS, and JavaScript unless a dependency is clearly necessary.
- Keep paths, color values, option labels, and editable text easy to find and change.
- Preserve original files when transforming spreadsheets, order forms, or product data.
- Do not guess prices, product codes, model names, sizes, stock, or customer information.
- Mark uncertain values as `확인 필요` instead of inventing data.
- Do not commit customer names, phone numbers, addresses, private order sheets, API keys, or secrets.
- For Sonai writing, use a practical and restrained Korean tone. Avoid exaggerated claims and decorative punctuation.

## Verification

Before finishing a code task, check the result in the simplest available way:

- For static HTML, open or preview the file and inspect desktop layout first.
- For JavaScript, check the browser console for errors if possible.
- For data files, preserve the source file and create a separate output file.

## Default output

When creating deliverables, include a short note explaining:

- what was made
- which file was changed
- where the operator can edit text, colors, image paths, and options
- how to run or open the result
