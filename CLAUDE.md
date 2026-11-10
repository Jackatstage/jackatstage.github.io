# Instructions for Claude

## Pull requests

- Never merge a pull request. Open it, then stop and let Jack review and merge it himself.
- This applies even if a pull request was merged in an earlier session or Jack asked for "PR then merge" before.

## Commits

- Commit author and committer must be Jack: `Jack Jiang <Jackatstage@gmail.com>`. Never commit as Claude, so Claude is never listed as a contributor.
- A `Co-authored-by: Claude` line in the commit message is fine.

## Answers

- Verify facts against official documentation or real data before answering. Quote or cite the source.
- State conclusions plainly. Never present a guess ("probably", "most likely") as an explanation; if something can't be verified, say exactly what is unknown and how to find out.

## This site

- Plain static site: `index.html` plus `images/`, published by GitHub Pages from `main`.
- All site and repo text is in English.
- This is Jack's portfolio for his application to The Academy (HAA). AI may only advise or edit: never write new content in Jack's voice. Use only his own words, and limit changes to grammar and clarity.
- Run `npm run validate` before committing.
