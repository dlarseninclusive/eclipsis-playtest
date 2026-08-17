# Eclipsis: The Shattered Expanse — store copy

*ST1 deliverable. Every claim below is drawn from `FEATURES.md` (shipped capability list),
`design/10_lore.md` (canon), `design/30_steam_page.md` (prior draft), and the seven frames in
`marketing/screenshots/`. Nothing here describes a feature that is not in the build.*

Full public title, spelled identically everywhere: **Eclipsis: The Shattered Expanse**.

---

## 1. One-line hook

> Survive a wasteland that keeps living whether you are in it or not.

Alternates, same positioning, if a shorter or longer slot is needed:

- *A dead civilisation left the machines running.* (short, atmospheric — good under capsule art)
- *Nineteen factions, one broken sun, and a world that does not wait for you.*

## 2. Short description

> Eclipsis: The Shattered Expanse is an open-world survival sim in the Kenshi lane. Nineteen
> factions hold their own cities, feed their own people and go to war without asking you. You
> start as nobody in particular, and the world keeps a record of what you did to it.

(287 characters — fits the ~300-character store limit as-is.)

## 3. About the game

**The sun goes out on a schedule**

Nothing exploded here. The old world was switched off. The civilisation everyone calls the
Architects did not fall — they stopped answering, and left their roads running true, their towers
humming on clear nights and their machines still executing the last instruction they were given.
Every fourteenth day at noon the sun goes black for a quarter of a day. The Cog Preachers call it
their holiest hour. Something in the Machine Nexus wakes up for it.

**A world that does not wait**

Enemy factions clash on sight whether or not you are on the map. Caravans haul real cargo to towns
that really need it, and towns eat, so a bad season on the breadbasket is a famine three regions
away and a price you can see move. Cities pay their guards out of a treasury, and a bankrupt one
loses them. Wars start over something, cost something, and end. Leave the game running and it will
still have news for you at dawn.

**What you actually do**

Scavenge, farm, cook, fish, mine and haggle. Recruit a squad, arm it, set its stance and take
direct control of any member. Climb seven ages of technology — stone to autonomous — with the bench
you built and the first thing you made at it. Run contraband past a gate frisk and fence it in a
back room. Take a bounty, or become one. Bury the companions you lose under a cut headstone with
your name on it, or dig up somebody else's dead and find out that grave goods are the one thing no
lawful counter in the Expanse will touch.

**Losing is a place the game continues from**

A fight has stances, blocks, dodges and charged heavies, and it can go badly in ways that are not a
reload. Limbs are lost and replaced with prosthetics. Go down in the wrong territory and you wake
in a cell, in a work gang, in a slaver's camp, or being carried off by the Hollowed to whoever they
answer to — and getting out is the next thing you do.

**Every system is wired to every other one**

There is no separate quest layer sitting on top of a diorama. A cull contract on the bar's work
board exists because a den three days away has been growing while nobody burned it. A rumour in
that bar was minted from something that actually happened to somebody. The Codex fills in as you
live, the History tab writes the world's own chronicle day by day, and a marker stands on the
ground where the thing it names took place.

**Drawn by code**

Every pixel in the game is drawn at runtime by the code that runs it — no sprite sheets, no
tilesets. That is why a town can be a hexagon of brick one seed and an octagon the next, why an
L-shaped building is solid where the wing is and walkable in the notch, and why the whole world can
be re-dressed by a mod. The grade is deliberately faded: the only vivid things in the Expanse are
blood, fire, an alert, the arcane, and the corona.

**Built to be rebuilt**

Factions, creatures, recipes, quests, items, reactions and most of the rules are plain data files,
and the base game is loaded through the same path a mod is. A mod folder merges over them, an
executable verifier checks it is honest, and a complete total conversion ships as a worked example.
If you want to make a different game with this one, that is the design rather than an accident.

## 4. Feature bullets

