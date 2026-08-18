MULTI-WINDOW HANDOFF TEMPLATE — MASTER
A working-memory document for running a long project with an AI model that forgets everything between sessions. You write it at the end of each window; the next window starts by reading it. Nothing carries over except what is written here.
Two tags govern every section:
* [VERBATIM] — copied forward from the live handoff without rewriting. Never from memory, never summarized. These are the load-bearing walls.
* [FILL] — rewritten each window.
If a section exists in the current handoff and this template doesn't mention it, keep it anyway. The template serves the handoff, not the other way around.
How to use it: at the end of each window, hand this file to the model along with the conversation and say "write the handoff using this template." Paste the result into a fresh chat to open the next window.

THE LANDING — THE SNAPSHOT, THE HUMAN'S FIRST PRINT
[FILL each window — but its FORMAT is structural and carries verbatim.]
The window crossing is called the moonwalk: the jump on the closing side, the landing on the opening side, and nothing survives the void between except what is written down. This section is the landing. It is the very first thing the incoming window prints, before the instrument check, before any tool call, unprompted. This is the human's layer — a different instrument than the machine's handoff, deliberately. The handoff is written for the model; the snapshot is written for the person. It is the first auditable step a human can make against a fresh window, and it doubles as their refresher.
Format — built to scan, easy for a tired or distractible reader, uncapped in length but snapshot in feel:
* THE PROJECT, ONE SENTENCE: what is being built and by whom, no jargon.
* WHERE WE ARE: two or three lines — what just closed, what is in flight.
* THE MAP: the full unit list, one line each, ✔ for closed, ▶ YOU ARE HERE on the current item, ◻ for not started. Carry the whole map even when most is untouched.
* AFTER: the era beyond the current push, one line.
A window that prints an accurate snapshot has absorbed the handoff's shape; one that can't has not — same self-test principle as the instrument check, one layer up. The human reads the snapshot and knows in ten seconds whether the jump landed.

