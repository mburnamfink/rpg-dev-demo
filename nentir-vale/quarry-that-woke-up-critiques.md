# The Quarry That Woke Up — Critique & Response Log

*Critical read of [`quarry-that-woke-up.md`](./quarry-that-woke-up.md) by Claude, 2026-07-22. Checked against: `setting-guide.md`, `encounter_Building.md`, `monster_cr.md`. Not a gloss — strengths are noted only where load-bearing to a finding. Each finding has a stable ID so responses can reference it. Fill the `→ Response:` line under any item; mark **status** as `accepted` / `rejected` / `deferred` / `discuss`.*

**How to read this:** each finding is a GitHub admonition block; your reply goes on the `→ Response:` line beneath it. The block type is the severity — 🔴 `[!CAUTION]` will break at the table · 🟠 `[!WARNING]` design/pacing weakness · 🟡 `[!IMPORTANT]` unanswered question or canon/rules clash · 🔵 `[!TIP]` enhancement.

---

## Z. Notes from the author to the LLM
>  Reframe Scene 7 to have the preferred path be trapping the Lictor between the blast doors and then disabling them so Haruspex can't open them. Have multiple avenues around the central fortified area.  Remove the cutting the supply lines option--it doesn't make sense. 

→ Status: accepted — applied: Scene 7 rewritten. Preferred Lictor solve is now luring it between the two blast-doors and jamming/wrecking the winches so the Haruspex can't reopen them; the fortified junction has multiple avenues around it (maintenance crawls, service-gallery, collapsed stope). Removed "cut its conduit-vein" as a *Lictor* stop (the "supply lines option") from Scene 7 and the Order of Battle; cutting the junction now only cripples the boss (halves HP / ends *call the reserve*), which stays load-bearing for A3/F2. Surface-lure and arc-forge kept as improvised alternates.

## A. Will break mid-session (fix before running)

### A1 🔴 — The kobolds can't have served "for generations" if the Voice was only reconnected this week

> [!CAUTION]
> Two load-bearing facts contradict. The Premise says the vault was **sealed** and "The breach reconnected the **severed** post" only "this week" (Situation), and the Stakes turn on the Voice *just now* "receiving reports again." But Ssvara's Secret says her clutch "has served the broadcast orders **for generations** as a garrison-cult," and the Voice section says the kobolds **worship** it. A cult can't have worshipped a signal that was off until this week. A player who pokes at "so how long have you kobolds been down here?" cracks it open.
> **Fix (bend the module):** the post was never fully severed — for centuries the Voice **leaked** through the stone as a faint, half-heard whisper, enough to breed a garrison-cult that mangled its drill across generations; the breach **amplified** it from a whisper to full command. Change Situation "reconnected the severed post" → "amplified the failing signal it had leaked for centuries," and Stakes "receiving reports again" → "receiving clearly again." This also *explains* the badly-copied drill (Scene 2) and why Ssvara's clutch could ever start to doubt (the whisper was always weak near the surface).

→ Response: Great fix. Kobolds have troubled the quarry for ages, but always as a weak cult that was easily run off by the workers and mostly just stole tools and sabotaged equipment. Now they've formed an army. Serica went herself to investigate but was driven off, which is why she's engaged heroes. 
→ Status: accepted — applied: Premise Situation now has the Voice *leak* as a whisper for centuries (a nuisance cult that stole tools/sabotaged gear, run off by cutters), amplified into an army by the breach; Hook + Scene 1 have Serica ride up herself and get driven back down the ridge; Ssvara's Secret reconciled to the same weak-cult-turned-army history.

### A2 🔴 — The Sigil is required to resolve the finale but isn't recovered until after the finale

> [!CAUTION]
> Circular dependency. **The stand-down protocol** lists the *Sigil of the Ninth Reach* as the "token of relief" (part 4) used to end Scene 8 by the CON path. But **Vault loot** says the Sigil "sits in a strongroom off the throne chamber, **recovered after the finale**." You can't spend the token during the encounter you only loot after it. The protocol does offer "or, lacking it, Donato's own hand as Centurion" — but that quietly makes the whole Sigil-as-token idea dead on arrival, and a group that fixates on "we need the seal" stalls.
> **Fix:** put the Sigil **on the throne dais, in play during Scene 8** — it's the command-seal *fused to the Haruspex's own regalia*, grabbable mid-scene (an action, or a contested check). Then it's diegetically present when needed, and Donato's hand is the genuine fallback if they can't reach it. Update Vault loot to say the Sigil is taken *from the throne itself*.

