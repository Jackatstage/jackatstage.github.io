# TODO: fields still to write

Every item below is an element in `index.html` with a `data-todo="id"` attribute.
It stays in the HTML but is hidden by CSS, so nothing unfinished shows on the site.

**To fill one in:** search `index.html` for `data-todo="id"`, replace the `[WRITE …]` /
`[CONFIRM …]` / `[ADD …]` text (and any `[ADD …]` URL in `href` or `data-src`), then
delete the `data-todo="id"` attribute. It appears on the page with no other change.
A field heading ("Why I started it", etc.) shows as soon as any text under it shows.

This file is listed under `exclude` in `_config.yml`, so it is not published.

## A · Rigo Smart Booking System (`#rigo`)

| id | Where | Question |
|---|---|---|
| `rigo-why` | Why I started it | [WRITE: what made you want in — the problem you saw for small shops] |
| `rigo-bug` | What I did, below the list | [WRITE: one bug your L3 tests caught and how you fixed it] |
| `rigo-challenge` | Challenge | [WRITE: the hardest problem you hit on Rigo] |
| `rigo-learned` | What I learned | [WRITE: what you learned building and testing Rigo] |
| `rigo-github` | Links | [ADD: Rigo GitHub repo URL, if public] (in `href`) |

## B · Glazunov Saxophone Concerto / performance (`#performance`)

| id | Where | Question |
|---|---|---|
| `glazunov-why` | Why I started it | [WRITE: why you chose the Glazunov concerto] |
| `glazunov-challenge` | Challenge | [WRITE: the hardest passage or problem in preparing it] |
| `glazunov-learned` | What I learned | [WRITE: what you learned preparing and performing it] |
| `glazunov-now` | Where it is now | [WRITE: where your playing is now] |
| `ferling-video` | Media, third video | [ADD: Ferling Etude No. 9 YouTube URL] (in `data-src`) |

Photos that appear on their own once the file is in `images/` (no data-todo):
`images/kovalev.jpg` (under Training) and `images/iu-program-2025.png` (Media).

## C · Saxophone quartets (`#quartets`)

| id | Where | Question |
|---|---|---|
| `quartet-why` | Why I started it | [WRITE: why you founded the Paly quartet] |
| `quartet-challenge` | Challenge | [WRITE: the hardest part of running the quartet] |
| `quartet-learned` | What I learned | [WRITE: what you learned founding and playing in quartets] |
| `quartet-performances` | Where it is now | [WRITE: performances given; who runs the Paly quartet now] |
| `quartet-video` | Media | [ADD: Palo Alto High School Saxophone Quartet YouTube URL] (in `data-src`) |
| `kairos-video` | Media | [ADD: Kairos Quartet YouTube URL] (in `data-src`) |

## D · Boundarie.org (`#boundarie`)

| id | Where | Question |
|---|---|---|
| `boundarie-why` | Why I started it | [WRITE: why you took on media for Boundarie.org] |
| `boundarie-challenge` | Challenge | [WRITE: the hardest part of the media work] |
| `boundarie-learned` | What I learned | [WRITE: what you learned from the engagement data] |
| `boundarie-instagram` | Links | [ADD: Instagram URL of the account you produce for] (in `href`) |

## E · Playing for the community (`#service`)

| id | Where | Question |
|---|---|---|
| `service-hours` | Note under the list | Several hundred hours of volunteer service in all [CONFIRM: exact total]. |

## F · Discord server (`#discord`)

The whole card stays hidden until at least one field below is filled.

| id | Where | Question |
|---|---|---|
| `discord-role` | Role line | [WRITE: your role · dates] |
| `discord-purpose` | Why I started it | [WRITE: what the server is for, and why you started it] |
| `discord-did` | What I did | [WRITE: what you did: set-up, moderation, bots, events] |
| `discord-challenge` | Challenge | [WRITE: the hardest part of running it] |
| `discord-learned` | What I learned | [WRITE: what you learned running it] |
| `discord-members` | Where it is now | [WRITE: number of members] |

## G · Teaching myself to build (`#code`)

| id | Where | Question |
|---|---|---|
| `code-repo-1` | Links | [ADD: GitHub repo URL 1] (in `href`) and [ADD: repo name 1] |
| `code-repo-2` | Links | [ADD: GitHub repo URL 2] (in `href`) and [ADD: repo name 2] |

## Next · What I want to build (`#next`)

The whole section (and its menu link) stays hidden until at least one item is filled.
The "Notes" heading shows once any note is filled.

| id | Where | Question |
|---|---|---|
| `next-build` | Main text | [WRITE: 2–3 sentences, the same idea as your video] |
| `note-1` | Notes, i | [WRITE: what practicing saxophone has in common with testing software] |
| `note-2` | Notes, ii | [WRITE: what a merchant taught you about building AI] |
| `note-3` | Notes, iii | [WRITE: optional] |

## Contact (`#contact`)

| id | Where | Question |
|---|---|---|
| `contact-github` | Contact grid | [ADD: GitHub profile URL] (in `href`) and [ADD: GitHub username] |

## Other switches and files

- `index.html` is plain HTML: it looks the same on GitHub Pages and on a local static
  server such as `python3 -m http.server`.
- Optional photos appear on their own once the file exists (nothing to edit):
  `images/profile.jpg` (hero, top right), `images/kovalev.jpg` (Training), `images/tiktok.png` (Boundarie.org),
  and `images/iu-program-2025.png` (performance media).
- Timeline row "2021 · Extreme Military Challenge" (`id="military-challenge"`): to hide it,
  add the word `hidden` to that `<li>`; delete `hidden` to show it again.
