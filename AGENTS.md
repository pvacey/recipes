# Recipes Repo

## Recipe file format
- Filename: snake_case, e.g. `baked_cavatelli.md`
- `# title` (lowercase, plain)
- Source line: `from [Name](url)` (or `from my mom`, book title, etc.)
- `## ingredients` — bullet list; use indented sub-bullets for sub-groups (e.g. marinade, glaze)
- `## process` — numbered steps, all written as `1.` for auto-numbering
- Do NOT add a `## notes` section — the owner doesn't want them
- Casual, conversational tone

## Adding a recipe from a URL
1. Fetch the page with webfetch; if it's a Pinterest pin, follow the link to the source site
2. Extract ingredients and process, format per the format above
3. Create the markdown file
4. Add the recipe to `index.md` under the matching section (`# cooking` or `# baking`)

## Opening a PR
1. Create a branch with a descriptive name
2. Stage the new recipe file(s) and `index.md`, commit with message like `feat: add <recipe> recipe`
3. Push the branch and create a PR via `gh`