- Nineteen factions with their own cities, territories, economies, named leaders, succession, wars and long memories.
- One continuous 75,000-unit map: six biomes, sixteen named lands, and walled towns you get into through the gate like everyone else.
- A living economy you can plug into — caravans that haul real cargo, treasuries that pay guards, glut prices that crash when you dump a harvest, and famine when a season goes wrong.
- Homesteading that feeds it: farm, cook, ranch, fish, hunt and mine, and smoke the catch before it spoils.
- Squad play — recruit, equip, command and take direct control of any companion; they carry moods, remember what you did, and want paying.
- Combat with styles, stances, blocks, dodges and charged heavies, plus bleeding, burns, broken bones, lost limbs and prosthetics.
- Crime as a system: contraband, gate frisks, witnesses, bounty hunters, four kinds of custody, and fences who buy what no shop will.
- Seven ages of technology across eleven disciplines, climbed by hand — or studied out of books and charts you buy off an archive shelf or take off a body.
- A nineteen-species ecology with predators, scavengers, dens that escalate into broodmother nests, seasonal migrations and three apex beasts waiting at fixed lairs.
- A graveyard outside every town: bury your dead under their own headstone, or leave them out there and watch the squad think about it.
- The Great Eclipse every fourteenth day — a quarter-day of totality that lets out the things which sleep the rest of the month.
- Optional local-LLM NPC dialogue with per-character memory, running entirely on your machine. No account, no internet, and written lines when it is off.

## 5. Screenshot captions

Source files live in `marketing/screenshots/`; the page serves them renamed to `screenshots/NN.png`.

| page file | source | caption |
|---|---|---|
| `01.png` | `01_town_day.png` | Rust Haven at midday — a Rust Walker town inside its hexagonal curtain wall, two dozen townsfolk on the streets, and a door you can walk through. |
| `02.png` | `02_town_night.png` | The same street at 23:20. Lit windows, lamps down the main road, and a crowd you can only half see — night is genuinely dark, and what you can see depends on what you are carrying. |
| `03.png` | `03_dust_storm.png` | A dust storm over the highway through Corona's Grave. Wind-aligned streaks, the tint on everything, travellers strung out along the road, and an Architect ruin just found and marked. |
| `04.png` | `04_interior.png` | Inside The Crooked Compass — the keeper behind the Rusty Cog's counter, patrons at the tables, kegs and stools, and a floor selector for the rooftop and the basement. |
| `05.png` | `05_combat.png` | A street brawl mid-swing: damage numbers in the air, blood and dropped packs on the ground, two Dust Reavers still standing, and a log line reading "You kill a Dust Reaver. Their people won't forget." |
| `06.png` | `06_world_map.png` | The whole Expanse laid flat — biome ground, faction territories in their own colours, named capitals, the sixteen named lands, and a compass rose. |
| `07.png` | `07_codex_history.png` | Six days of world, written down: a famine in the Cinder Dominion, a war between the Blacklight Syndicate and the Automatons, treasuries, world mood — and "A shadow crossed the sun for the length of a breath, and the birds have not come back down." |

## 6. Pre-alpha disclaimer block

> **This is a pre-alpha playtest.** That is a real description rather than a modest one. Expect
> bugs, including ones that lose you a session. There is no audio at all — no music, no effects,
> nothing. The art is drawn by code and is still being worked on; several systems look plainer than
> they will. Saves are not guaranteed to survive the next build. Balance is provisional everywhere,
> and some corners of the map are thinner than others.
>
> A run-based mode — pick a seed, play until the waste takes you, and the next wanderer inherits
> what the last one learned — is in design and is *not* in this build. Nothing on this page
> describes it as present.
>
> This page is unlisted: it is not indexed, not announced, and not linked from anywhere public.
> Please do not repost the link or the build.
>
> If you play it, tell me what happened — what confused you, what you tried that the game did not
> expect, and what made you stop. That is the whole reason this build exists.

---

## 7. Positioning decisions, and why

**Led with "a world that keeps living whether you are in it or not."** This is ST1's job done: the
player-facing form of the dev framing ("a sim engine, a game you can make games with"). ST1 points
at Track R's line — *every run leaves the world changed* — for that translation, but Track R is in
design and nothing of it is in the build, so selling on it would be selling a mode that does not
exist. The shipped half of the same truth is the autonomous world: nineteen factions with their own
wars, caravans, treasuries, famines and chronicle. That is demonstrable in the build today and it
is the same promise a player would hear in the rogue-lite pitch.

**The engine claim is never made in engine language.** "A sim engine" is a developer's compliment
to himself and reads as a warning to a player (unfinished, technical, no game in it). It appears
instead as two player-facing consequences: *Every system is wired to every other one* (what a sim
buys you at the table) and *Built to be rebuilt* (the modding contract, stated as something you can
do rather than as an architecture). The words "engine", "framework" and "systemic" do not appear.

**The LLM is framed as optional, twice, before anyone can be surprised by it.** Once in the feature
bullets and once in the requirements table, in both cases with the offline fallback in the same
sentence and with "no account, no internet" attached. `design/30` is right that a buyer must not
discover this after the fact; the current build also degrades gracefully by construction (the
dialogue probe treats an absent Ollama as a warning, not an error, and re-probes). It is not
foregrounded in the hook or the short description, because "AI NPCs" is a claim that currently
attracts more suspicion than interest and the sim is the stronger lead.

