Based on full context, here's the refined framework and prompts:

***

## **REFINED ReadMe: Secondary Mathematics Pedagogical Framework**

### **PRIORITY 1: IMMEDIATE (Test Tomorrow – Monday, 9 Feb 2026)**

**Goal:** Prepare Grade 10 student for Algebraic Expressions assessment in one 3-hour session.

**Session Structure:**

- **Hour 1 (60 min):** Core concepts + laws review
    - Polynomial term anatomy (Sign, Coefficient, Variable, Power)
    - The 4 structural forms (DOTS, Perfect Square, Standard Trinomial, Complex Quadratic)
    - Reversibility demonstration (expansion ↔ factorisation with traceability)
- **Hour 2 (60 min):** Worked examples + parallel practice
    - Walk through worksheet questions together
    - Student attempts parallel versions (same structure, different numbers)
    - Diagnose blockage points: sign errors vs structural misunderstanding
- **Hour 3 (60 min):** Mini-test (30–45 min) + immediate feedback
    - Cover key assessable concepts from tomorrow's test scope
    - Mark together, using misconception log format

**Key Results (KR):**

- Student can identify expression structure before attempting manipulation
- Student demonstrates reversibility understanding (can trace expanded form back to factors)
- Student completes mini-test with confidence in success criteria hierarchy (common factor → structure recognition → execution)

***

### **PRIORITY 2: SHORT-TERM (Platform Setup – Next 2 Weeks)**

**Hosting Platform Recommendation:**
Use **GitHub Pages + Obsidian Publish** or **Notion** for lightweight, accessible setup:[^1][^2]


| Platform | Strengths | Best For |
| :-- | :-- | :-- |
| **GitHub Pages (with Jekyll)** | Free, version-controlled, Markdown-native, can embed GeoGebra/Desmos iframes | Structured syllabus delivery, worked example repository, lesson scripts |
| **Notion** | Student-friendly UX, inline images/PDFs, progress tracking databases, mobile-friendly | Student uploads (homework images), M\&E tracking, weekly test results |
| **NotebookLM** | Auto-generates study guides, flashcards, audio summaries from uploaded sources | CAPS curriculum grounding, theory reference library, parent/student study aids |
| **Replit** | Interactive coding (if you add Python/Jupyter for dynamic demos), instant sharing | Optional: interactive algebra visualisations, automated quiz generation |

**Recommended Stack:**

- **GitHub Pages**: Public-facing syllabus, module breakdowns, worked examples library
- **Notion (private workspace)**: Student progress tracking, image uploads, misconception log, weekly test archive
- **NotebookLM**: Curriculum + pedagogy research hub (CAPS docs, teaching PDFs, your refined scripts)

***

### **PRIORITY 3: LONG-TERM (Full Grade 10 Pedagogy – Term 1–4)**

**Scope:**

- Modular syllabus aligned to CAPS Term breakdown
- Evidence-based pedagogy grounded in:
    - Variation Theory (structure-constant vs surface-varied practice)[^3]
    - Worked examples + retrieval practice[^4][^5]
    - Traceability auditing (term-origin mapping)[^6][^3]
    - ZPD scaffolding (Pause \& Name protocol, K-method triggers)[^3]

**Module Sequence (Starting Point):**

1. **Term 1: Algebraic Expressions** (Expansion, Factorisation, Simplification)
2. **Term 2: Exponents \& Surds**
3. **Term 3: Equations \& Inequalities**
4. **Term 4: Graphs \& Functions**

**Repository Structure (GitHub Pages example):**

```
/syllabus
  /term1-algebraic-expressions
    - module-overview.md
    - lesson-01-term-anatomy.md
    - lesson-02-four-forms.md
    - worked-examples-bank.md
    - practice-items-tagged.md
/student-uploads
  - [linked to Notion for image/PDF storage]
/misconception-log
  - pattern-library.md
/assessment-blueprints
  - weekly-test-templates.md
```


***

## **IMAGE INGESTION PROMPTS (Two Versions)**

### **Version A: For Your "Explaining Scripts" (Tutor-Created Materials)**

```text
CONTEXT: Explaining Script Review
- Module: [e.g., Algebraic Expressions – Factorisation]
- Concept: [e.g., Difference of Two Squares traceability]
- Target: Grade 10, CAPS Term 1

ARTEFACT:
- Image: [your handwritten/typed explanation]

REQUEST:
1) Extract the core teaching idea and structural logic.
2) Identify pedagogical strengths (e.g., traceability shown, reversibility emphasized).
3) Suggest refinements:
   - Clearer scaffolding (if ZPD jumps are too large)
   - Backed theory (cite Variation Theory, worked example effect, etc.)
   - Visual enhancements (distribution matrix, color-coded term paths)
   - Language precision (avoid "FOIL-as-rule"; frame as "distribution pattern")
4) Provide an improved version with:
   - Principle → Application → Example structure
   - One "structure-varied" parallel example
   - Student self-check question
5) Tag: [Structure], [Common pitfall this addresses], [CAPS alignment]
```


***

### **Version B: For "Student Work Examples" (Diagnostic + Teaching)**

