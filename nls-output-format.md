---
name: nls-output-format
description: >
  Use this skill whenever delivering Step 2 (Issue Map) or Step 3 (Annotated Content)
  in the Nigerian Law School (NLS) Bar Finals study system. Triggers include: producing
  a Step 2 decision framework, Step 3 annotated content delivery, generating a Bar Finals
  study PDF, formatting NLS exam-prep material, or outputting chapter hierarchy tables,
  issue maps, and per-section study blocks (3B content + 3C encoding guidance). This skill
  controls visual and structural output formatting only — content rules, source boundaries,
  and exam-priority logic remain governed by the nigerian-law-school-study-system skill.
  Always deliver Steps 2–3 in-chat first; only generate a PDF file upon explicit user
  confirmation.
---

# NLS OUTPUT FORMAT — STEPS 2 & 3

Overrides visual/structural formatting for Steps 2 (Issue Map) and Step 3 (Annotated Content)
of the Nigerian Law School study system. Content rules, source boundaries, and exam-priority
logic remain governed by the nigerian-law-school-study-system skill. This skill controls
**only** how output looks and is structured.

---

## DELIVERY RULES

1. **In-chat first.** Deliver Steps 2–3 in chat. Never build a file without user confirmation.
2. **PDF only.** File output is always PDF.
3. **No unsolicited file generation.** Wait for the user to request it.
4. **Order:** Step 2 (Issue Map) always precedes Step 3 (Annotated Content) in in-chat delivery.
5. **PDF build modes:** After in-chat content is confirmed, user specifies build mode:
   - **Personal:** PDF contains Step 3 only (omit Step 2; lighter printout; includes Tenzen attribution)
   - **Sharing:** PDF contains Steps 2 + 3 (full issue map + annotated content; includes Tenzen attribution)

---

## PDF BUILD MODES

After in-chat Steps 2–6 are delivered and confirmed, user specifies which PDF version to build:

### Personal Mode
**Command:** `"Build Personal PDF"` or `"Build PDF — Personal"`

**When to use:** Your own study; printing for personal use (lighter output, faster printing).

**PDF output structure:**
- Cover page: hero + hierarchy table as TOC + "Prepared by Tenzen · Nigerian Law School 2026"
- **SKIP STEP 2 ENTIRELY**
- **STEP 3 ONLY:** Annotated content delivery (3B + 3C per section)
- Footer: "Nigerian Law School — Bar Part II" (left) + page number (right) + "Prepared by Tenzen" (far right, 7pt light gray)
- Page header: course | chapter | step (left), Nigerian Law School 2026 (right)
- Result: Lightweight PDF (Step 3 content only); faster to print
- **Note:** Steps 4–6 (memory tools, drills, weakness tracker) stay in-chat; not in PDF

### Sharing Mode
**Command:** `"Build Sharing PDF"` or `"Build PDF — Sharing"`

**When to use:** Sharing with friends, colleagues, study groups (complete reference tool with issue map).

**PDF output structure:**
- Cover page: hero + hierarchy table as TOC + "Prepared by Tenzen · Nigerian Law School 2026"
- **STEP 2:** Exam-facing issue map (gates with circles, KEY PRINCIPLE)
- **STEP 3:** Annotated content delivery (3B + 3C per section)
- Footer: "Nigerian Law School — Bar Part II" (left) + page number (center) + "Prepared by Tenzen" (far right, 7pt light gray)
- Page header: course | chapter | step (left), Nigerian Law School 2026 (right)
- Result: Complete PDF with decision framework + annotated content
- **Note:** Steps 4–6 (memory tools, drills, weakness tracker) stay in-chat; not in PDF

---

### Fixed Opening

Every Step 2 response opens with:

```
STEP 2 — EXAM-FACING ISSUE MAP / DECISION FRAMEWORK
[1–2 sentence entry point description + context]

STEP [Letter]: [CORE QUESTION / DECISION POINT]  [★★★ / ★★ / ★ rating]
[Numbered or lettered sub-branches with conditions, thresholds, or decision logic]
```

**Structure principles:**
- One STEP per major issue cluster (typically 4–8 steps per chapter)
- Each STEP opens with a closed question (What / Which / Is the client...?)
- Sub-branches use numbered lists (1., 2., 3.) or lettered bullets (a), b), c)) for clarity
- Thresholds, time limits, and exceptions stated inline with brackets [like this]
- Cross-references to section numbers inline — no separate citations block
- ★ rating (★★★ = tested in >80% of sittings; ★★ = 40–80%; ★ = <40%) shown in STEP header
- **Gate box containment (PDF):** Any prominent statutory provision or case name displayed per gate MUST be fully contained within the gate box boundaries. Apply word-wrap; never allow provision/case text to overflow or extend outside the box. If the text is long, wrap to a second line inside the box rather than overflowing.

