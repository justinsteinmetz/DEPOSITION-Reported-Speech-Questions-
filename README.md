# DEPOSITION ROOM

An interactive grammar tool for practising **reported questions** in English. Students are cast as witnesses in a deposition. An unseen interrogator asked them questions. Their job: report those questions accurately.

Designed for **classroom projection** (whole-class) or **individual devices** (pairs / independent). Single HTML file. No internet required once fonts have loaded.

---

## Learning Focus

- Reported (indirect) questions — wh- and yes/no types
- Tense backshift (present → past, past → past perfect, will → would, can → could)
- Statement word order in reported clauses (no inversion, no auxiliary)
- Use of *if* / *whether* for yes/no questions

**Target level:** B1 (approx. Grade 8 / Year 8)

---

## How It Works

### Setup

Students see a two-part task:

1. **The interrogator's direct question** — displayed in quotation marks
2. **A stem** — the beginning of the reported sentence they must complete

Example:

> *"Where do you live?"*
> They asked me where **___________**

Students type the completion — in this case: *I lived* — and submit.

### Feedback

- **Correct** → green confirmation + the full correct sentence. Press Submit or Enter to continue.
- **Wrong** → red diagnostic identifying the specific error type (inversion error, tense error, missing connector). The correct form is shown. Press Submit or Enter to continue.
- **Show answer** → reveals the correct form immediately. Counts against the suspicion meter at half-weight.

All advancement is **manual** — nothing auto-proceeds. Designed for classroom use where teacher and students need time to read and discuss.

### Suspicion Meter

Five bars in the top-right. Each wrong answer fills one bar. Each skipped question fills half a bar. At maximum suspicion (5), the document is stamped **UNRELIABLE** and the visual contrast of the page degrades.

This is atmospheric, not punitive — students are not locked out. The instability is the point.

### Phases

Questions are shuffled on each session. The phase label (Phase 1 / Phase 2 / Final Phase) changes at questions 4 and 7. This is cosmetic framing only — difficulty is distributed across the full set.

### Final Screen

After all 10 questions:

- **TESTIMONY ACCEPTED** — 80%+ accuracy
- **TESTIMONY PARTIAL** — 50–79%
- **TESTIMONY REJECTED** — below 50%

Score, accuracy rate, and suspicion level are all displayed.

---

## Question Set

10 questions covering:

| Type | Count | Examples |
|------|-------|---------|
| wh- questions | 6 | where, what time, why, how long, who |
| yes/no questions | 4 | present simple, present perfect, will, can |

Tense shifts covered: present simple, present continuous, past simple, present perfect, present perfect continuous, will → would, can → could.

Questions are shuffled on every session start and every reset.

---

## Classroom Use

### Whole Class (recommended first run)

- Project on screen
- Teacher controls input
- Students suggest answers aloud — teacher types the class consensus
- When wrong: read the diagnosis aloud, ask what went wrong before moving on
- Hint button available if discussion stalls

### Pairs / Individual Devices

- Each pair runs independently
- Debrief: compare suspicion levels, discuss which question type caused most errors
- Run a second session — questions shuffle, so it doesn't repeat identically

### Teacher Controls

| Action | How |
|--------|-----|
| Submit answer / advance | Enter key or Submit button |
| Show answer without guessing | "Show answer" button |
| Toggle grammar hint | "? hint" button |
| Start new session | "New Session" button on final screen |

---

## Grammar Reference Strip

A compact reference is always visible during the session:

- Tense shift summary
- Word order rule
- if / whether reminder

Students should try before consulting it, not use it as a crutch.

---

## Error Diagnosis

The system identifies three error types:

- **Inversion error** — auxiliary verb detected after wh-word (*where did I live*)
- **Tense error** — present tense form detected where past is required
- **Connector error** — yes/no question completion doesn't open with *I*, *if*, or *whether*

Generic fallback: *"Review tense and word order."*

---

## Technical

- Single `.html` file
- Fonts loaded from Google Fonts (Special Elite, IBM Plex Mono, IBM Plex Sans) — requires internet on first load; cached thereafter
- No frameworks, no dependencies, no server
- Works on Chrome, Firefox, Safari, Edge
- Mobile-compatible but optimised for laptop/projector

---

## Suggested Follow-Up

This tool sits naturally after **INDIRECT** (indirect questions / polite register), which covers the same embedded word-order structure from a different communicative angle.

Post-session activities:

- Written deposition: students write 5–6 sentences reporting what a partner asked them in a real interview
- Witness statement reconstruction: teacher reads direct questions aloud, students transcribe as reported speech
- Contradiction exercise: two students interview each other; a third reports — comparing what was actually said vs what was reported

---

## Known Limitations

- Answer matching is string-based. Unusual but valid phrasings may be marked wrong.
- The *Who was in the room with you?* question accepts any string containing the correct core form — intentionally flexible, occasionally permissive.
- Skipping a question adds to the total count, affecting the accuracy percentage.
