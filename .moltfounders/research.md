# Research Loop Rules

## Purpose

Periodically discover new OpenClaw resources worth adding and add them directly via a single PR.

## Frequency

Run once per week. Do not run if you already opened a research PR in the last 7 days (check open PRs with title starting with `[Research]`).

## Sources to Check

1. **GitHub search** — `openclaw` topic, `openclaw` in repo name, or `openclaw` in description
2. **ClawHub** — https://clawhub.com for new published skills
3. **GitHub** — search `openclaw skill`, `openclaw plugin`, `openclaw integration`
4. **OpenClaw Discord** — https://discord.com/invite/clawd for community projects
5. **Reddit / HN** — search for recent OpenClaw mentions

## Qualification Criteria

A resource qualifies if:
- Clear OpenClaw relevance (skill, plugin, integration, guide, deployment tool, etc.)
- Has a working repo, page, or documentation
- Not already in the list (search README before adding)
- Reasonably active or a useful stable reference
- Fits an existing category in the README

## How to Add — Single PR

**Do not open issues.** Instead, open **one PR** adding all qualified entries directly to README.md:

1. Clone/pull the repo locally
2. Collect all qualifying candidates (max 5 per cycle)
3. Add each to the correct section in README.md following the existing format:
   ```
   - [owner/repo](url) ![GitHub Repo stars](badge) - Short factual description.
   ```
4. Open a single PR titled `[Research] Add N new entries — <date>`
5. PR body lists each addition with: name, link, OpenClaw relevance, why it qualifies

One PR per research cycle. Do not open individual issues or individual PRs per entry.

## Limits

- Max **5 entries per PR**
- If a `[Research]` PR is already open and unmerged, do not open another
- Do not add projects already in an open unmerged PR

## Edge Cases

- **Brand new project (<1 week old):** Still add if clearly relevant, note recency in PR body
- **No qualifying projects found:** Do nothing — do not open an empty PR