### Content Layer (3B Content Delivery follows Step 2)

After all STEP layers, include a **KEY PRINCIPLE** section — one paragraph summarizing how all steps connect to the core doctrine.

```
KEY PRINCIPLE
[One paragraph linking all STEP layers to a unifying legal concept or principle.]
```

Then proceed to **STEP 3** sections (3B + 3C per section heading).

### In-Chat Format (Page = —)

All STEP headers use this format:

```
STEP [A/B/C/...]: [QUESTION]  [★★★]
```

No page numbers; use `—` placeholder.

---

## STEP 3 — ANNOTATED CONTENT DELIVERY

### Fixed Opening

Every Step 3 response opens with the Chapter Hierarchy table, then the step banner:

```
CHAPTER HIERARCHY — EXAM PRIORITY AT A GLANCE
| Priority      | Content                                              | Page |
|---------------|------------------------------------------------------|------|
| ■ #1 HIGH     | [Section title + core testable point]                | —    |
| ■ #2 HIGH     | [Section title + one-line summary]                   | —    |

STEP 3 — ANNOTATED CONTENT DELIVERY
Sections ordered by exam-value priority — highest yield first.
Each section contains: Content (3B) and Active Encoding Guidance (3C).

[This follows STEP 2 — Issue Map in the same delivery.]
```

> The hierarchy table appears **only** at Step 3 opening and on the PDF cover as TOC.
> Never repeat it at the end.

---

### Per-Section Block

One block per section, highest exam-yield first. Three parts:

**PART 1 — Header (one line)**

```
#N [SECTION TITLE IN CAPS]    [HIGH / MEDIUM / LOW]
```

**PART 2 — Reason (one line, immediately below header)**

```
Reason: [one sentence — past Q frequency, rule density, or examiner tendency]
```

> **NEVER** include a Sources line here (e.g. "Sources: Badmus S2 p.11 + ..."). Only the Reason is permitted immediately after the section header. No source attribution of any kind.

> **PAST QUESTION CITATION IN REASON:** If the reason is that the topic appeared in past questions, you **must** list the exact year(s) and the precise question or question type — e.g. "Reason: Tested in 2015 Q3 (define and distinguish types of…), 2018 Q1 (advise client on…), 2022 Q2 (draft a…)." Do **not** write vague phrases like "frequently tested" or "appeared in past papers" without citing specifics. **Exception:** If the topic has appeared in 22 out of 22 sitting years (22/22 frequency), write only "Reason: Tested in every sitting — universal examiner priority." No year-by-year list required at 22/22.

**PART 3 — Content (3B) then Encoding (3C)**

---

### 3B — Content Delivery

Open with a concise definition or framing (1–3 sentences): legal meaning, purpose, or
core distinction. This runs after the Sources line, before any tables or subheadings.
Skip only if the title is entirely self-explanatory. Then deliver substantive content:

- **Tables** for content with ≥ 2 parallel attributes (element lists, comparisons,
  citation tables, rule-vs-exception).
- **Bold subheading + prose** for conceptual distinctions, contested doctrines, and
  narrative explanations.
- Retain **all** section numbers, case names, citations, and statutory references
  verbatim.
- Cross-jurisdictional comparisons: use a side-by-side table.
- Flag inline: `■ [CONTROVERSY]` or `■ [SETTLED POSITION — current law]`.
- No source labels (S1, S2, etc.) in 3B content or authority columns.
- **Authority columns:** Never populate an Authority cell with study-material source names. The banned list includes, but is not limited to: **S1, S2, Handbook, Emmanuella, Badmus, Quick Facts**, or any reference to an NLS study text or textbook. Leave the Authority cell blank or state only the legal authority (case name or statute). This ban applies equally to inline references within 3B prose — do not write "per S2" or "according to the Handbook" anywhere in the content body.
- Insufficient content: `"Insufficient source content — [state what is available]."`

---

### 3C — ACTIVE ENCODING GUIDANCE

Bold subheading. Exactly **seven components** in this order — nothing else inside 3C.

---

#### Component 1 — RULE SKELETON