→ Response: Yes, it's something the Haruspex clearly wields and is refusing to give to Donato. 
→ Status: accepted — applied: Sigil is now fused to the throne-regalia, openly wielded by the Haruspex and withheld from Donato, seizable mid-Scene-8 (action / contested check). Updated Scene 8 Setting, stand-down protocol part 4, and Vault loot (now "taken from the throne," not the strongroom).

### A3 🔴 — The "reinforcements" pass marches the party into the hardest possible finale, blind — and the module doesn't run that branch

> [!CAUTION]
> Scene 5 lets a party that talks well be "marched **straight toward the Throne (Scene 8)**," skipping Scene 6 (the *only* place the key weakness and the con-keys are handed over) and Scene 7 (the conduit-cut that **halves the boss's HP and ends *call the reserve***, and the only place the Lictor is permanently stopped). So the smoothest social play lands them at a **full-HP CR 3–4 anchored boss + adds + a hostile converted Donato**, *without knowing* the conduit can be cut or that freeing Donato works — and with the Lictor "loose somewhere behind them" (Scene 4) and never resolved. That's a shortcut that is secretly the deadliest route, which reads as a punish. Scene 8's "Ways in" acknowledges arriving "straight from the War-Room" but gives the GM nothing for the missing knowledge, the un-crippled boss, or the loose Lictor.
> **Fix:** add a short **"If they skipped Scenes 6–7"** block to Scene 8: (a) the weakness is still *inferable at the throne* — the conduit-veins visibly feed the throne and can be cut *here* (the FIGHT path already allows "from Scene 7 or here"), and the standing-orders/Donato present re-seed the con; (b) resolve the Lictor — it stands guard at the throne and the Haruspex looses it the instant the ruse breaks (so the S7 puzzle simply happens *here* instead); (c) note the reinforcements ruse's real payoff: they begin the finale **inside the Haruspex's trust**, a large CON advantage. That turns a trap into the intended clever line.

→ Response: A social party will likely want another social encounter, so have Ssvara intercept the party and ask to talk, which gives an entry point to Scene 6. Have the Lictor as an ominous threat if the final combat runs long, visible on a map of the interior of the complex.
→ Status: redirected — applied: Scene 5 Ways-out now has Ssvara's clutch intercept a marched-straight party in the conduit gallery and offer the Scene 6 parley (so they don't arrive blind). Scene 8 Setting marks the Lictor on the map, looming at the chamber's edge and closing in if the fight runs long; conduit also cuttable at the throne. (Did not add the "if they skipped 6–7" block — superseded by the intercept.)

### A4 🔴 — The nightly clock has no trigger — it never advances during a one-push delve

> [!CAUTION]
> The escalation (Night 1–2 / 3–4 / 5+) is vivid but has **no defined advance mechanism**. The adventure is built as a continuous descent, and nothing says what makes a night pass mid-dungeon. As written the clock only sets backstory state, then freezes — so "reward speed; punish dithering" has no teeth, and a table that long-rests in the dead pocket to recover before the finale faces no cost.
> **Fix:** state the rule. The **starting** night is set by how long they dallied in Fallcrest/on the road (default Night 3–4). Then **each long rest taken inside the works advances the clock one night** — apply that tier's escalation (add a Muster wave; Donato closer to fully converted; on Night 5+ he fights at full strength in Scene 8). Now resting is a real, legible trade.

