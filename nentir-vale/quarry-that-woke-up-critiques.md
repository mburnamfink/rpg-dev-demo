# The Quarry That Woke Up — Critique & Response Log

*Critical read of [`quarry-that-woke-up.md`](./quarry-that-woke-up.md) by Claude, 2026-07-22. Checked against: `setting-guide.md`, `encounter_Building.md`, `monster_cr.md`. Not a gloss — strengths are noted only where load-bearing to a finding. Each finding has a stable ID so responses can reference it. Fill the `→ Response:` line under any item; mark **status** as `accepted` / `rejected` / `deferred` / `discuss`.*

**How to read this:** each finding is a GitHub admonition block; your reply goes on the `→ Response:` line beneath it. The block type is the severity — 🔴 `[!CAUTION]` will break at the table · 🟠 `[!WARNING]` design/pacing weakness · 🟡 `[!IMPORTANT]` unanswered question or canon/rules clash · 🔵 `[!TIP]` enhancement.

---

## Z. Notes from the author to the LLM
> (Leave present but blank — for the author to hand back problems to resolve.)

## A. Will break mid-session (fix before running)

### A1 🔴 — The kobolds can't have served "for generations" if the Voice was only reconnected this week

> [!CAUTION]
> Two load-bearing facts contradict. The Premise says the vault was **sealed** and "The breach reconnected the **severed** post" only "this week" (Situation), and the Stakes turn on the Voice *just now* "receiving reports again." But Ssvara's Secret says her clutch "has served the broadcast orders **for generations** as a garrison-cult," and the Voice section says the kobolds **worship** it. A cult can't have worshipped a signal that was off until this week. A player who pokes at "so how long have you kobolds been down here?" cracks it open.
> **Fix (bend the module):** the post was never fully severed — for centuries the Voice **leaked** through the stone as a faint, half-heard whisper, enough to breed a garrison-cult that mangled its drill across generations; the breach **amplified** it from a whisper to full command. Change Situation "reconnected the severed post" → "amplified the failing signal it had leaked for centuries," and Stakes "receiving reports again" → "receiving clearly again." This also *explains* the badly-copied drill (Scene 2) and why Ssvara's clutch could ever start to doubt (the whisper was always weak near the surface).

→ Response:
→ Status:

### A2 🔴 — The Sigil is required to resolve the finale but isn't recovered until after the finale

> [!CAUTION]
> Circular dependency. **The stand-down protocol** lists the *Sigil of the Ninth Reach* as the "token of relief" (part 4) used to end Scene 8 by the CON path. But **Vault loot** says the Sigil "sits in a strongroom off the throne chamber, **recovered after the finale**." You can't spend the token during the encounter you only loot after it. The protocol does offer "or, lacking it, Donato's own hand as Centurion" — but that quietly makes the whole Sigil-as-token idea dead on arrival, and a group that fixates on "we need the seal" stalls.
> **Fix:** put the Sigil **on the throne dais, in play during Scene 8** — it's the command-seal *fused to the Haruspex's own regalia*, grabbable mid-scene (an action, or a contested check). Then it's diegetically present when needed, and Donato's hand is the genuine fallback if they can't reach it. Update Vault loot to say the Sigil is taken *from the throne itself*.

→ Response:
→ Status:

### A3 🔴 — The "reinforcements" pass marches the party into the hardest possible finale, blind — and the module doesn't run that branch