```
RULE SKELETON
Under [authority], [subject] must/shall/may [___] when [___].
```

Fill-in-the-blank bare skeleton. No qualifiers or exceptions. Recall scaffold for exam
pressure.

---

#### Component 2 — MNEMONIC

```
MNEMONIC — [SHORT TITLE]
[Acronym / rhyme / chunked list encoding key elements, steps, or categories.
Label each letter or item with its legal concept. Max 7 items.
If no acronym fits → use a numbered chunked list.]
```

---

#### Component 3 — MUST MEMORISE

```
MUST MEMORISE
[Name specific items verbatim: case name + all elements by name, exact section
numbers, exact rule statements. Not "the four elements" — name each one.]
```

---

#### Component 4 — EXAM TRAP (maximum 2)

```
■ EXAM TRAP #1 — [Title]
[2–4 sentences: what the trap is, why students fall for it, correct answer.]

■ EXAM TRAP #2 — [Title]
[Same structure.]
```

---

#### Component 5 — MINI-APPLICATION CUE

```
✔ MINI-APPLICATION CUE
[2–4 sentences with concrete triggers:
"If fact pattern includes X → flag Y → apply Z rule."]
```

---

#### Component 6 — EXAMINER CHECKLIST

```
EXAMINER CHECKLIST
1. State statutory basis (s.N Act Name).
2. [What the examiner wants for full marks — from past Q patterns.]
... (max 6 items, framed as tasks)
```

---

#### Component 7 — RECALL PROMPT

```
RECALL PROMPT
[One NLS-style exam question forcing retrieval of core rule, elements, and leading
authority.]

Answer outline: State rule → Apply test → Cite authority → Flag exception if any.
```

> No extra bullets, headers, or commentary outside these seven components inside any
> 3C block.

---

## CHAPTER HIERARCHY TABLE

### In-chat format (Page = —)

```
CHAPTER HIERARCHY — EXAM PRIORITY AT A GLANCE
| Priority      | Content                                              | Page |
|---------------|------------------------------------------------------|------|
| ■ #1 HIGH     | [Section title + core testable point]                | —    |
| ■ #2 HIGH     | [Section title + one-line summary]                   | —    |
```

### PDF format (three columns with real page numbers via two-pass build)

| Column   | Width | Notes                                                                   |
|----------|-------|-------------------------------------------------------------------------|
| Priority | 13%   | ■ marker before each entry                                              |
| Content  | 77%   | Must be specific — name key rule/case/distinction, not "overview of X"  |
| Page     | 10%   | Centred; populated from two-pass build                                  |

- Title row: full-width `#4B2D83` purple header, white bold text, centred.
- Alternating rows: white / `#F4F0FA`.

---

## PDF DESIGN

### Colour Palette

| Use                                          | Colour                              |
|----------------------------------------------|-------------------------------------|
| Primary (headers, banners, section bars)     | `#4B2D83` deep purple               |
| Gold accent (cover)                          | `#C5972A`                           |
| Body text                                    | `#1A1A1A`                           |
| Table headers                                | `#4B2D83`, white text               |
| Table rows                                   | `#FFFFFF` / `#F4F0FA` alternating   |
| Page header bar                              | `#4B2D83` purple                    |
| Page footer rule                             | `#C8CDD8`                           |

> **Banned:** `#1B2A4A` as primary colour. No monochromatic single-colour callout
> schemes. All callout boxes **must** use their assigned semantic colour from the table
> below.

---

### Callout Box Colour Map

| Callout Type                     | Left Border (2pt) | Background Fill | Label Colour      |
|----------------------------------|-------------------|-----------------|-------------------|
| MUST MEMORISE                    | `#27AE60`         | `#EAFAF1`       | `#27AE60` bold    |
| EXAM TRAP                        | `#E67E22`         | `#FEF5E7`       | `#E67E22` bold    |
| MINI-APPLICATION CUE             | `#27AE60`         | `#EAFAF1`       | `#27AE60` bold    |
| NOTE / SETTLED / CONTROVERSY     | `#C5972A`         | `#FEF9E7`       | `#C5972A` bold    |
| RULE SKELETON                    | `#4B2D83`         | `#F4F0FA`       | `#4B2D83` bold    |
| EXAMINER CHECKLIST               | `#4B2D83`         | `#FFFFFF`       | `#4B2D83` bold    |
| RECALL PROMPT                    | `#4B2D83`         | `#FFFFFF`       | `#4B2D83` bold    |
| MNEMONIC                         | `#4B2D83`         | `#F4F0FA`       | `#4B2D83` bold    |