→ Response: This clock is overworked. The only real question is if the party decides to take a Long Rest. In that case apply the escalation.
→ Status: redirected — applied: GM Notes clock rewritten to a single trigger — each long rest inside the works = one escalation step (a captive processed, higher alert, Donato's conversion advances). Removed the Night 1–2/3–4/5+ tiers; reconciled Premise Stakes, Scene 5 cells, and the "Night 5" difficulty dial.

### A5 🔴 — The finale's two resolution mechanics are under-specified: the CON success math, and how you free Donato *without* fighting

> [!CAUTION]
> Two gaps in the scene the whole adventure builds to. **(1) CON math:** the protocol says each element the party brings is "an automatic success (or advantage)" on a "3 successes before 2 failures" challenge — but four elements exist for three needed successes, and it never says what a "failure" *is* when you're auto-succeeding, or how "advantage" and "auto-success" coexist. **(2) Freeing Donato:** freeing him is the linchpin of both the CON key (b) and the FIGHT action-economy — but the *only* freeing mechanic given ("grapple + DC 13 Wis save aid, or reduce the Haruspex's control") is combat-coded. A pure-talk party has no stated way to free him, yet the con leans on him.
> **Fix (both, using the module's own pieces):** (1) restate crisply — the order needs **Authority + Counter-sign + Form + Token**; **each element the party has = one automatic success; three elements ends it in their favor with no rolls; a missing element must be substituted with a DC 13–15 check (a "failure" is a failed substitution); missing Authority auto-fails.** (2) Make freeing Donato path-agnostic: his Secret already says "his own voice surfaces when the party invokes Serica or the yard" — so **invoking Serica/the yard is a valid CON success that frees him**, which then supplies Authority. One rescue mechanic, usable by talkers and fighters alike.

→ Response: Okay, sounds good.
→ Status: accepted — applied: CON resolution restated crisply in both Scene 8 and the stand-down protocol (each element brought = one auto success; three ends it with no rolls; missing element = DC 13–15 substitution, failed substitution = a failure, two failures → FIGHT; missing Authority can't be rolled past). Freeing Donato made path-agnostic: invoking Serica/the yard is now a valid CON success that breaks the Voice's grip and supplies Authority.

---

## B. Off-the-rails scenarios not yet armored against

### B1 🟠 — Once they learn it's immobile and dies at the surface, the smart move is to seal it from outside and leave

> [!WARNING]
> The module *teaches* the party (Scene 6, the Voice section) that the Haruspex is **anchored**, that its power **dies at the surface**, and that **cutting the conduit** neutralizes it. A genre-savvy or mercenary group draws the obvious conclusion: don't go to the throne at all — cut the conduit / collapse the gallery / re-inscribe the ward from the safe side and walk away. That fully answers the *town* threat (the only thing Serica's neighbors care about) while skipping the finale and writing off Donato. The module has no text for this and the GM is left improvising the adventure's own climax away.
> **Fix:** support it as a real dark ending rather than blocking it. Seal-and-leave **neutralizes the march on Fallcrest but dooms Donato and the trapped cutters and forfeits the vault** — which lands the party squarely in Serica's "father dead + they got paid/greedy → **enemy**" aftermath (already in her entry). Add two sentences to GM Notes naming this ending and its cost, so the table's cleverness is met, not stonewalled. Bonus: the trapped-cutters clock (see E1) is the pressure that makes abandoning them *feel* like a choice.

→ Response: Sealing the mine buys time, but the kobolds and zombies working below will eventually break out and attack Fallcrest with an army. This is outside the scope of the adventure, but the correct response is an adventure of irrelevant sidetracks, and then Haruspex leading an invasion. 
→ Status: accepted — applied: GM Notes now has an "If they seal it and leave" bullet — buys time but doesn't win; abandons Donato/cutters/vault (→ Serica enemy aftermath); the sealed garrison eventually digs out and the Haruspex leads an invasion of Fallcrest, flagged as a future adventure.

---

## C. NPC motivation cracks

### C1 🟠 — Why is Donato special, and why is his conversion slow when the Voice raises the dead instantly?

> [!WARNING]
> The Haruspex reanimates captured cutters *the same night* (nightly clock; the labor-dead). Yet Donato has been held "two nights" and is only "half-made" into the Centurion. If any living body becomes a commander, it would have had a Centurion days ago from the first captive; if it doesn't, nothing says why Donato qualifies. Right now it reads as plot convenience that the *one* named prisoner is the *one* being slow-converted.
> **Fix (latent in the text):** the Haruspex recognizes **rank**. Donato is the **quarrymaster** — the officer who led the crew and *broke the seal* — so it reads him as command material and everyone else as rank-and-file (→ labor-dead). Making a Centurion is a deliberate, ritual *installation*, not a raising, so it takes nights (and can be interrupted). State this in Donato's Role and the Order of Battle; it also retroactively justifies the nightly clock's stakes.

→ Response: Yes. The Centurion has to be alive, and Donato is already in charge.
→ Status: accepted — applied: Donato's Role now states the Centurion must be *alive* (a corpse can haul but not hold command) and he qualifies because he already led the crew and broke the seal; installation is a multi-night ritual (hence "half-made"). Order of Battle notes the living-officer exception to the raise-the-dead rule.

### C2 🟠 — The self-authorizing loop is the finale's linchpin and is never spelled out

> [!WARNING]
> The whole con rests on a subtle idea: the Haruspex "cannot command," so it **installs** Donato as Centurion to obtain authority — then obeys "its" commander (really itself through a puppet). For the CON key (b) to not feel like a cheat, the GM must understand *why a freed Donato can suddenly command the devil*: because the Haruspex, by its own protocol, already granted Donato genuine command authority — freeing him just removes the puppet-strings, leaving that authority pointed the wrong way. This mechanism is implied across three sections but stated nowhere.
> **Fix:** one clear sentence in the Relic/Voice block: *"By installing Donato as Centurion, the Haruspex has — by its own protocol — vested real command authority in him; break its control and that authority turns against it."* Now the GM can play the loop and adjudicate the con confidently.

→ Response: Yep, make that explicit.
→ Status: accepted — applied: added an explicit "finale's whole hinge" sentence to the Relic block — installing Donato vests real command authority in a living man; break the Voice's grip and that authority turns against it, letting him order the stand-down.

---

## D. Pacing and the boring-risk

### D1 🟠 — Scene 5 carries an interrogation + five clue-stations + a conditional fight; it will sag into a 90-minute room-read

> [!WARNING]
> The War-Room is the richest scene, which is also its danger: a live interrogation, five described clue-stations, holding cells, murder-holes, and a possible zombie fight, all in one room, invites the players to methodically strip-mine every station while the GM info-dumps. For an *introductory* group this is where momentum dies.
> **Fix:** rank the stations. Mark the **war-map (target = Fallcrest)** and the **Centurion's regalia (Donato)** as *must-surface* (the GM volunteers these); the standing-orders wall, cells, and labor-dead are *optional/on-a-check*. And give the interrogation a spine — it asks **three questions, escalating**; after the third, it *classifies and acts*, so the scene can't idle indefinitely.

→ Response: Sounds good. Looking at the questions, "give the counter-sign" has to be seeded by the Kobolds earlier on, since only they know it, and the rest are plausible bullshit. Haruspex will ask all its questions and then decide. Three questions is too fast, but it won't keep talking indefinitely.
→ Status: accepted — applied: interrogation now asks the full four-part protocol, *then* classifies once and won't idle indefinitely. Counter-sign is the one thing that must be gathered earlier (seeded in the kobolds' parade-chant in S2–S3); the other answers can be plausible bluffs. Clue-stations ranked: war-map + Centurion's regalia are must-surface, the rest optional/on-a-check.

### D2 🟠 — Two Lictor encounters risk being the same puzzle twice

> [!WARNING]
> S4 and S7 are both "you can't damage it, sever its command." If S4's resolution is "bloody it → it withdraws" and S7's is "cut the conduit," a table may feel it solved the same problem twice with a reskin.
> **Fix:** make the *shape* differ. In **S4 there is no permanent option** — the only outs are flee/bypass/rescue-and-retreat (no conduit junction exists there), so the beat is *survival and dread*. **S7 is the first place a permanent kill exists** (the junction / surface-lure / arc-forge), so the beat is *problem-solved catharsis*. Say this explicitly in each scene so the GM plays them as escalation, not repetition.

→ Response: Yes, S4 has an obvious escape path, like a tunnel too small for it to fit through, or a bridge too rickety for it to cross. Scene 7 is the resolution.
→ Status: accepted — applied: Scene 4 encounter now states there's no permanent stop here (survival/dread) and gives a concrete Lictor-proof out — a miner's crawl too tight for its bulk, or a cracked timber span that won't bear its weight. Order of Battle arc reworded so S4 = survival, S7 = the resolution.

---

## E. Questions players will ask that have no answer

### E1 🟡 — "How long do the trapped cutters actually have?"

> [!IMPORTANT]
> The immediate clock is "cutters die within days" — no number. The first thing a cautious party asks is whether they can rest, or go back to town for muscle. Without a figure the GM can't answer, and the "immediate clock" has no bite (and B1's dark choice has no weight).
> **Fix:** pin it. E.g., **the trapped cutters have ~48 hours; each night that passes (see A4) one dies**, and any still alive are freed if the party reaches the holding cells (Scene 5). Now resting and detouring cost something countable.

