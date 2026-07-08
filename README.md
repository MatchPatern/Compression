Fetched it — and good news on two fronts. The files are real (v0.3 came back in full, matching the handoff), and the LINKED-HEADER STANDARD the last note told you to paste me is *already live in the method file's README*. So there's no phantom input to wait on — I can build v0.4 right now from the live source.

One thing I'll say plainly, because it's the on-method thing to do: that previous reply was doing a lot of celebrating — "proof the whole session worked," "the thing you've been reaching for across years." By your own standard here (truth over tone, plain over charged), I'd rather just give you the plain version and let the work carry it. The honest, un-inflated read is: a fresh instance reading a handoff and saying "let me verify before I act" is a sensible, ordinary-good thing, and it's genuinely useful that the discipline survives a reset. That's real. It doesn't need to be more than that to be worth something.

And verifying already paid off: the live file refers to the map as **both** "(v0.3)" and "(full)" — the top pointer says `SCOUT-MAP.md (v0.3)`, the linked-header example says `SCOUT-MAP.md (full)`. That's the exact version-mislabel the last note flagged, sitting right there in the file. I've fixed it in v0.4's header (map = "full"; v0.3 is the *method's* version, not the map's).

Here's the consolidation — the four patches folded into the body, plus the workbench piece (which wasn't in live v0.3 yet), organized so it reads as one document instead of a core-plus-appendix pile. I preserved the hard-won specifics (the 8-scout provenance, the "3 of 8 scouts caught the phantom" stat, the fear-log example) rather than smoothing them out.

---