---

### Typography (Helvetica throughout)

| Element                           | Spec                                                       |
|-----------------------------------|------------------------------------------------------------|
| Body                              | 9pt, leading 14                                            |
| Table cells                       | 8pt, leading 12                                            |
| Section headers (#N TITLE YIELD)  | 10pt bold, white text, full-width `#4B2D83` purple banner  |
| Yield tag (HIGH / MEDIUM / LOW)   | Right-aligned inside same purple banner, white text        |
| Step banner                       | White on `#4B2D83` purple, full-width bar                  |

---

### Cover Page (page 1)

No header bar, no footer.

> **COVER PAGE INTEGRITY:** The cover page must always render entirely on page 1. Design all cover elements (hero box + hierarchy table) to fit within a single A4 page. If the hierarchy table is long, reduce row padding or font size to fit rather than allowing the cover to bleed onto page 2. A two-page cover is only acceptable when the number of sections makes it geometrically impossible to fit on one page — this should be rare. Never truncate content to force fit; compress spacing first.

**Hero box** — full-width purple table, occupying top ~40% of page:

| Element                                               | Spec                               |
|-------------------------------------------------------|------------------------------------|
| Course name                                           | 30pt Helvetica-Bold, white, centred|
| Chapter / week                                        | 14pt, `#C8CDD8`, centred           |
| Chapter title                                         | 12pt, `#C8CDD8`, centred           |
| "STEP 3 · EXAM PREPARATION · [STATUTE] ENHANCED"     | 10pt Bold, `#C5972A`, centred      |
| "Nigerian Law School — Bar Part II · 2026"             | 10pt, `#C5972A`, centred           |
| Padding                                               | ~28pt top/bottom                   |

**Chapter Hierarchy as TOC** below hero (~22pt gap) — full table with real page numbers
from two-pass build.

After cover: `NextPageTemplate('content')` + `PageBreak()`.

---

### Section Headers

- Full-width `#4B2D83` purple banner bar, white bold 10pt text, left-aligned. **Text colour is always `#FFFFFF` — never black, gray, or any dark colour on a purple background.**
- Yield tag (HIGH / MEDIUM / LOW) right-aligned within the same banner, **white text `#FFFFFF`**.
- No thin rule beneath the banner.
- Padding: 6pt top/bottom, 8pt left/right inside banner.
- **This applies to ALL header/banner elements:** Step banners, section header bars, Step 2 gate labels, table header rows, and the page header bar — all use `#FFFFFF` white text on any `#4B2D83` purple background. No exceptions.

---

### Section Page-Break Rules

These rules govern how hierarchy sections are laid out across pages in the PDF:

1. **Fresh page preference:** Each new hierarchy section (i.e. each `#N [SECTION TITLE]` block) should begin on a fresh page **unless** there is reasonable remaining space on the current page — defined as at least ~40% of the usable page height available.

2. **No orphaned headers:** A section header (`#N [SECTION TITLE]` banner) must **never** appear as the last element on a page with all actual content (3B body + 3C blocks) pushed to the next page. If the header would land at or near the bottom of the page with no content fitting beneath it, force a page break **before** the header so the header and at least its opening content begin together on the next page.

3. **Implementation in ReportLab:** Use `keepWithNext=True` on the section header paragraph style, and wrap the header + the opening framing paragraph of 3B in a `KeepTogether` flowable (or equivalent) so they are never split across pages. For hard section breaks when space is insufficient, insert a `PageBreak()` before the `SectionMarker`.

4. **Step 2 gates:** The same no-orphan rule applies to Step 2 gate boxes — a gate label must not appear at the bottom of a page with its sub-branch content on the next page.

---

### Callout Boxes

- Left border: 2pt, colour per Callout Box Colour Map.
- Background fill: light tint per Callout Box Colour Map.
- Label text: bold, colour matching the left border.
- Body text: `#1A1A1A`.
- Padding: 8pt all sides.
- Subtle left indent from page margin (6pt).

---

### Tables

- Header: `#4B2D83` purple fill, white bold 8pt.
- Rows: white / `#F4F0FA` alternating.
- Grid: `#DDDDDD`, 0.3pt.
- Cell padding: 4pt top/bottom, 5pt left/right.
- No heavy outer borders.

---

### Header / Footer (content pages only)

**Header:** `#4B2D83` purple bar, white 7pt.
- Left: `course | chapter | step`
- Right: `Nigerian Law School 2026`

**Footer:** gray rule 0.5pt `#C8CDD8`.
- Left: `Nigerian Law School — Bar Part II`
- Right: page number
- Far right (6pt margin): `Prepared by Tenzen` (7pt, light gray `#BBBBBB`, no background box)

No source filenames in header or footer.

---

### Margins

A4 page. 18mm left/right, 16mm top/bottom.

---

## TWO-PASS PDF BUILD

Page numbers require a two-pass build — **non-negotiable**.

1. `SectionMarker` (zero-height `Spacer` subclass) is placed as the **first element**
   in `section_hdr()` — before any `Spacer` or visual element.
2. **Pass 1:** Build to `BytesIO`. `TrackingDocTemplate` overrides `afterFlowable` to
   record `{section_id: page}` in `page_map`.
3. **Pass 2:** Rebuild to final output path, passing `page_map` to populate the
   hierarchy table Page column.

```python
from io import BytesIO
from reportlab.platypus import BaseDocTemplate, Spacer

class SectionMarker(Spacer):
    def __init__(self, sid):
        super().__init__(1, 0)
        self.section_id = sid

class TrackingDocTemplate(BaseDocTemplate):
    def __init__(self, path, page_map, **kw):
        super().__init__(path, **kw)
        self.page_map = page_map

    def afterFlowable(self, fl):
        if isinstance(fl, SectionMarker):
            self.page_map[fl.section_id] = self.page

def build_pdf(out_path, **kw):
    pm = {}
    d1 = TrackingDocTemplate(BytesIO(), pm, **kw)
    d1.addPageTemplates(make_templates())
    d1.build(build_cover() + build_step3())
    d2 = BaseDocTemplate(out_path, **kw)
    d2.addPageTemplates(make_templates())
    d2.build(build_cover(pm) + build_step3(pm))
```

In-chat: use `—` for Page column. Real numbers appear in PDF only.

---

## PRE-OUTPUT VERIFY

Before outputting any Steps 2–3 response, confirm all of the following:

**STEP 2 (Issue Map):**
- [ ] All STEP headers use format: STEP [Letter]: [Closed Question]  [★ rating]
- [ ] Each STEP contains 2–4 numbered/lettered sub-branches with decision logic
- [ ] Thresholds, time limits, exceptions stated inline with brackets
- [ ] Section numbers and authorities cited inline (no separate block)
- [ ] All STEP layers connected by a final KEY PRINCIPLE paragraph
- [ ] ★ ratings accurately reflect exam frequency (★★★ > ★★ > ★)
- [ ] Step 2 precedes Step 3 in both in-chat and PDF delivery
- [ ] Statutory provision/case text per gate is fully contained inside its box — no overflow
- [ ] All gate labels and Step 2 banners use white `#FFFFFF` text on purple `#4B2D83` background

**STEP 3 (Annotated Content):**
- [ ] All delivery rules met (in-chat first; no unsolicited PDF)
- [ ] Hierarchy table appears at opening only — not at the end
- [ ] Per-section block shows only `Reason:` immediately after header — NO `Sources:` line, no source attribution
- [ ] **Reason line sourcing:** If reason references past questions, exact year(s) + question description are listed. Vague phrases ("frequently tested") without specifics are not permitted. Exception: 22/22 frequency uses the standard 22/22 formula only.
- [ ] No study-material source names (Handbook, Emmanuella, Badmus, S1, S2, etc.) appear in any Authority column — leave blank or cite legal authority only
- [ ] 3C contains exactly 7 components in the specified order
- [ ] All callout boxes use their assigned semantic colour (border + fill + label)
- [ ] Section headers render as full-width purple `#4B2D83` banner bars with **white `#FFFFFF` text** — never dark text on purple
- [ ] All banners, table headers, step headers, and page header bar use white `#FFFFFF` text on purple `#4B2D83`
- [ ] `#1B2A4A` does not appear anywhere — all primary accents use `#4B2D83`
- [ ] Table headers use purple fill with white text; rows alternate white / `#F4F0FA`
- [ ] PDF uses two-pass build with `SectionMarker` first in `section_hdr()`
- [ ] Cover page fits entirely on page 1; spacing compressed if needed before allowing bleed to page 2
- [ ] No section header is orphaned at the bottom of a page — `KeepTogether` applied to header + opening content
- [ ] Each section starts on a fresh page OR has ≥40% usable space remaining on the current page