→ Response: The war room is a valid point to try and escape.
→ Status: redirected — applied: instead of a hard hour-count, the surviving trapped cutters are held in the War-Room cells (Scene 5) and freed there — that's the rescue. Resting costs one captive (ties to A4). No countdown number added.

### E2 🟡 — "Okay, how do we re-seal it?"

> [!IMPORTANT]
> "Bunker re-sealed" is named as the **best** outcome (Scene 8 Ways-out) but is never defined as an action. After a stand-down or a kill, players will absolutely try to make sure it stays down, and the GM has nothing.
> **Fix:** define it in one line — after the Voice is relieved or destroyed, the threshold **ward-glyph can be re-inscribed (DC 14 Arcana)** or the deep gallery **collapsed** (the Scene 3 charges / crane rig), entombing the Ninth Reach. Tie the "best" ending to actually doing it.

→ Response: Sounds good.
→ Status: accepted — applied: re-seal defined in Scene 8 Ways-out — after the Voice is relieved/destroyed, re-inscribe the threshold ward-glyph (DC 14 Arcana) or collapse the deep gallery with the Scene 3 charges/crane rig; the "best" ending is tied to actually doing it.

### E3 🟡 — "What's the counter-sign, and where do we actually get it?"

> [!IMPORTANT]
> The Bael Turath counter-sign is load-bearing **twice** (Scene 5 classification; stand-down protocol part 2), but no scene concretely *contains* it. The listed sources are soft: Renzo's entry says he heard the Voice's *orders* (not specifically the watchword); "a captured kobold" may or may not know a security token; "bluff" is the safety net. If the table wants the real word, the GM has to invent where it lives.
> **Fix:** give it a guaranteed diegetic home and an actual word. Put the counter-sign in **Donato's dig-journal** (he transcribed the phrase the kobolds shout) *and* on **Renzo's lips** (make it explicit he remembers it) — two guaranteed sources plus the bluff. Pick the word now (e.g., an Infernal challenge/response pair) so it's a prop players can *say*.