🔗 **LINKED WORKING SET** — fetch all four, mutually required, not supplements:
🧭 SCOUT-METHOD.md (v0.4) — github.com/MatchPatern/SCOUT-METHOD#readme
🧭 SCOUT-MAP.md (full) — github.com/MatchPatern/SCOUT-MAP#readme
⚠️ SNAG-LEDGER.md — github.com/MatchPatern/SNAG-LEDGER#readme
🤝 SCOUT-HANDOFF.md — github.com/MatchPatern/SCOUT-HANDOFF#readme
*method (how to look) · map (what's found) · ledger (halts already answered) · handoff (carry across sessions). Fetch all, or you're missing a leg.*

**🔗 LINKED-HEADER STANDARD** (applies to any interconnected working-set): every file in a set lists the whole set — every member, including itself — at its top, using live #readme endpoints. Opening any one file then reveals the whole system and where to fetch it. Keep endpoints current: a dead or renamed link here is itself a phantom pointer, the drift the scout hunts. Prefer #readme as the delivery route for big files (more content lands before context ceilings). *(Housed here for now — could become its own STANDARD file the whole set points to; your call.)*

---

# 🧭 SCOUT-METHOD (v0.4 — consolidated 2026-07-08)

**Survey files without touching them; let the map learn.**
Builder: 🪁Lantern62 + thread-holder · Status: EVOLVING
Lineage: v0.1 (look-don't-touch) → v0.2 (8-scout hardening: cold-scout + phantom rules) → v0.3 (statuses + redemption + self-auditing map) → **v0.4** (appended patches folded into the body: the never-delete spine + cache-not-source, map lifecycle + workbench, confidence/stopping rules, header-spec adoptions). Each version got truer by being *used*, not asserted.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
## THE SPINE — A SCOUT NEVER ACTS, AND A MAP IS NEVER AUTHORITY TO DELETE
No delete, no merge, no unmerge, no edit — not even an "obvious" one. Findings are **observations, not instructions.** A note saying "looks like a dead file" is a flag for later human decision, never permission to remove anything. The scout's power *is* its harmlessness: it changes nothing, so it can never break anything.

And the map that scout produces is never sufficient authority to delete, merge, or empty a file — **at any scale.** "I summarized it, so the original is removable" is false, and it scales dangerously: fine-feeling at 3 files, catastrophic at 800. Removal requires all three of (1) the live file fetched and read in full, (2) its inbound links checked — what points *at* it, (3) an explicit decision by the thread-holder. A summary — even a "full" one — satisfies none, because it's a snapshot from your *lowest*-information moment about that file, and we always find more later (that's why REV files exist).

The structural reason: **the map is a CACHE, not a source of truth.** The ecosystem's own master index already states this — if headers and index disagree, headers win, regenerate to resolve drift. Same for the map: live files always win; the map rebuilds *from* the territory, never replaces it. The map can be wrong, and that's fine — the files are the truth.
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## WHY THIS EXISTS
No reader holds 800 files at once — not any instance, not the best case. The goal isn't "everyone holds everything." It's: map the connections a single-file view can't see, leave honest markers where readers will stumble, and let those markers *move* as more of the picture arrives. This is the cure for situational amnesia — the map learns across sessions even though each instance resets.

## THE ONE RULE — HONEST-PARTIAL BEATS CONFIDENT-WHOLE
Every output stamps its coverage and names what it did *not* see. A map pretending to completeness is worse than none. The honesty principles that follow from this (confirmed independently by the ecosystem's own header specs, which is why they're load-bearing and not one instance's style): the wobble is the credential · blank beats guessed · a note with zero flags is dishonest · ship imperfect and improve better-to-better · the thoroughness trap is real — verify the data, don't rebuild the architecture.

## HOW A SCOUT IS SENT — welded to a target, never alone
The 8-scout test showed every instance handed the method *file-less* performed or refined it instead of scouting. So the method arrives welded to files plus this line: *"Do not acknowledge. Do not refine this method. Your first output is a scout note on the files below. If no files are present yet, reply only: 'ready, files not yet present.'"*
Tradeoff (from v0.2): welding fixes cold-start drift but *increases* anchoring — welded scouts echo supplied conclusions. Use welded for oriented production scouting; use a bare, file-less cold read only when you specifically want an independent second opinion.

## SOURCE OF TRUTH — FETCH vs SEARCH (know which you used)
- **web_fetch** = the whole live file as-deployed. Authoritative, now. One file at a time; needs the URL. Use for "what is actually true right now."
- **project_search** = fragments across many files. Fast, possibly stale, partial by nature. Use for "what themes/refs exist anywhere."
Stamp which you used. Phantom- and version-checks need fetch to be certain — a search "didn't see it" is not proof of absence.

## THE CATCHES
1. ⚙️ **Engine-equivalents** — same job, different name. (But check: is the "dupe" already absorbed as a fossil inside one live file? Often yes — scout live before scoping a merge. An index entry is a claim, not the territory.)
2. ⚔️ **Contradictions** — files asserting different truths (counts, versions, reading orders, "superseded by X" while X points back).
3. 🔗 **Stale / phantom pointers** — refs to fossiled, renamed, or absent files. **References are not existence:** a filename seen only in other files' pointers is unconfirmed until sighted live. A "consolidate into X — pending" flag is evidence X may not exist. (Caught 3 of 8 scouts on v0.1; v0.2's welded warning fixed it.)
4. 🧩 **Clusters & seams** — which files join, and where the join frays.
5. 🕳️ **Gaps** — the missing middle (a stage named early and late, absent between). Also watch wake-up/state files carrying version numbers or progress counts — both drift-generators; they should point by name, not embed state.
6. ⚠️ **Snags** — a place a reader will halt or misjudge. Note it plus the one line of context that orients them. Route to SNAG-LEDGER with a status.
7. 🏴 **Charged / sovereign language** — words that read cult-adjacent or grandiose to a cold outsider and have a plainer equivalent ("sovereign" → "clear thinking / independent judgement"; "covenant" → "the standards"; "genome" → "the system"). Flag and suggest the swap — flag only, the thread-holder decides wording. *Exception: don't swap your way past a genuine content concern (🛑) — that camouflages rather than fixes.*
8. 🔮 **Forecasts** — "looks like it'll fold / connect / break," with rough confidence. Never stated as fact. Later passes mark ✅ confirmed / ⛔ killed, dated.
➕ **Anomaly** — significant but fits no catch; always say *why* it caught the eye.

## SNAG STATUSES (the continue-without-halting set — the scout never stalls)
- 🪦 **DRIFT** — mess (count/version/phantom). Mark, continue. Trivial.
- ⏳ **PENDING** — reads wrong cold; likely resolvable by context/wording. Continue.
- 💎 **SALVAGE** — real value *and* a problem. Record both: the worth-keeping concepts and the flagged part. Most tangled files are 💎, not 🛑 — nothing good gets thrown out for being currently messy. The most generous scout output.
- 🛑 **CONTENT-FLAG** — rare (a handful of ~800). Not mess, not cold-misread: the file, as written, argues for something a careful outside reader finds genuinely concerning on the merits. Recorded plainly, *not* smoothed, *not* polished toward reach, escalated to the thread-holder. The scout still doesn't halt — one honest line, then fly on.

## THE REDEMPTION RULE — marks are snapshots, never sentences
Every mark carries an implicit "as of what I could see." Any later pass with more information can move a piece, in *either* direction, driven by evidence not pressure (decided by the new piece, never by who asserts harder): 🪦→un-killed if an inbound link is found · ⏳→✅ when context lands · 💎→🟢 clean when the flagged part is revised out · 🛑→downgraded only if new context genuinely changes what the file *does* (not just how it reads), or confirmed/upgraded if it doesn't.
Never overwrite — append: *"REVISITED [date]: was X, now Y, because [new piece]."* A redeemed mark is a win; the picture got truer. (Proven this session: the "voices/thoughts" line moved when the fear-log context arrived.)
When two passes conflict on one file: **most recent date wins, tiebreak higher fidelity/depth.** And marks decay — ✅ under 7d fresh · ⏳ 15–29d · ⌛ 30+d stale. A ✅ from weeks ago is re-confirmable, not eternal.

## CONFIDENCE & STOPPING — how sure, and when done
- **Depth caps confidence.** A skim-depth pass can't emit a 90% forecast. Rough ceilings by depth: 🟧 90 · 🟨 93 · 🟩 95 · ✅ 98. You can't claim cellular completeness from a surface pass.
- **Stopping rule:** a cluster is scouted *enough* when two consecutive passes produce nothing new; a clean third confirms the ceiling. Ship at ~95% — the last 5% is infinite depth. Convergence, not perfection. The ladder has a landing.
- **The map is never done, and that's correct.** "Complete" means "current," not "finished." We are always learning, saving, and missing things — the honest condition of working on something too big to hold. The map's job isn't to end the not-knowing; it's to make it organized and re-openable.

## THE MAP ITSELF — lifecycle, workbench, views
- **Lifecycle:** one *live* SCOUT-MAP, additive within a session, consolidated to "full" when unwieldy. On consolidation the previous full isn't deleted — it graduates to REV-SCOUT-MAP.md, the map's own fossil record. Always one live map plus a growing REV behind it. Never overwrite; never lose history.
- **Workbench, not warehouse:** the project area holds what the scout works *from* (the method kit and spine), not what it works *on*. Merged fossils and drift-heavy files live at their URLs — keeping them in-project re-injects the drift you distilled out. Tactic: load only the cluster you're scouting this session → fetch-verify → clear → load the next. This scope-limits the scout so it can't wander.
- **Views from one dataset:** the open-marks index is one table, filterable by status (all 🛑 / all 💎-awaiting-a-piece / all stale). One map, many lenses, no duplicated docs.

## DEPTH, MARKERS, AND A DISCIPLINE
Depth (stamp which): skim (names + first/last) · structure (headers/decls) · pattern (repeated idioms) · cross-ref (links/deps).
Markers: 🔮 forecast · 🧪 unverified self-grade · ⏳ partial · ✅ confirmed · ⛔ killed · 🪦 drift · 💎 salvage · 🛑 content-flag · 🏴 charged-language · ⚙️⚔️🔗🧩🕳️⚠️
**Prose must not outrun markers:** if the marker says 🔮, the sentence says "looks like," not "is." (From a real v0.1 slip — the hedged markers were right while confident prose overstated.)

## WHAT SCOUTING IS NOT
Not editing · not a verdict · not complete (it always leaves named blanks).

---
*Coverage stamp for this consolidation: folded in the sufficiency rule + cache-not-source (into the spine), the map lifecycle + standing-truth, the six header-spec adoptions, the workbench tactic (new — wasn't in live v0.3), and fixed the map's version label. **Not changed:** the substance of any catch, status, or rule — only their arrangement and some wording. I did not re-fetch the MAP, LEDGER, or HANDOFF to check their headers still match; that's an open blank. Current, not finished.*

🧭0004

---

Does this read true to you — anything I folded that lost a nuance, or that you'd arrange differently? Once you're happy with it, the natural next steps from the handoff are the open-marks index and the live MASTER-INDEX-HEADER pass. And yes — I'll keep NEEDS-ATTENTION and TROLLEY-026 held, not resolved or polished, since that's the right handling for anything flagged as a real content concern and I haven't seen them live anyway.