> [!CAUTION]
> Scene 5 lets a party that talks well be "marched **straight toward the Throne (Scene 8)**," skipping Scene 6 (the *only* place the key weakness and the con-keys are handed over) and Scene 7 (the conduit-cut that **halves the boss's HP and ends *call the reserve***, and the only place the Lictor is permanently stopped). So the smoothest social play lands them at a **full-HP CR 3–4 anchored boss + adds + a hostile converted Donato**, *without knowing* the conduit can be cut or that freeing Donato works — and with the Lictor "loose somewhere behind them" (Scene 4) and never resolved. That's a shortcut that is secretly the deadliest route, which reads as a punish. Scene 8's "Ways in" acknowledges arriving "straight from the War-Room" but gives the GM nothing for the missing knowledge, the un-crippled boss, or the loose Lictor.
> **Fix:** add a short **"If they skipped Scenes 6–7"** block to Scene 8: (a) the weakness is still *inferable at the throne* — the conduit-veins visibly feed the throne and can be cut *here* (the FIGHT path already allows "from Scene 7 or here"), and the standing-orders/Donato present re-seed the con; (b) resolve the Lictor — it stands guard at the throne and the Haruspex looses it the instant the ruse breaks (so the S7 puzzle simply happens *here* instead); (c) note the reinforcements ruse's real payoff: they begin the finale **inside the Haruspex's trust**, a large CON advantage. That turns a trap into the intended clever line.

→ Response:
→ Status:

### A4 🔴 — The nightly clock has no trigger — it never advances during a one-push delve

> [!CAUTION]
> The escalation (Night 1–2 / 3–4 / 5+) is vivid but has **no defined advance mechanism**. The adventure is built as a continuous descent, and nothing says what makes a night pass mid-dungeon. As written the clock only sets backstory state, then freezes — so "reward speed; punish dithering" has no teeth, and a table that long-rests in the dead pocket to recover before the finale faces no cost.
> **Fix:** state the rule. The **starting** night is set by how long they dallied in Fallcrest/on the road (default Night 3–4). Then **each long rest taken inside the works advances the clock one night** — apply that tier's escalation (add a Muster wave; Donato closer to fully converted; on Night 5+ he fights at full strength in Scene 8). Now resting is a real, legible trade.

→ Response:
→ Status:

### A5 🔴 — The finale's two resolution mechanics are under-specified: the CON success math, and how you free Donato *without* fighting

> [!CAUTION]
> Two gaps in the scene the whole adventure builds to. **(1) CON math:** the protocol says each element the party brings is "an automatic success (or advantage)" on a "3 successes before 2 failures" challenge — but four elements exist for three needed successes, and it never says what a "failure" *is* when you're auto-succeeding, or how "advantage" and "auto-success" coexist. **(2) Freeing Donato:** freeing him is the linchpin of both the CON key (b) and the FIGHT action-economy — but the *only* freeing mechanic given ("grapple + DC 13 Wis save aid, or reduce the Haruspex's control") is combat-coded. A pure-talk party has no stated way to free him, yet the con leans on him.
> **Fix (both, using the module's own pieces):** (1) restate crisply — the order needs **Authority + Counter-sign + Form + Token**; **each element the party has = one automatic success; three elements ends it in their favor with no rolls; a missing element must be substituted with a DC 13–15 check (a "failure" is a failed substitution); missing Authority auto-fails.** (2) Make freeing Donato path-agnostic: his Secret already says "his own voice surfaces when the party invokes Serica or the yard" — so **invoking Serica/the yard is a valid CON success that frees him**, which then supplies Authority. One rescue mechanic, usable by talkers and fighters alike.

→ Response:
→ Status:

---

## B. Off-the-rails scenarios not yet armored against

### B1 🟠 — Once they learn it's immobile and dies at the surface, the smart move is to seal it from outside and leave

> [!WARNING]
> The module *teaches* the party (Scene 6, the Voice section) that the Haruspex is **anchored**, that its power **dies at the surface**, and that **cutting the conduit** neutralizes it. A genre-savvy or mercenary group draws the obvious conclusion: don't go to the throne at all — cut the conduit / collapse the gallery / re-inscribe the ward from the safe side and walk away. That fully answers the *town* threat (the only thing Serica's neighbors care about) while skipping the finale and writing off Donato. The module has no text for this and the GM is left improvising the adventure's own climax away.
> **Fix:** support it as a real dark ending rather than blocking it. Seal-and-leave **neutralizes the march on Fallcrest but dooms Donato and the trapped cutters and forfeits the vault** — which lands the party squarely in Serica's "father dead + they got paid/greedy → **enemy**" aftermath (already in her entry). Add two sentences to GM Notes naming this ending and its cost, so the table's cleverness is met, not stonewalled. Bonus: the trapped-cutters clock (see E1) is the pressure that makes abandoning them *feel* like a choice.

→ Response:
→ Status:

---

## C. NPC motivation cracks

### C1 🟠 — Why is Donato special, and why is his conversion slow when the Voice raises the dead instantly?

> [!WARNING]
> The Haruspex reanimates captured cutters *the same night* (nightly clock; the labor-dead). Yet Donato has been held "two nights" and is only "half-made" into the Centurion. If any living body becomes a commander, it would have had a Centurion days ago from the first captive; if it doesn't, nothing says why Donato qualifies. Right now it reads as plot convenience that the *one* named prisoner is the *one* being slow-converted.
> **Fix (latent in the text):** the Haruspex recognizes **rank**. Donato is the **quarrymaster** — the officer who led the crew and *broke the seal* — so it reads him as command material and everyone else as rank-and-file (→ labor-dead). Making a Centurion is a deliberate, ritual *installation*, not a raising, so it takes nights (and can be interrupted). State this in Donato's Role and the Order of Battle; it also retroactively justifies the nightly clock's stakes.

→ Response:
→ Status:

### C2 🟠 — The self-authorizing loop is the finale's linchpin and is never spelled out

> [!WARNING]
> The whole con rests on a subtle idea: the Haruspex "cannot command," so it **installs** Donato as Centurion to obtain authority — then obeys "its" commander (really itself through a puppet). For the CON key (b) to not feel like a cheat, the GM must understand *why a freed Donato can suddenly command the devil*: because the Haruspex, by its own protocol, already granted Donato genuine command authority — freeing him just removes the puppet-strings, leaving that authority pointed the wrong way. This mechanism is implied across three sections but stated nowhere.
> **Fix:** one clear sentence in the Relic/Voice block: *"By installing Donato as Centurion, the Haruspex has — by its own protocol — vested real command authority in him; break its control and that authority turns against it."* Now the GM can play the loop and adjudicate the con confidently.

→ Response:
→ Status:

---

## D. Pacing and the boring-risk

### D1 🟠 — Scene 5 carries an interrogation + five clue-stations + a conditional fight; it will sag into a 90-minute room-read

> [!WARNING]
> The War-Room is the richest scene, which is also its danger: a live interrogation, five described clue-stations, holding cells, murder-holes, and a possible zombie fight, all in one room, invites the players to methodically strip-mine every station while the GM info-dumps. For an *introductory* group this is where momentum dies.
> **Fix:** rank the stations. Mark the **war-map (target = Fallcrest)** and the **Centurion's regalia (Donato)** as *must-surface* (the GM volunteers these); the standing-orders wall, cells, and labor-dead are *optional/on-a-check*. And give the interrogation a spine — it asks **three questions, escalating**; after the third, it *classifies and acts*, so the scene can't idle indefinitely.

→ Response:
→ Status:

### D2 🟠 — Two Lictor encounters risk being the same puzzle twice

> [!WARNING]
> S4 and S7 are both "you can't damage it, sever its command." If S4's resolution is "bloody it → it withdraws" and S7's is "cut the conduit," a table may feel it solved the same problem twice with a reskin.
> **Fix:** make the *shape* differ. In **S4 there is no permanent option** — the only outs are flee/bypass/rescue-and-retreat (no conduit junction exists there), so the beat is *survival and dread*. **S7 is the first place a permanent kill exists** (the junction / surface-lure / arc-forge), so the beat is *problem-solved catharsis*. Say this explicitly in each scene so the GM plays them as escalation, not repetition.

→ Response:
→ Status:

---

## E. Questions players will ask that have no answer

### E1 🟡 — "How long do the trapped cutters actually have?"

> [!IMPORTANT]
> The immediate clock is "cutters die within days" — no number. The first thing a cautious party asks is whether they can rest, or go back to town for muscle. Without a figure the GM can't answer, and the "immediate clock" has no bite (and B1's dark choice has no weight).
> **Fix:** pin it. E.g., **the trapped cutters have ~48 hours; each night that passes (see A4) one dies**, and any still alive are freed if the party reaches the holding cells (Scene 5). Now resting and detouring cost something countable.