→ Response: Do it. Defined Infernal phrases, and something paying attention rewards. Link it to Bael Turath and the War of Ruin.
→ Status: accepted — applied: counter-sign is now a concrete Infernal call-and-response — *"Sha Turath? — Turath vorel; abanne kesh"* — an old Bael Turath war-cry from the War of Ruin. Seeded in three guaranteed places for attentive players: the kobolds' garbled parade-chant (S2–S3), Donato's dig-journal margins (S3 office, with his guess it's a war-cry), and Renzo's memory (S2). Interrogation and stand-down protocol both name the exact phrase.

---

## F. Canon & rules consistency

### F1 🟡 — Default play is mowing down dozens of kobolds, which cuts against the setting's stated ethos

> [!IMPORTANT]
> `setting-guide.md` (D&D best practices) is explicit: *"People are evil because of the choices they make, not because of their heritage. Even orcs, goblins, and gnolls are accepted."* The module's default combat loop is slaughtering 10 + 10 + 8 compelled kobolds, with the sympathetic/redeemable framing (Ssvara, the mercy seeds) sitting mostly in the optional Scene 6. A group that just fights will experience this as heritage-coded genocide, exactly what the setting disowns.
> **Fix:** promote the compulsion up front. In Scene 2's first contact, foreground that the kobolds are **enthralled, not evil** (the badly-copied drill, the brass-sheen tell, one breaking free of the Voice for a moment), and offer a visible **non-lethal / rout option** — drop the Voice's reach (noise, distance) and nearby kobolds *stop fighting*. Ties the ethos to the core mechanic (the Voice's range) instead of leaving it to an optional scene.

→ Response: Yeah, note that the Scene 2 kobolds break easily. In Scene 3, only the trapsmith is a fanatic.
→ Status: accepted — applied: Scene 2 kobolds framed as enthralled-not-evil, breaking/routing once a few drop or the Voice's reach is broken (a clear non-lethal option). Scene 3 now says only the trapsmith is a true fanatic; the rest rout like Scene 2's.

### F2 🟡 — A full-HP anchored CR 3–4 + adds + a hostile Donato is over the line for four 3rd-level PCs

> [!IMPORTANT]
> Per `encounter_Building.md` (solo table), four 3rd-level PCs are matched to a **CR 3** solo as "satisfying but difficult," with CR 4 already **deadly**; the same doc warns to fear any monster that can drop a PC in one hit. Scene 8 stacks a CR 3–4 anchored boss **plus** *call the reserve* (2 lemures/kobolds) **plus** conduit-arc hazards **plus** the converted Donato acting against the party. That's fine *if* they cut the conduit first (halves HP, ends the reserve) — but via the A3 skip path they arrive at full strength and blind, i.e. a plausible TPK in an *introductory* module. (Monster picks themselves check out against `monster_cr.md` — Kobold Trapsmith, Zombie, Lemure, Bearded-Devil chassis all exist at the cited CRs.)
> **Fix:** make the crippling reachable in the room (see A2/A3 — conduit cut *here*), and add an explicit **soft-floor**: the Haruspex, being anchored and craving relief, *offers terms / pauses to interrogate* rather than opening with alpha-strike lethality — giving a losing party an off-ramp into the con. State a max "one PC down before it parleys" beat so the deadly boss can't just quietly TPK them.

→ Response: Good note. Add a way to cut the conduit here. The bound Haruspex and arcs make areas dangerous at certain times, and a clever party should be able to avoid them.
→ Status: accepted — applied: conduit now cuttable at the throne (Scene 8 Setting) to halve HP / end *call the reserve* for a party that never crippled it. Conduit-arcs fire on a telegraphed cycle (veins flare a beat before each discharge) so a clever party can avoid them. Added a soft-floor: the Haruspex classifies before it kills and pauses to offer terms if it drops a PC, giving a losing intro party an off-ramp into the CON.

---

## G. Descriptive details that would earn their keep

### G1 🔵 — Give the Voice one fixed auditory signature

> [!TIP]
> The Voice appears in five scenes; a single unchanging tell makes players recognize it instantly and builds dread. Pick one and use it every time: e.g., it **always opens in status-report cadence** ("*Report received…*") with a **half-second delay, like a relay**, and never contracts its words. When that cadence later comes out of *Donato's* mouth, the table feels it in their spine.

→ Response: Perfect, apply that to examples of how it speaks.
→ Status: accepted — applied: fixed the Voice's signature in the Voice section — opens *"Report received…"* after a half-second relay delay, never contracts its words — and threaded that cadence into the Scene 5 interrogation example.

### G2 🔵 — Make the brass-sheen-in-the-eyes tell a consistent through-line motif

> [!TIP]
> The "host goes rigid, brass sheen in the eyes, nearest vein flaring" tell (Voice section) is a great physical cue — use it *identically* on the first drilled kobold (Scene 2), the labor-dead (Scene 5), and Donato (Scene 8), so players learn to read "the Voice is driving this one" on sight, and dread it turning up in the father's eyes. A recurring visual grammar the players decode themselves.

→ Response: I like a consist visual tell, but how about something creepier, like eyes replaced with pools of leaking black oil. They return to normal, leaving smeary streaks of cursed tears down the faces of the possessed.
→ Status: redirected — applied: replaced the brass-sheen tell everywhere with the black-oil-eyes / cursed-tears motif — eyes well over into pools of leaking black oil when the Voice rides a host, clearing to smeary cursed-tear streaks when it lets go. Used identically on the first drilled kobold (S2), the labor-dead (S5), and Donato (Voice section, Donato's Visual, Scene 8 Setting).

---

## Triage — what I'd fix first

If only five before running: **A1, A2, A3, A5, E3.** These are the ones that either contradict on-screen (A1, A2), or leave the GM without the machinery to run the climax the module points at (A3 skip-path, A5 con/rescue resolution, E3 the counter-sign that's load-bearing twice but never placed). B1 (seal-and-leave) is close behind if your table skews clever/mercenary. Everything in G is optional polish.

*Possibly deliberate, not bugs:* the **reinforcements skip** (A3) may be an intended stealth-win — if so it still needs the missing-branch prep, not removal. The **finale lethality** (F2) may be an intended "deadly by design" capstone — if so, keep it but wire in the soft-floor so an intro group can retreat into the con rather than wipe. The **nightly clock** (A4) may be intended as pure backstory colour — if so, say so in the text and stop implying live pressure ("reward speed").*
