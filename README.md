# IESE PE/VC Club — Plugins

Plugin marketplace for the IESE Business School PE/VC Club.

| Plugin | What it does |
|---|---|
| **PE/VC Club Toolkit** | *Investment Thesis Coach* — a Socratic guide that walks you through the 14 blocks of an investment thesis, requires an external source for every claim, and applies the reasoning lenses of ten leading VC firms. |

---

## Install (club members)

Requires a paid Claude plan (Pro, Max, Team or Enterprise).

1. In Claude, open the **Cowork** tab.
2. Sidebar → **Customize** → **Plugins** tab.
3. Under *Personal plugins*, click **"+"** → **Add marketplace**.
4. Paste this repository's URL:

   ```
   https://github.com/YOUR-USERNAME/iese-pevc-club
   ```

5. The `iese-pevc-club` marketplace appears in the list. Click **Install** on *PE/VC Club Toolkit*.

That's it. From then on, just tell Claude "I want to build an investment thesis on X" and the skill triggers on its own.

---

## Releasing an update (maintainers)

The part that catches people out: **Claude decides whether you have a new version by reading the `version` field, not your commits.** Push changes without bumping the version and everyone keeps the cached copy.

The full release cycle:

1. Edit the content — usually `plugins/pevc-club-toolkit/skills/investment-thesis-coach/SKILL.md`.
2. **Bump the version** in `plugins/pevc-club-toolkit/.claude-plugin/plugin.json`:

   ```json
   "version": "0.2.0"
   ```

   Rule of thumb (semver): wording fix or small tweak → `0.1.1`. New block or changed behaviour → `0.2.0`. A rewrite that breaks how people used it → `1.0.0`.
3. Record what changed in `CHANGELOG.md`.
4. `git commit` and `git push`.
5. Tell the group. Each member updates from **Customize → Plugins**: sync the marketplace, then accept the plugin update.

> Keep the version in **`plugin.json` only**. Do not repeat a `version` field in the `marketplace.json` entry — with both set, Claude uses `plugin.json` and the other one just breeds confusion.

### Adding another skill to the toolkit

Create `plugins/pevc-club-toolkit/skills/<skill-name>/` with a `SKILL.md` inside, bump the version, push. Natural candidates: deal-flow screening, market-map building, VC interview prep, cap table reading.

### Adding a second plugin

Create `plugins/<new-plugin>/` with the same structure and add an entry to `.claude-plugin/marketplace.json`. Anyone who already has the marketplace installed will see the new plugin appear.

---

## Repository layout

```
.claude-plugin/
  marketplace.json              # catalogue — lists the plugins in this repo
plugins/
  pevc-club-toolkit/
    .claude-plugin/
      plugin.json               # manifest and the plugin VERSION
    skills/
      investment-thesis-coach/
        SKILL.md                # the agent itself
    README.md
CHANGELOG.md
```
