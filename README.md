# acs-skills

Skills for **Audio Cascading Style Sheets** (ACS). Auto-generated
mirror of [`Grkmyldz148/acs`](https://github.com/Grkmyldz148/acs)'s
`skills/` folder.

## Bundled skills

- `acs-soundscape` — see [`skills/acs-soundscape/SKILL.md`](skills/acs-soundscape/SKILL.md)
- `create-acs-sound` — see [`skills/create-acs-sound/SKILL.md`](skills/create-acs-sound/SKILL.md)


## Install — Claude Code (native plugin)

```
/plugin marketplace add Grkmyldz148/acs-skills
/plugin install acs-skills@acs-skills
```

Lands in `~/.claude/plugins/`. Both skills become invokable as
`/create-acs-sound` and `/acs-soundscape` immediately. Future
skills added to the source repo arrive via
`/plugin update acs-skills`.

## Install — any agent runtime (`npx skills`)

```bash
npx skills add Grkmyldz148/acs-skills
```

Uses the [`skills`](https://www.npmjs.com/package/skills) CLI
(vercel-labs). Picks the runtime interactively (Claude Code, Cursor,
Codex, OpenCode, 50+ supported), shows a multi-select picker so you
can install both skills in one go or just the one you need.

## Updating

**Do not commit here.** Changes pushed directly to this repo are
overwritten on the next mirror sync. Open PRs against the source repo
(`Grkmyldz148/acs`) under `skills/<skill-name>/`; merging to
`main` triggers a re-mirror within seconds.

---

Last sync: `4e93788`
