# GOAT Academic Writing Skills (`goat-academic-writing-skills`)

A universal, top-tier academic paper writing, polishing, and aesthetic LaTeX formatting skill suite designed for researchers and AI coding agents (Claude Code, Codex, Cursor, Gemini, etc.). It empowers authors to build Oral-level scholarly narratives, eliminate defensive hedging and AI writing tells, guarantee citation authenticity through 1st/2nd-degree reference tracing and live web verification, and achieve dense, publication-grade page layouts.

---

## 🎯 Four Core Problems Solved

| Common Pain Point | `goat-academic-writing-skills` Solution |
| :--- | :--- |
| **1. Unfocused Narrative & Track Mismatch** | Establishes a direct 4-step Abstract flow (**Current Progress $\rightarrow$ Unsolved Problem $\rightarrow$ Specific Aspects of Improvement/Categorization $\rightarrow$ Achieved Effect**); expands the Introduction naturally in three parts ending with bulleted contributions; moves non-core hardware/engineering setups to the Appendix. |
| **2. Defensive & Apologetic Writing** | Strictly bans weak hedges (`unavailable`, `obtained merely from`, `cannot be certain due to lack of`, `does not aim to`); replaces apologetic caveats with **positive boundary scoping**; replaces row-by-row table recitation with insight-driven discussion. |
| **3. AI Punctuation Tells, Repetitive Words & Fake Citations** | **Replaces >95% of semicolons (`;`) and colons (`:`)** with periods or commas; integrates cross-references (`Figure X`, `Table Y`) directly as sentence subjects or objects; **enforces unambiguous, domain-standard technical terms while varying general words like `effective` with synonyms to avoid intra-paragraph repetition**; traces **1st- and 2nd-degree citations** and enforces **100% live web verification**. |
| **4. Loose Layout, Large Blank Spaces & Page Flipping** | Supports **reference file paths** for figures, tables, and style files; enforces **aesthetic paragraph arrangement** (eliminating $<20\%$ widow lines and keeping line widths $\ge 80\%$ full); limits subheadings to $\le 5$ words; **minimizes figure/table-to-text spacing without overlap to avoid large blank gaps**, placing floats on the exact page of mention within the venue's page limit. |

---

## 📁 Repository Contents

- `SKILL_EN.md`: Full English specification for academic writing and aesthetic formatting.
- `SKILL_ZH.md`: Full Chinese specification for academic writing and aesthetic formatting.
- `README_EN.md`: English quick-start guide and ready-to-use prompt templates.
- `README_ZH.md`: Chinese quick-start guide and ready-to-use prompt templates.

---

## 🚀 Quick Start Guide

### ✨ Option 1: Mount in AI Coding Agents (Claude Code / Codex / Cursor)
Place `SKILL_EN.md` or `SKILL_ZH.md` into your agent's skill directory (e.g., `.claude/skills/goat-academic-writing-skills/SKILL.md`, or include it in `CLAUDE.md` / `.cursorrules` at your project root) so the agent automatically applies these rules whenever drafting prose, verifying `.bib` files, or adjusting LaTeX layouts.

### ✨ Option 2: Ready-to-Use Prompt Templates

#### 🎉 Scenario 1: Drafting or Rewriting Abstract & Introduction
> Using Pillar 1 of `goat-academic-writing-skills`, please rewrite the Abstract and Introduction of `main.tex`:
> 1. **Abstract**: Follow the 4-step flow (current progress in the field $\rightarrow$ unsolved core problem $\rightarrow$ specific aspects of our improvement/categorization $\rightarrow$ achieved performance), without any defensive *"This paper does not aim to..."* phrasing.
> 2. **Introduction**: Expand the Abstract in three parts—background evolution (with clustered citations), pros/cons of prior work and core bottlenecks, and our specific innovations—concluding with 3 clear bullet points summarizing our contributions.

#### 🔍 Scenario 2: De-AI Polishing, Lexical Variety & Live Citation Audit
> Apply Pillars 2 and 3 of `goat-academic-writing-skills` to audit and polish `main.tex` and `references.bib`:
> 1. Remove all defensive words (`unavailable`, `seems to`, etc.) and reframe limitations as positive scope boundaries.
> 2. Replace over 95% of semicolons and colons with periods or commas, and integrate parenthetical references like `(Figure X)` directly as sentence subjects or objects.
> 3. Ensure all technical terms are domain-standard, unambiguous, and globally consistent, while replacing repeated general words (such as `effective`, `show`, `improve`) with natural synonyms so no general word is repeated multiple times within the same paragraph.
> 4. Trace 1st- and 2nd-degree citations around our core references to fill any missing related work, and **verify every `.bib` entry via live web search** (title, authors, year, venue) to eliminate any hallucinated references.

#### 🎨 Scenario 3: Reference-Guided Formatting, Aesthetic Paragraphs & Compact Float Spacing
> Apply Pillar 4 of `goat-academic-writing-skills` for final aesthetic formatting on `main.tex` (Reference figure: `/path/to/ref_figure.pdf`, reference TeX: `/path/to/ref_paper.tex`, official style directory: `/path/to/official_style/`):
> 1. **Aesthetic Paragraph Arrangement**: Eliminate trailing widow lines shorter than 20% width by lightly editing secondary words, keep lines at least 80% full, and shorten all analytical subsection titles to $\le 5$ words without line wrapping.
> 2. **Compact Spacing & Page Limit**: Place figures and tables on the same page where they are first cited, **make the vertical gap between figures/tables and text as small as possible while remaining clean and non-overlapping to avoid large blank spaces**, and ensure the main text fits strictly within the venue's page limit.