```text
CONTEXT: Student Work Assessment
- Grade/Term/Topic: Grade 10, Term 1, Algebraic Expressions
- Assessment context: [Homework / Test prep / Mock exam]
- Goal: [Diagnose + Teach / Mark + Feedback / Generate practice]

ARTEFACTS:
- Image 1: [Worksheet question(s)]
- Image 2: [Student's working]
- Image 3: [Your explanation attempt, if provided]

REQUEST:
1) **Extract:** Transcribe the question(s) and key student steps (preserve errors; don't fix yet).
2) **Diagnose:** Identify the earliest wrong step and classify:
   - Sign error (e.g., forgot to distribute negative)
   - Structural error (e.g., tried to factor non-factorable form)
   - Conceptual error (e.g., treated $x^2 - 4$ as $(x-4)^2$)
   - Calculation slip (correct method, arithmetic mistake)
3) **Teach (Principle → Application → Example):**
   - State the relevant law/structure principle
   - Show why the student's move violated it
   - Provide a minimal worked solution (exam-style clean)
   - Provide a traceability version (matrix/origin map for expansion)
4) **Practice generation:** Give 6 parallel items:
   - 2 easier (same structure, simpler numbers)
   - 2 same level (different surface features)
   - 2 harder (structure variation, e.g., binomial as unit)
   - Include answer key
5) **Misconception log entry:**
   | Error Pattern | Likely Cause | Micro-Intervention | Next Check Item |
   |---------------|--------------|---------------------|-----------------|
   | [e.g., $(x-3)^2 = x^2 - 9$] | Forgot middle term doubling | Show Perfect Square trace | Give $(2x+5)^2$ |
```


***

## **RECOMMENDED NEXT STEPS**

### **A. Hosting Setup (This Week)**

1. **Create GitHub repo:** `grade10-maths-pedagogy`
    - Initialize with README.md (paste refined version above)
    - Create folder structure: `/syllabus`, `/worked-examples`, `/assessment`
2. **Set up Notion workspace:**
    - Database 1: "Student Uploads" (image gallery + comment field)
    - Database 2: "Misconception Log" (pattern, cause, intervention, check-item columns)
    - Database 3: "Weekly Tests" (date, topic, score, areas for attention)
3. **Launch NotebookLM project:**
    - Upload CAPS Grade 10 Maths curriculum PDF[^7][^8]
    - Upload your refined scripts (Markdown versions)
    - Upload teaching research PDFs (MTR design thinking, worked examples research)[^9][^10]

### **B. Research Prompts for Perplexity**

Use these to build your evidence base:

```
1. "CAPS Grade 10 Term 1 Algebraic Expressions assessment standards observable mastery indicators"
2. "Variation Theory mathematics worked examples sequencing difficulty Grade 10 algebra"
3. "Retrieval practice interleaved worked examples factorisation misconceptions research"
4. "GeoGebra Desmos algebra structure visualization activities Grade 10"
5. "South Africa mathematics pedagogy frameworks Zone Proximal Development scaffolding"
```


### **C. Immediate Pre-Test Session Prep (Today)**

1. **Print/digitize:** The 4 structural forms reference sheet[^3]
2. **Prepare:** 10 parallel practice items (matching tomorrow's test scope)
3. **Create:** 30-min mini-test (CAPS-style wording, mixed question types)
4. **Set up:** Notion page for tomorrow's session notes + student upload field

***

**Final Note on Format Ingestion:**
For your Gemini thread, **upload images directly** with the prompt captions above. For archival/RAG later, convert your explaining scripts to **Markdown** (preserves LaTeX math + structure) and store in GitHub; use **NotebookLM** to auto-generate study materials from those Markdown files + CAPS PDFs.[^11][^1][^3]

Would you like me to draft the **3-hour session lesson plan** with timings and specific activities for tomorrow's prep?
<span style="display:none">[^12][^13]</span>

<div align="center">⁂</div>

[^1]: https://www.appgambit.com/blog/llms-love-structure-using-markdown-for-pdf-analysis

[^2]: https://worldlycode.github.io/nanobot-dev-docs/blog/parsing-docs/

[^3]: Draft1_-Maths_Pedagical_Framework-ReadMe.txt

[^4]: https://www.sciencedirect.com/science/article/pii/S0959475225001203

[^5]: https://ammaramerhbi.substack.com/p/when-worked-examples-meet-retrieval

[^6]: Gemini-Brainstorming-0-Start-Point-for-Maths_Pedagogy.md

[^7]: https://www.education.gov.za/LinkClick.aspx?fileticket=xB_6NSmf6m8%3D\&tabid=1853\&portalid=0\&mid=8657

[^8]: https://www.thutong.doe.gov.za/ResourceDownload.aspx?id=44785

[^9]: MTR-Design-thinking-6-3-19-accepted.pdf

[^10]: An-accurate-and-practical-method-for-assessing-science-and-engineering-problem-solving-expertise.pdf

[^11]: https://www.instill-ai.com/blog/the-best-way-to-parse-complex-pdfs-for-rag-hybrid-multimodal-parsing

[^12]: Master-Prompt-Ingestion-Gem-Maths_Pedagogy.md

[^13]: Gemini-Brainstorming-0-Start-Point-for-Maths_Pedagogy.md