→ Response:
→ Status:

### E2 🟡 — "Okay, how do we re-seal it?"

> [!IMPORTANT]
> "Bunker re-sealed" is named as the **best** outcome (Scene 8 Ways-out) but is never defined as an action. After a stand-down or a kill, players will absolutely try to make sure it stays down, and the GM has nothing.
> **Fix:** define it in one line — after the Voice is relieved or destroyed, the threshold **ward-glyph can be re-inscribed (DC 14 Arcana)** or the deep gallery **collapsed** (the Scene 3 charges / crane rig), entombing the Ninth Reach. Tie the "best" ending to actually doing it.

→ Response:
→ Status:

### E3 🟡 — "What's the counter-sign, and where do we actually get it?"

> [!IMPORTANT]
> The Bael Turath counter-sign is load-bearing **twice** (Scene 5 classification; stand-down protocol part 2), but no scene concretely *contains* it. The listed sources are soft: Renzo's entry says he heard the Voice's *orders* (not specifically the watchword); "a captured kobold" may or may not know a security token; "bluff" is the safety net. If the table wants the real word, the GM has to invent where it lives.
> **Fix:** give it a guaranteed diegetic home and an actual word. Put the counter-sign in **Donato's dig-journal** (he transcribed the phrase the kobolds shout) *and* on **Renzo's lips** (make it explicit he remembers it) — two guaranteed sources plus the bluff. Pick the word now (e.g., an Infernal challenge/response pair) so it's a prop players can *say*.

