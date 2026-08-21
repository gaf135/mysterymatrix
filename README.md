# Mystery Matrix

A single-file HTML tool for running the Mystery Matrix from **Mythic Magazine Volume 6 —
"Creating Mystery Adventures"** (Tana Pigeon, Word Mill Games).

Open `mystery-matrix.html` in any browser. No install, no server, no network.

## What it does

**The sheet.** The same layout as the printed Matrix: 20 Clue boxes around the outside
(numbered in 1d100 bands, 1-5 through 96-100), 10 Suspect boxes down the middle, Progress
Points for Clues and Suspects along the bottom. Type straight into any box.

**Links and Clue Points.** Click 🔗 on a box, then click the box to link it to; the line is
drawn for you. Linking the same pair again strengthens that Link, and ↑ Intensifies a Clue so
every Link to it is worth more. Each Suspect's Clue Point total is kept up to date in their box.

**The dice.** Buttons roll the Mystery Elements Table (1d10 + that column's Progress Points),
Discovery Check Exceptional Yes (two rolls, one Progress Point), the Mystery Special Table, the
Mystery Event Focus Table, the Mystery Descriptors tables, and plain Clue (1d100) / Suspect
(1d10) rolls on the Matrix.

Results come back resolved rather than as a table reference: the tool rolls the Clue and
Suspect a Link result needs, tells you when you hit an empty box and have to Choose Most
Logical, records the Progress Point for the trip, runs a Roll Twice as two nested results, and
applies PP-6, PP+3 and PP-3 for you. Every Link, removal and roll goes to the journal.

**The Clincher.** Roll it on the Elements Table and the tool links the new Clue to the Suspect
with the most Clue Points (flagging ties for you to choose). Or it announces the automatic
Clincher when a Suspect crosses the threshold — 6 Clue Points by default, adjustable, along with
starting Progress Points, to make easier or harder Mysteries.

**Your case.** Autosaves to the browser. Export/Import move a case as JSON; Print gives you a
clean sheet with the controls stripped out.

## Reference

The Mystery Elements, Special, Event Focus and both Descriptors tables are collapsed at the
bottom of the page, along with a short summary of how a Mythic Mystery runs.

The rules themselves belong to Tana Pigeon and Word Mill Games — this is a play aid for people
who own *Mythic Magazine Volume 6*, not a replacement for it.
