# Visual Evaluation Rubric (v1)

A working rubric for judging still images: illustrations, posters, product and editorial visuals, and AI-generated output. I wrote it as a self-initiated exercise, and I used it to score the six constructed samples in `critiques.md`.

**How to use it in one minute:** Read the brief. Look at the image for three seconds, then squint. Score the eight dimensions with whole numbers 1 to 5. Tag every note `[C]` (convergent) or `[D]` (divergent). Finish with one concrete fix per major problem.

---

## 1. The scale

Use the same scale for every dimension. Whole numbers only.

| Score | Meaning | Test |
|---|---|---|
| **5** | Resolved and intentional | I would not change anything without changing the brief. |
| **4** | Strong | One small, fixable issue. |
| **3** | Competent | Works, but is generic, or has one clear weakness. |
| **2** | Flawed | A viewer would notice a problem without being prompted. |
| **1** | Failing | The problem undermines the image's purpose. |

**N/A rule:** Mark a dimension N/A if the brief and the image make no claim in that area. For example, a lighthouse poster with no cultural content gets N/A for cultural relevance. An N/A is left out of the average.

**Overall score:** the mean of the scored dimensions, to one decimal. It is a summary only. Always report the full profile, because a 3.4 made of 5s and 1s is a different image from a 3.4 made of 3s and 4s.

**Verdict bands** (a guide, not a law):

| Mean | Verdict |
|---|---|
| 4.2 and above | Ship |
| 3.4 to 4.1 | Usable, with notes |
| 2.6 to 3.3 | Revise |
| Below 2.6 | Reject / regenerate |

**Gate:** if any `[C]` dimension scores 1, the verdict is "Revise" at best, whatever the mean says. A single broken fundamental should not be averaged away.

---

## 2. The eight dimensions

Anchors are given for 1, 3 and 5. Scores 2 and 4 sit between them. The **Type** column says how much of the judgment is shared craft (`C`) and how much is personal direction (`D`). Section 3 explains the tags.

### 2.1 Composition (Type: C)
*Where does the eye enter, travel and rest?*
Look at balance, grouping, negative space, edge tension, tangents, cropping and depth layering.

- **1:** Elements are scattered or cropped awkwardly. The eye has no path. Edges collide or touch (tangents).
- **3:** Balanced and legible, but default: centered, or spread evenly with no path.
- **5:** A clear entry, route and resting point. Negative space is deliberate. The crop helps.

### 2.2 Visual hierarchy (Type: C)
*What do I see first, second and third? Is that the right order?*
Tests: the 3-second glance, the squint test, and the grayscale test.

- **1:** Everything has equal weight, or the wrong thing wins.
- **3:** There is one clear primary, but the secondary competes with it or disappears.
- **5:** Three readable tiers. The subject wins through at least two cues (value, saturation, size, edge sharpness, position).

### 2.3 Color and value (Type: C for structure, D for palette choice)
*Does the value structure hold in grayscale? Is the palette controlled?*
Look at the number of hues, harmony, temperature, saturation, and the use of accents.

- **1:** Muddy or clashing without purpose. The value range has collapsed, so everything is a similar mid-gray.
- **3:** Pleasant but safe. Values or saturation are slightly off balance.
- **5:** A controlled palette. The grayscale version still works. An accent is used to direct the eye.

### 2.4 Cohesion and internal logic (Type: C)
*Does everything look like it belongs to one world?*
Check the light source, shadow direction, perspective, scale, level of detail, and rendering style. Stylized worlds can break physics, but they must break it consistently.

- **1:** Parts look as if they came from different images, or contradict each other.
- **3:** Mostly coherent, with one or two contradictions.
- **5:** One world. Its rules, even stylized ones, are obeyed everywhere.

### 2.5 Craft and artifacts (Type: C)
*Does it hold up at 100% zoom?*
Check edges, texture, banding, noise, text legibility, duplicated or stamped shapes, malformed anatomy, and unintended overlaps.

- **1:** Obvious glitches at normal size.
- **3:** Clean at normal size. Flaws appear when zoomed in.
- **5:** Holds up under close inspection. Details look chosen, not leftover.

### 2.6 Mood and intent fit (Type: mixed)
*Does the feeling match the brief?*
`[C]` when judging whether the mood matches the brief. `[D]` when judging which mood is better.

- **1:** The mood contradicts the brief.
- **3:** The mood is right but generic.
- **5:** The mood is felt before it is analyzed. Every choice serves it.

### 2.7 Originality (Type: D)
*Is there a point of view, within what the brief allows?*
Originality is not weirdness. Score distinctiveness with control.

- **1:** Default or stock look. It could be any image from the category.
- **3:** Familiar, with a personal touch.
- **5:** A recognizable point of view, and the craft to carry it.