**The rogue-lite is teased in exactly one place, inside the disclaimer, negated.** Named as in
design and explicitly not present. That gets the interest without a promise.

**Kenshi is named; Dwarf Fortress and RimWorld are not.** One comparison anchors a genre; three
comparisons read as a pitch deck. Kenshi is the closest and the one the codebase actually measures
itself against (`tests/parity.gd`'s 81-mechanic rubric). The DF/RimWorld influences show up as
mechanics in the copy (the chronicle, mood and thoughts) rather than as name-drops.

**"Nineteen factions", not eighteen.** `data/factions.json` has 19 ids and `FEATURES.md` says
nineteen; older docs and some memory say 18 (and one legacy playtest check name says 15). The
data won.

**"Every run leaves the world changed" is absent.** So is any word on Early Access, pricing,
release date, wishlists or a trailer — this is a playtest download page, not the storefront, and
those are Dave-only decisions per `design/30` §0.

**Register.** No "epic", "immersive", "stunning", "unique" or "deep". Every claim is a mechanic
with a noun in it. Where the game is weak (no audio, provisional balance, unstable saves) the page
says so in its own voice rather than in small print — a playtest page that oversells gets you
politeness instead of bug reports.

## 8. Things in FEATURES.md deliberately left off the page

- **Test counts, proof lines, golden frames, the parity rubric** (441/480 checks, 76.5/81) — real
  and impressive to a developer, meaningless to a player, and they make a store page read like a CI
  dashboard.
- **Slab and track codenames** (TT3, AR1, D4, N5, EG2, gy2a…) and the data-knob JSON keys. Same
  reason.
- **Utility networks, item quality and wear, the debt/loan/collector system, diplomacy at the
  leader's table, assassination contracts, the sting, courier runs, the Quiet Mile's landless
  structure, world states, hero relics, succession detail, salt-flat claims, build mode, siege
  emplacements, roof turrets, fast travel, the compass, hazard zones, three time speeds, keybinding,
  save slots.** All shipped; all cut for length. A twelve-bullet list that a stranger reads beats a
  forty-bullet list that they skim. Most are one clause away from being restorable if the page ever
  grows a "systems" section.
- **The eclipse boon draft, glyph sockets, weapon quirks** (the Noita-derived power layer) — real
  and shipped, but they are the substrate Track R will be built on, and describing them next to a
  rogue-lite tease invites a reader to assume the mode is in.
- **Slavery, work gangs and cages** are named as hazards you escape, once, in context. Kept because
  they are a genuine and distinctive part of the loop and one of the six starts; not dwelt on,
  and not made a selling point. (The full honest content survey belongs on the storefront's content
  form, not on a download page.)
- **The Hollowed / Eclipse Choir horror content** gets one clause. It is a reveal, and reveals
  should not be spent on a page a player reads before they play.
- **`design/30`'s "PEOPLE WHO REMEMBER" LLM section as a headline block** — demoted to a bullet, per
  the positioning note above.

## 9. Notes for whoever publishes this

- The two download buttons carry the literal placeholders `%%WIN_ZIP_URL%%` and `%%LINUX_ZIP_URL%%`;
  the version line carries `%%BUILD_VERSION%%`. Substitute all three before publishing.
- The page expects `screenshots/01.png` … `screenshots/07.png` beside `index.html`. Those files are
  already in this directory, copied and renamed from `marketing/screenshots/`.
- **The Linux build does not exist yet.** `godot_spike/export_presets.cfg` has exactly one preset,
  "Windows Desktop", and `BUILDING.md` documents a Windows-only export. The Linux button and the
  Linux instructions are written and ready, but a Linux export preset has to ship before that URL
  can point at anything. If it will not make this playtest, delete the Linux button, the Linux
  column in the instructions and the Linux clauses in the requirements list.
- Filenames in the instructions are assumed (`eclipsis.exe` from `BUILDING.md`; `eclipsis.x86_64`
  by Godot convention). Check the Linux one against the actual export before publishing.
- The log path is stated as the Godot user-data folder rather than "next to the executable",
  because that is where this build actually writes it (`project.godot` sets
  `debug/file_logging/enable_file_logging.pc`, and `BUILDING.md` gives the path). If the release
  build is changed to log beside the exe, simplify that paragraph.