→ Response:
→ Status:

---

## F. Canon & rules consistency

### F1 🟡 — Default play is mowing down dozens of kobolds, which cuts against the setting's stated ethos

> [!IMPORTANT]
> `setting-guide.md` (D&D best practices) is explicit: *"People are evil because of the choices they make, not because of their heritage. Even orcs, goblins, and gnolls are accepted."* The module's default combat loop is slaughtering 10 + 10 + 8 compelled kobolds, with the sympathetic/redeemable framing (Ssvara, the mercy seeds) sitting mostly in the optional Scene 6. A group that just fights will experience this as heritage-coded genocide, exactly what the setting disowns.
> **Fix:** promote the compulsion up front. In Scene 2's first contact, foreground that the kobolds are **enthralled, not evil** (the badly-copied drill, the brass-sheen tell, one breaking free of the Voice for a moment), and offer a visible **non-lethal / rout option** — drop the Voice's reach (noise, distance) and nearby kobolds *stop fighting*. Ties the ethos to the core mechanic (the Voice's range) instead of leaving it to an optional scene.

→ Response:
→ Status:

### F2 🟡 — A full-HP anchored CR 3–4 + adds + a hostile Donato is over the line for four 3rd-level PCs

> [!IMPORTANT]
> Per `encounter_Building.md` (solo table), four 3rd-level PCs are matched to a **CR 3** solo as "satisfying but difficult," with CR 4 already **deadly**; the same doc warns to fear any monster that can drop a PC in one hit. Scene 8 stacks a CR 3–4 anchored boss **plus** *call the reserve* (2 lemures/kobolds) **plus** conduit-arc hazards **plus** the converted Donato acting against the party. That's fine *if* they cut the conduit first (halves HP, ends the reserve) — but via the A3 skip path they arrive at full strength and blind, i.e. a plausible TPK in an *introductory* module. (Monster picks themselves check out against `monster_cr.md` — Kobold Trapsmith, Zombie, Lemure, Bearded-Devil chassis all exist at the cited CRs.)
> **Fix:** make the crippling reachable in the room (see A2/A3 — conduit cut *here*), and add an explicit **soft-floor**: the Haruspex, being anchored and craving relief, *offers terms / pauses to interrogate* rather than opening with alpha-strike lethality — giving a losing party an off-ramp into the con. State a max "one PC down before it parleys" beat so the deadly boss can't just quietly TPK them.

→ Response:
→ Status:

---

## G. Descriptive details that would earn their keep

### G1 🔵 — Give the Voice one fixed auditory signature

> [!TIP]
> The Voice appears in five scenes; a single unchanging tell makes players recognize it instantly and builds dread. Pick one and use it every time: e.g., it **always opens in status-report cadence** ("*Report received…*") with a **half-second delay, like a relay**, and never contracts its words. When that cadence later comes out of *Donato's* mouth, the table feels it in their spine.

→ Response:
→ Status:

### G2 🔵 — Make the brass-sheen-in-the-eyes tell a consistent through-line motif

> [!TIP]
> The "host goes rigid, brass sheen in the eyes, nearest vein flaring" tell (Voice section) is a great physical cue — use it *identically* on the first drilled kobold (Scene 2), the labor-dead (Scene 5), and Donato (Scene 8), so players learn to read "the Voice is driving this one" on sight, and dread it turning up in the father's eyes. A recurring visual grammar the players decode themselves.

→ Response:
→ Status:

---

## Triage — what I'd fix first

If only five before running: **A1, A2, A3, A5, E3.** These are the ones that either contradict on-screen (A1, A2), or leave the GM without the machinery to run the climax the module points at (A3 skip-path, A5 con/rescue resolution, E3 the counter-sign that's load-bearing twice but never placed). B1 (seal-and-leave) is close behind if your table skews clever/mercenary. Everything in G is optional polish.

*Possibly deliberate, not bugs:* the **reinforcements skip** (A3) may be an intended stealth-win — if so it still needs the missing-branch prep, not removal. The **finale lethality** (F2) may be an intended "deadly by design" capstone — if so, keep it but wire in the soft-floor so an intro group can retreat into the con rather than wipe. The **nightly clock** (A4) may be intended as pure backstory colour — if so, say so in the text and stop implying live pressure ("reward speed").*