### 2.8 Cultural relevance and sensitivity (Type: mixed)
*Are references accurate, specific and respectful?*
`[C]` for factual errors, stereotype shorthand, or misused symbols. `[D]` for preference between valid references.

- **1:** Inaccurate, stereotyped, or careless with meaningful symbols.
- **3:** Neutral or generic. Nothing wrong, nothing specific.
- **5:** Specific, informed, and respectful of its sources.

---

## 3. Convergent quality vs. divergent taste

Some judgments should come out the same for most trained reviewers. Others depend on direction and taste. If I mix them, I either bully a stylistic choice with fake objectivity or let a real error through as "just my taste". So I separate them and say which is which.

### 3.1 Definitions
- **Convergent `[C]`:** quality that rests on a mechanism most people share. Examples: attention (what the eye lands on), physics (light and shadow), legibility, and consistency. If two competent reviewers read the same brief, they should land within about one point.
- **Divergent `[D]`:** quality that depends on direction, not mechanism. Examples: flat vector vs. painterly, restrained vs. maximal, cool vs. warm mood, and what counts as original. Reasonable reviewers will differ, and neither is wrong.

### 3.2 Three questions to decide the tag
1. **Mechanism test:** Can I point to a mechanism (attention, physics, legibility) instead of saying "I prefer"? If yes, lean `[C]`.
2. **Reviewer test:** Would four of five trained reviewers with the same brief agree? If yes, `[C]`. If it would split, `[D]`.
3. **Fix test:** Does the fix depend on which direction the artist wants? If yes, `[D]`. If the fix is the same for any direction, `[C]`.

If I am unsure, I write `[C?]` and say why.

### 3.3 How to flag each

| Tag | How I write it | Example |
|---|---|---|
| `[C]` | State the problem and the mechanism. Give one fix. | "[C] The cabin's lit wall faces away from the sun. Light direction contradicts itself. Fix: swap the wall values." |
| `[D]` | Say what I notice, then phrase the fix conditionally on direction. | "[D] The soft ceramics look is very familiar. If the brief wants a distinct voice, add one unexpected material or scale." |
| `[C?]` | Give a best guess and the reason I'm unsure. | "[C?] The small dash may be a stray mark, or an intentional accent. It reads as stray." |

### 3.4 Scoring divergent dimensions fairly
- For `[D]` dimensions, score **fit to the brief and execution**, not match to my taste.
- I disclose my own lean so other reviewers can correct for it. Mine: I tend to prefer restrained palettes, strong value structure, and graphic, simplified shapes. A painterly or maximal image has to work a bit harder to convince me, so I check myself on those.
- Rule-breaking is fine if it is consistent and purposeful. A deliberately flat, shadowless image is not a lighting error. An image that implies a light source and then contradicts it is.

### 3.5 Using the split when building benchmarks
- Use `[C]` scores for pass/fail gates, regression checks and training signal. These are the shared fundamentals.
- Keep `[D]` as tags and distributions rather than one "correct" score. Preserve the spread of valid tastes instead of averaging it away.
- **Disagreement as signal:** if two reviewers differ by 2 or more points on a dimension, find out why. Either the anchor wording is ambiguous (fix the rubric), or it is a real taste split (re-tag it `[D]`).
- **Anchor sets:** keep two or three pinned example images per score level for each dimension, and re-score them periodically to check drift.
- **Homogenization risk:** optimizing only for the convergent signal tends to produce a polished, safe average. A benchmark should reward fundamentals and still leave room for distinct work.

---

## 4. Quick checks

Run these before scoring.

- **3-second glance:** What is the first thing I see? Is it meant to be first?
- **Squint:** Blur my eyes. Do the big shapes still read? Is there one clear winner?
- **Grayscale:** Desaturate. Does the value structure still separate subject from ground?
- **Light audit:** Mark the light source. Check highlights, shadows, reflections and glows against it.
- **Edge and tangent sweep:** Look at where objects touch each other or the frame edge.
- **100% zoom:** Check edges, texture, text and repeated shapes.

---

## 5. One-page scoring sheet

```
Image / ID:            Brief (one line):
Reviewer:              Taste lean (one line):

Composition      [ ]   note + tag
Hierarchy        [ ]   note + tag
Color & value    [ ]   note + tag
Cohesion         [ ]   note + tag
Craft            [ ]   note + tag
Mood fit         [ ]   note + tag
Originality      [ ]   note + tag
Cultural         [ ] / N/A

Mean (scored dims):    Verdict:    Gate triggered? (C dim = 1)

What works (1-3 lines):
What fails (1-3 lines):
Fix (one concrete, testable change per major problem):
Convergent vs. divergent note:
```