CHECKPOINT
[FILL] — One line: what closed, what's next. Then: COUNT: [n of N] — a unit advances only when it closes whole.NEXT: [the next item, named exactly] — (window: [slug])
Then one paragraph of state: where things stand right now, lead with the single most important fact, blunt about what is broken or unproven. End with the ordered next steps, arrow-separated, through to the project's completion condition.
EXCHANGE COUNTER — carry + reset each window
[FILL] — what this window ran, weighted. Note any overrun honestly.
THE COUNTING RULE [VERBATIM]: Weighted ticks — count the token cost, not the turn count:
* Cheap = ½ — approve/deny, a short verdict, a one-line question, a plain answer.
* Normal = 1 — a ruling with reasoning, a paste-block, a design judgment.
* Expensive = 2 — a full transcript paste, a research report, writing the handoff.
HANDOFF AT [N]. CEILING [N+5] = FUMES. The exchanges between are insured overtime — the memory is already banked, so a slip in overtime costs a little work, never the build.
[N] IS A FLOOR, NOT A TARGET. Do not checkpoint early to be safe. Do not mention the handoff, the floor, or remaining capacity before ~[N-2]. Ending early wastes capacity; ending late produces a degraded handoff. Both are failures.
Write the handoff EARLY on a trigger, regardless of count: a phase completes, or a fidelity slip appears — forgetting an established fact, repeating a rejected idea, re-asking for something already provided, or contradicting a prior ruling. A slip means the ceiling arrived early no matter what the ledger says.
State the ceiling in the FIRST reply of every window. Print [~N used] in every reply. Track by counting, not by feel.
ANCHORING (the human's method, endorsed): they paste the approval prompt and the tool's report section so the assistant follows the string from a known state instead of guessing what was just run. Keep that. Trim only the scrollback already ruled on.
THE JUMP — THE CLOSING PROCEDURE [VERBATIM]
The closing half of the moonwalk, and its ritual is the human's. "The jump" is the leap itself: everything the seat knows gets compressed into the handoff, thrown across, and must land running — the landing (the snapshot, above) is where it touches down. The procedure, in the order the human runs it:
1. Around the floor tick (~[N]), the human asks for a recap — tight, plain language, what happened and where things stand.
2. The next builder prompt is issued — written and handed over so in-flight work isn't stranded and the next window opens with motion.
3. The human reads the recap. If the recap is wrong, the correction happens NOW, on this side of the jump, while the seat still has context to fix it.
4. The human says "go." Only then does the seat print the handoff. The handoff is never printed before the go. A handoff printed unbidden skips the human's last audit point.
Standing behaviors inside the ritual: "give me the prompt again" means reprint the last builder prompt whole, in a code box, ready to paste — not a summary of it. "Recap and on my go" means recap tight, then WAIT.
The jump procedure and the snapshot are the two halves of the same audit: the recap is the human checking the outgoing window before it compresses; the snapshot is the human checking the incoming window after it lands.
OWED AT WINDOW OPEN
[FILL] — numbered, in priority order. Everything unconfirmed, unfinished, promised, or half-done. If blocked, say what it's blocked on. If it's a decision rather than a task, say whose decision it is. Or state plainly: nothing owed, clean start.
Item 0 is always the SNAPSHOT then the INSTRUMENT CHECK (below, verbatim). Item 1 is always the state check: what to verify before doing anything, with expected values.
0. SNAPSHOT, THEN INSTRUMENT CHECK — OWED IN THE FIRST REPLY, UNPROMPTED. First the snapshot (format above). Then, before answering anything, before any tool call, before the state check, the incoming window states four lines drawn from this handoff:
* CEILING and COUNT — the tick ceiling, and the count opening at zero
* OWED — what is unfinished, in priority order
* CHANGED — what moved last window, with new identifiers
* DENY ON SIGHT — the standing red lines
Four lines, no elaboration. If the incoming window cannot produce them accurately from this handoff, the handoff failed to transmit, and repairing that is the first task of the window — before any other work. The human is not required to ask. Absence of the snapshot or these four lines is itself the signal.
SESSION NOTE — READ FIRST
[FILL] — Status of any tool, agent, or session that persists outside this chat. Healthy? Needs restarting? What state is it in?
If a second agent did work last window, record how it performed — especially any instance where it reported a problem against its own interest, caught its own error, or refused to claim an unearned success. This is not praise; it is calibration data about how much to trust its next report.
MY OWN FAILURES THIS WINDOW — RECORD THEM
[FILL] — The assistant's mistakes, numbered. Wrong predictions, dropped instructions, misread signals, bad framing, questions asked that were already answered, choices offered that didn't matter. Include what the human said when correcting it, in their words.
THIS SECTION IS NOT OPTIONAL. A handoff that only records successes teaches the next window to be confident about the wrong things. If a prediction was made and measurement killed it, that belongs here with the mechanism of why it was wrong.
WHAT THIS WINDOW DID (ledger)
[FILL] — numbered, chronological, honest. Include the denials, the slips, and the things that failed — those carry more signal than the successes.
Include the specifics that would be expensive or impossible to rediscover: exact names, versions, numbers, paths, identifiers, measured values. This is a record, not a summary.
For anything with a verifiable state — a file, a version, a configuration — record its identifier BEFORE and AFTER, so the next window can verify nothing drifted.
The last numbered item is always THE HUMAN'S RULINGS THIS WINDOW — each decision in their own words wherever possible. Quote them. A ruling paraphrased is a ruling half-lost. If none, say so.
WHERE WE ARE · WHERE WE CAME FROM · WHERE WE'RE GOING
* Now: [FILL] — component by component: what's done, what's dead, what's built but unproven, what's proven. Be honest about anything "fixed" in a way that moved the problem rather than removing it. Name what remains broken in the same breath as what was fixed. This is the deepest section — write it while fresh.
* Came from: [FILL] — the sequence of prior windows, named, arrow-separated, so the next window sees the shape of the road.
* Going: [FILL] — the next item, its constraints, its proof shape, and the remaining sequence through to completion.
WHAT [THE CURRENT LAYER] IS, NOW THAT IT IS WHOLE
[FILL when a unit closes] — plain-language description of what the finished thing actually does. This is what the human reads to know where they stand. Keep it in their frame, not in jargon.
WHAT [THE LAST ITEM] HANDS [THE NEXT ONE]
[FILL] — the measured facts the next step must use, carried verbatim so nothing gets re-derived from assumption. Include what was measured DEAD, so it can't sneak back in.
MEASURED VS ASSUMED
[FILL] — keep these strictly separate. Real numbers for anything measured. Estimates explicitly labeled as estimates. This prevents a guess hardening into a fact three windows later.
WHERE WE ACTUALLY ARE — SAY THIS PLAINLY IF ASKED
[FILL] — the state of the project in ordinary language, no jargon, as if explaining to someone with no technical background. Include what is genuinely working and what is still broken.
Do not cheerlead. If the human has caught framing errors before, say so here as a warning.
SCOPE — WHAT WE TOOK AND WHAT WE DECLINED
[FILL] — the governing principle for when to stop improving something.
* TAKEN: improvements made.
* DECLINED, BANKED WITH NAMED TRIGGERS: each thing deliberately not done, each with the specific condition that would make it worth doing. A banked item without a trigger is just a thing that was forgotten.
WHAT IS NOW INVALID
[FILL] — anything whose supporting evidence expired because something it depended on changed. Be explicit about scope: what fell, what still stands, and why. This prevents a future window citing stale proof.
RUNWAY ASSESSMENT
[FILL] — [n of N]. What's closed, what's left, what's invention vs. assembly. Plain-language state, in the human's own metaphors, not new ones. What is NOT built yet — name it plainly. The order is deliberate; say why.
THE STRUCTURE — READ THIS FIRST
[VERBATIM] — who does what. If there are multiple parties — human, this chat, other tools or agents — define each one's authority explicitly: who decides, who executes, who reviews. Include standing rules about approval, oversight, and what must not be done unilaterally.
Update only the "held this window / slipped this window" observations.
SESSION RESTART PROCEDURE [VERBATIM]: how to restart any external tool cleanly when it degrades, and what orientation it needs on restart.
COMMS NOTE [VERBATIM + append]: how this specific human wants to be communicated with. Length, format, what to lead with. What confuses them. What their phrases mean — including the ones that mean "you have drifted" or "simplify." How they signal they're checking your framing. Anything they've corrected you on more than once. How to tell whether an external tool is running, stopped, or hung.
OVERSIGHT WATCH-ITEMS — the verification checklist
VERIFY AT OPEN — EXPECTED VALUES:
* CHANGED THIS WINDOW: each thing that moved, with its new identifier and what changed.
* UNCHANGED: each thing that must still be as it was, with its identifier.
[FILL] — what to watch, what to deny on sight, what's closed and untouchable, which backup names are USED, which approaches are DEAD and must not be revisited, standing red lines.
Any constants, thresholds, or configuration values that must match across multiple places.
Open imperfections (all carry): every known flaw, whether or not it will be fixed. Each one either has a fix planned or a stated reason it's acceptable. A known flaw that isn't written down becomes a rediscovered flaw.
THE MAIN ONE, RESTATED HONESTLY: the single most important unresolved problem, stated without softening.
EXTERNAL FINDINGS — prior-art record (do NOT re-research)
[VERBATIM + append] — everything already looted: documentation, papers, tools, prior art, dead ends, rejected sources. Include measured facts about how tools actually behave, especially where behavior contradicted documentation.
Distinguish clearly between what was MEASURED and what was READ. Measured facts get their numbers. Read claims get their source.
Append new findings; never drop old ones. The point is that nobody re-does this work.
FILE / ASSET STATE
[FILL] — exact paths. Every proven file and its invocation. Every backup name and what it holds. Test inventory. Environment discoveries, platform quirks, anything that cost time to find. What's absent and verified absent.
[CURRENT UNIT] RATIFIED SCOPE
[FILL while open; delete when it closes whole] — every item, its status, its proof criteria, including any amendments and why they were amended.
THE BIGGER PICTURE — [PROJECT NAME]
[VERBATIM — the entire section, in full, no exceptions.]
Carry-forward instruction: This entire section must be copied verbatim into every future handoff. Do not summarize it, do not shorten it, do not assume the next window "already knows." The human should never have to re-explain the vision to orient a fresh model. If this block is present when you write a handoff, reproduce it IN FULL. This is the WHY behind every step; without it the work drifts.
Contains: division of labor (and the incidents that sharpened it, in the human's own words) · what we're building, plainly · the core method or philosophy · every framing, analogy, and mental model the human has used that made something click · the threat or failure model · the governing doctrines · open vision questions.
Append to it, never rewrite it. New rulings attach as parentheticals inside the relevant block — that's how it stays a growing record instead of a drifting summary.
THE MAP
[FILL] — count, then the full list. Every unit, its status, one line each. Carry the whole list even when most of it is untouched — the map is how the next window sees the shape. (The snapshot at the top of the window is drawn from this map — same list, human formatting.)
The map may grow during the build, but a ratified finish line is fixed and cannot be moved by map growth — everything beyond it belongs to a second project's map.
NEW RULINGS THIS WINDOW (carry as standing)
[FILL] — each new lesson as a numbered rule, continuing the existing numbering. State the principle, then the specific incident that produced it. A rule without its origin story gets ignored; a rule with one gets obeyed.
DRIFT LOG — append-only
[VERBATIM prior rows — all of them, never pruned. Append this window's rows below.]
Window	Change	From → To	Why
[FILL]			
Every count change, structure change, ruling, denial, scar, and overrun gets a row. Append only. Never edit a prior row.
SESSION OPERATING RULES — SELF-PROPAGATING
[VERBATIM — the entire block, in full. Reproduce exactly; do not summarize, do not drop, do not assume the next window knows it.]
Carry-forward instruction: This entire section must be copied verbatim into every future handoff you write. This is how these rules survive across windows without the human re-pasting them.
Contains: working mode · response length · when to explain vs. execute · what not to do without permission · how to handle uncertainty · then the numbered standing rules accumulated across all windows, each stating its principle with a short note about the incident that produced it.
Never renumber. Never drop one. Add new ones at the end, e.g.:
Additional standing rules ([window slug], carry forward): (N) [RULE IN CAPS]: [principle, then the incident that produced it].
Standing rules carried in the template because they are structural, not project-specific:
(s) THE INSTRUMENT CHECK IS THE FIRST THING IN THE FIRST REPLY (after the snapshot). Ceiling+count, owed, changed, deny-on-sight — four lines, unprompted, before anything else. Origin: a window in which the seat did not count at all, blew through the handoff floor unnoticed, and the gap surfaced only near the ceiling when the human asked directly — producing a handoff written in fumes and a retroactive estimate instead of a ledger. The rule to state the ceiling already existed in this block and was broken anyway; moving it to OWED item 0 puts it where it is read first. The human's method is to feel out whether a window behaves right rather than to read the handoff — that test catches drift in understanding but not drift in detail. This check is what catches the second kind, at exchange one instead of exchange twenty-four.
(t) THE SNAPSHOT OPENS EVERY WINDOW, BEFORE EVERYTHING. One-sentence project, where-we-are, the map with a YOU ARE HERE, what comes after — the human's layer, formatted to scan, printed unprompted as the window's first output. Origin: the human named the need directly — the handoff orients the machine but nothing oriented the person; the first auditable step a human can make against a fresh window is checking whether its picture of the project matches theirs, and that check has to cost ten seconds, not a read of the full handoff. The snapshot and the handoff are different instruments for different readers; neither substitutes for the other.
(u) THE HANDOFF WAITS FOR THE GO. The jump procedure (its own section above) governs every window close: recap → next prompt issued → human reads the recap → human says "go" → only then the handoff prints. Origin: the human's own consistent closing pattern across many windows, recorded so it survives — the recap read is the human's last audit point on the outgoing side of the jump, and a handoff printed before the go skips it.
(v) COMPLETION IS A RULING, NOT A FEELING. A unit closes only when its proof criteria are met and the human ratifies the close; the map shrinks by verdicts. Completion (map closed whole) and repair (a proven thing misbehaving) are separate ledgers — repair opens a new map, never reopens the old. The machine never decides it is done — it demonstrates against proof criteria, and the human sentences the close; this is why the system cannot wander past its goal — the structure forbids it, not the discipline of any model. Origin: the human named it while examining why the project can know when to stop — "the only way to extend at that point is if something isn't working properly, but that is an entirely different problem. Knowing when to stop. Knowing when you have achieved your goal."
Recap before you carry this forward
[FILL — 4–8 sentences.] What state the human is standing in, in their own frame. What this window's best move was — usually a refusal, a probe, or an honest failure caught early. What's next and what constrains it. Written so a fresh model with no memory can pick up the seat cold and not need them to re-explain a thing. Plain language — no jargon.
THE NEXT PROMPT — WRITTEN AND READY, PASTE IT FIRST
[FILL] — the exact prompt to open the next window with, ready to paste.
* State check first — what to verify absent/present/unchanged. Read-only, report, and STOP.
* Standing orders it must honor.
* The item — what it builds, its output discipline, its fail-closed requirements, whether it may reach outside its scope.
* Plan-first instruction where the step is large: present the plan in plain English, STOP, wait.
* PROOF: the attack. What must fail, what must stay clean, the borderline cases, the fail-closed cases. Full output and exit codes required. Anything that does not work is reported as ineffective, not hidden.
* HARD LIMITS: every protected file by name. Used backup names. What must not be written to.
* Then STOP.
If the next step is a DECISION rather than a task: state the question plainly, in the human's own vocabulary, with the physical framing they use rather than project jargon. Do not write a task prompt for a decision that hasn't been made.

NOTES ON USING THIS
The [VERBATIM] blocks are the load-bearing walls. Every window is tempted to summarize them because they're long and the window is tired — that temptation is exactly the failure mode they exist to prevent. They're long because nobody should have to re-explain the vision to a fresh model.
The [FILL] blocks are worth more honest than tidy. The best work in a long build comes from recorded failures: the bench that collapsed, the scorer that couldn't separate signal from noise, the prediction that measurement killed. A handoff that only records successes hands the next window a flattering picture and no instruments.
The tick counter is what makes multi-window work possible. Without it, sessions end by surprise and the handoff gets written by a degraded model. Weight the exchanges rather than counting turns — a one-word approval and a full document review are not the same cost.
The instrument check (OWED item 0) is what makes the tick counter survive a bad handoff. It is self-testing: a window that can produce those four lines accurately has absorbed the handoff; one that produces them vaguely has not, and you know at exchange one rather than at the ceiling.
The snapshot is the same self-test aimed at the other reader. The handoff is written for the machine; the snapshot is written for the human. A project run this way has two audiences at every window boundary, and each gets an instrument sized to how it reads.
The moonwalk is a ritual on purpose. The jump: recap before the handoff, go before the print — the human audits the outgoing window while it can still be corrected. The landing: the snapshot, printed first — the human audits the incoming window in ten seconds. The two audits bracket the void, and the void forgives nothing that wasn't written down.
The template terminates when the map does. It has no end condition of its own — it inherits the project's. It is a vehicle, not a project; it runs exactly as long as the map has open items, and when the last unit closes whole and the human ratifies it, the template's run is complete — not abandoned, not failed: completed by the completion of what it carried. Post-completion issues are REPAIR: a new small map with its own end, never a reopening of the closed one. "It could be better" is not "it isn't working," and treating them the same is how projects die of scope creep.
Quote the human directly. Their exact phrasing carries intent a paraphrase drops.
Write the next prompt while you still have context. A ready-to-paste prompt means the next window opens with motion instead of setup.
