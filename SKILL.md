---
name: academic-paper-writing
description: Comprehensive guide for academic paper writing and formatting in English. Covers language issues, style guidelines, organization, and LaTeX/Word tools. Use when user asks about "academic writing", "paper format", "LaTeX", "research paper", "thesis writing", "manuscript preparation", or requests help with "abstract", "introduction", "related work", "conclusion" sections.
---

# Academic Paper Writing and Formatting Guide

This skill provides comprehensive guidance for writing and formatting academic papers in English, based on common issues identified across 100+ papers. It covers language level problems, style issues, organization, and tools.

## Language Level Issues

### Voice and Pronoun Usage

**CRITICAL: Use Active Voice in Abstract and Introduction**
- In abstract and contribution sections, prefer active voice over passive
- Use "we" boldly - it represents the authors who proposed the model/algorithm
- Do not use "this paper" repeatedly or passive voice unnecessarily

**When to use "we":**
- In abstract and contribution summarization: "We propose...", "We design..."
- When describing author actions and contributions

**When NOT to use "we":**
- When describing the model itself (it's not about the authors)
- When explaining model characteristics
- Example of WRONG usage: "The proposed framework uses intersections, so **we can** avoid noise influence." → The framework avoids noise, not "we"

### Tense Rules

- Use **simple present** and **present perfect** throughout (except Related Work)
- Related Work: use **past tense** when describing previous work
- Only experimental section may occasionally use past tense

### Common Language Mistakes

**DO NOT USE:**
- "can be", "may be" in abstract/contribution/conclusion when describing what you did
  - Use "is", "are" instead - you've done it, so state it directly
- "We believe", "We think" - data/theory/experiments matter, not beliefs
- "And" at the beginning of sentences (colloquial)
- "very important" - use "vital", "fundamental", "paramount", "core issue"

**USE CORRECTLY:**
- "cannot" (one word, NOT "can not")
- "such as" (NOT "like" for examples)
- "different from" (NOT "unlike")
- "i.e." (NOT "namely", "aka")
- "find" (NOT "find out")
- "attempt to" (variation with "try to")
- "that" in object clauses (don't omit it)
- "as follows" (NOT "as following" or "as followed")

### Punctuation and Formatting

- **NO Chinese punctuation**: No book title marks (《》), no long dashes (——), no enumeration commas (、)
- In LaTeX: quotes are `` '' (two backticks, two apostrophes)
- Space after periods and commas: `. Word` NOT `.Word`
- Space around parentheses: `(word)` NOT `(word )` or `( word)`
- Sentences should be **20-30 words** maximum for beginners
- Split 50-word sentences into two 25-word sentences

### Grammar Issues

- Subject-verb agreement: check singular/plural
- "Let something **do**" (NOT "does")
- "training set", "test set" (NOT "testing set")
- "prove" → use "verify" or "testify" instead (few things can be truly proven)
- Avoid "mainly include", "mainly contain" - just list what's included
- "if XXX, then XXX" - the "then" is unnecessary

### Model Description Guidelines

**Avoid subjective language in model descriptions**
- Do NOT use phrases like "we are interested in", "we focus on"
- These add unnecessary subjectivity to technical descriptions
- Example:
  - WRONG: "The distribution **we are interested in** is a conditional language model based on the input statement x."
  - RIGHT: "The distribution is a conditional language model based on the input statement x."

### Subject Matching Errors

**CRITICAL: Watch for dangling participles**
- WRONG: "When using XXXX to deal with the problem, the following steps are required."
  - "using" is done by humans, not by "the following steps"
- RIGHT: "When XXXX is used to deal with the problem, the following steps are required."

### Pronoun and Article Usage

- In Related Work, referring to authors: use "authors" (plural), NOT "author" (singular)
  - Computer science papers typically have multiple authors
- Generic references: use "users" or "a user" (NOT "the user" for generic reference)
- Avoid redundant: "the two both datasets" → either "the two datasets" OR "both datasets"
  - Same for "the total number of the whole bikes" → "the total number of bikes"

### Word Choice Precision

- "including" vs "such as":
  - "such as" = giving examples (not exhaustive)
  - "including" = enumeration/containing (suggests completeness)
- After "using XXXX and XXXX": both MUST be nouns
  - RIGHT: "using information fusion and a collaborative approach"
  - WRONG: "using information fusion and collaboratively"
- Before using a new term:
  - Check if the term has been used by previous researchers
  - Make sure to explain what it means in your paper

## Style Guidelines

### Formal Academic Writing Rules

**ABSOLUTELY FORBIDDEN:**
- Colloquialisms: "OK", "fine", "Of course"
- Slang of any kind
- Famous quotes/proverbs
- Contractions: "don't", "can't", "it's" (use "do not", "cannot", "it is")
- "and so on", "etc." in formal writing
- Inverted structures: "not only...but also"
- "the more...the more" patterns
- Abbreviations in references (like [C][J][D] - these are Chinese format)

### Word Choice Guidelines

**Use PRECISE SINGLE words:**
- Instead of vague multi-word phrases like "take on", "put up", "get on", "make up"
- Exception: phrases with single clear meanings like "take advantage of"

**AVOID:**
- Overly obscure words (check if commonly used in search engines)
- Uncertain words that reduce credibility: "sometimes", "perhaps" → use "is likely to", "probably"
- Very general words: "information", "process" (unless in established phrases)
- "about" when meaning "approximately" - it's too informal

### Consistency Requirements

**CRITICAL: Maintain consistency throughout:**
- Same concept = same terminology throughout entire paper
  - Example: "similarity computation" NOT sometimes "similarity calculation", "similar relation computation"
  - Example: "document summarization" NOT alternating with "document digest"
- Abbreviations: write full form on first use, then abbreviation consistently
  - Format: "Neural Collaborative Filtering (NCF)"
  - Use full form once per paper (may repeat in abstract since it's separate)
- Section/Figure/Table references: capitalize consistently
  - Either "Section 2.3" throughout OR "section 2.3" throughout (not mixed)

### Capitalization Rules

- First word after "Abstract.", "Section X.X" must be capitalized
- First word of EVERY LINE must be capitalized (after line breaks)
- Proper nouns, acronyms: ACM, IEEE, IET (all caps, NOT Acm, Ieee)
- Model/framework names must be consistent: "AB-CD" not "ab-cd" sometimes
- DO NOT capitalize terms mid-sentence for emphasis
  - WRONG: "The whole architecture of **Attention** mechanism"
  - RIGHT: "The whole architecture of attention mechanism"
- **Check publisher guidelines** for proper noun and abbreviation capitalization preferences
  - Different publishers may have different rules
  - Example: "Deep Learning" vs "deep learning" - follow your target venue's style

### Font Consistency

- **CRITICAL**: Entire body text must use consistent font
  - ACM/IEEE/ACL/Springer templates: typically Times New Roman
  - NO other fonts in body text (except image labels)
  - Headings: follow template specifications

### LaTeX Indentation

- Do NOT write flush left from first line to last line
- Follow section hierarchy with proper indentation
- Every line should respect section-level indentation
- This includes formulas, tables, and all content

### Sentence Structure

- Every sentence must have clear subject, verb, object
- NO sentences without subjects (common in non-native speakers)
  - WRONG: "Then select the words according to the importance."
  - RIGHT: "We then select the words according to the importance."
- Between independent sentences: use conjunctions (and, but, or)
- Limit use of "Moreover", "Additionally", "Furthermore" - can use simple "Also"
- Use "First", "Second", "Third" (NOT "Firstly", "Secondly", "Thirdly")
- Avoid scattering sentences with too many commas
  - Three short parallel items: add one comma between second and third
  - Two short parallel items: NO comma needed between them

### Grammar Clauses

**Restrictive vs Non-restrictive Relative Clauses:**
- **Restrictive clauses**: use "that" (defines/limits the noun)
  - Example: "The model **that** uses attention performs better."
- **Non-restrictive clauses**: use "which" (adds extra information)
  - Example: "Transformer models, **which** use attention, have achieved success."
- **CRITICAL**: Do NOT use "which" for restrictive clauses
  - This creates unnecessary ambiguity about clause nature
  - Academic writing prioritizes precision over grammatical permissiveness

### Semicolon Usage

- Semicolons (;) ARE acceptable in academic papers
- Use to connect closely related independent clauses
- Use in complex lists with internal commas
- Example: "The model has three advantages: it is fast; it is accurate; and it is scalable."

### Citation Guidelines

- In Related Work, cite by author's last name only
  - One or two authors: list all
  - Three or more: "Xu et al." (NOT "Y. Xu et al.")
  - NO first name initials
- Multiple citations: sort chronologically `\cite{Lee2000,GouvertOF2020,XuWGSYX21}`
- Conference papers: "In Proceedings of XXX" (proceedings contain the papers)
- References should include all authors (no "et al." in reference list)
- Reference format must be consistent throughout

**Authoritative Citation Sources:**
- DO NOT cite: Wikipedia, Baidu Baike, or other encyclopedias
- DO cite: peer-reviewed conference papers, journals, books, monographs
- Avoid arXiv papers IF published version exists (cite the published version)
- Acceptable: websites for dataset sources or software repositories

**Reference Formatting:**
- Journal papers: include volume, number, pages, year
- Conference papers: generally no volume/number (unless published by journal)
- Format: "In Proceedings of XXX" (papers are contained in proceedings)
- Do NOT use [C][J][D] markers (these are Chinese format, NOT English)

## Organization and Structure

### Section Guidelines

**Introduction:**
- Use "First", "Second", "Third" for enumeration
- Clearly distinguish your method from baselines
- Emphasize "the proposed method", "our proposed model"
- Use correct verbs: "propose", "design", "develop", "study", "explore", "investigate"

**Related Work:**
- Should have at least 20 references for full papers
- Use past tense when describing previous work
- Once you use past tense for a work, continue with past tense
- Write everything in your own words - NO copying from cited papers
  - >2/3 consecutive words repeated = plagiarism
  - >1/2 words (not necessarily consecutive) = flagged as possible duplication

**The Proposed Method:**
- Explain baselines appropriately, NOT in great detail
- Don't derive standard formulas for baselines
- Focus on YOUR contribution

**Experiments:**
- Avoid "we can see XXX" for non-obvious phenomena
- Use objective: "Figure 5 shows..."
- **Don't just describe trends - explain WHY trends occur**
  - WRONG: "The accuracy first increases and then decreases."
  - RIGHT: "The accuracy increases from 70% to 85% as training epochs grow from 1 to 50, likely because the model learns more representative features. However, after 50 epochs, accuracy declines to 82%, suggesting overfitting on the training data."
- For evaluation metrics: give full form if abbreviation used

**Conclusion:**
- NOT a copy of Abstract
- Write what you proposed, results obtained, what this demonstrates
- Shows your hypothesis/design approach is correct

### Visual Elements

**Figures:**
- Must be clear, properly sized, correctly positioned
- Labels should be readable
- Use Python/Matlab/Mathematica (NOT Excel when possible)
- Figure captions go BELOW the figure
- Use vector formats (.pdf, .eps) for LaTeX (NOT .jpg, .png)

**Tables:**
- Table captions go ABOVE the table
- Font size should be one size smaller than body text

**Formulas:**
- MUST have preceding explanation before presenting
- MUST have following explanation after presenting
- "where" is lowercase (NOT "Where" - it's part of the same paragraph)
- Use standard mathematical notation
- Use × or · for multiplication (NOT asterisk/snowflake)
- Equation numbering: either all numbered or none numbered (be consistent)
- Mathematical symbols (m, n, d, etc.) should be italicized in LaTeX

### Titles and Headings

- Use noun phrases or gerund phrases
- Can include modifying adjectives/verbs
- DO NOT start with verbs or adjectives
- Level 1 and level 2 headings: format consistently
  - Either "Introduction" or "INTRODUCTION" throughout (not mixed)
  - Same for "The Proposed Method", "Experiments", etc.
  - Do NOT mix: "Introduction" then "RELATED WORK" then "Conclusion"

### Document Layout

- **NO large whitespace gaps** (5+ consecutive blank lines)
- Paper folder naming: use meaningful names
  - BAD: "1", "paper", "doc"
  - GOOD: "The manuscript", "paper for AAAI", "ICML submission"

### Mathematical Notation

- **Matrices**: UPPERCASE (A, B, X)
- **Scalars**: regular font
- **Vectors**: lowercase (traditional ML: bold or subscript; neural networks: not strictly enforced)
- **Sets**: UPPERCASE
- **Mathematical symbols must be italicized in LaTeX**:
  - Variables like $m, n, d, i, j$
  - Example: "for $m$ users and $n$ items" (not "for m users")
  - Note: brackets, numbers, subscripts that are NOT variables should NOT be italic

## Common Technical Mistakes

### Common Confusions

- "denote" vs "donate" (completely different meanings)
- "the same as" NOT "the same with"
- "compared to" NOT "compared with"
- "because" or "as" NOT "since" (since means "now that" in modern English)
- "XXX-based YYY" with hyphen (NOT "XXX based YYY")
- "identical to" is a good alternative to "the same as"

### Common Expression Errors

**WRONG expressions to avoid:**
- "As can be seen from the results" → Use "As **it** can be seen from the results" OR "From the results, we can observe that"
- "find out" → Use "find" alone (no need for "out")
- "the two both datasets" → Use "the two datasets" OR "both datasets" (redundant)
- "the total number of the whole bikes" → Use "the total number of bikes"
- "Of course" → Too colloquial for academic writing
- "and so on" → Use "etc." is also colloquial; use formal alternatives or list explicitly
- "capture" → Overused; prefer "learn", "mine", "compute", "extract"
- "obtain" → Not very professional; use "achieve", "produce", "generate", "yield", "form"

### Verb Forms

- Prefer present participle (-ing) over infinitive (to ...) in abstract and conclusion
- This creates more flowing, active prose
- Example: "Our method **achieving** state-of-the-art results..." vs "to achieve..."

### Word Position Issues

- "in each iteration" more common than "at each iteration"
- "in the first dataset" more common than "on the first dataset"
- "impact" is a COUNTABLE noun: "a large impact", NOT "large impact"

### Bibliography File (.bib) Guidelines

**Standard order (this reduces errors):**
```
author
title
booktitle or journal
vol
no
pages
year
```

**Why follow this order?**
- Properties scattered randomly make it difficult to spot errors
- Consistent format helps with manual verification
- Makes it easier to identify missing or incorrect information

**DELETE these 5 items (they clutter your .bib file):**
- `editor = {xxx and xxx and xxx}`
- `timestamp = {Wed, 16 Oct 2019 14:14:55 +0200}`
- `keywords = {XXXXXXXXXXXXXXXXXXXXX}`
- `bibsource = {dblp computer science bibliography, https://dblp.org}`
- `abstract={xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx}`

**Create meaningful citation keys:**
- Use "AuthorConferenceYear" format: `ZhangICSE2022` NOT `60901175`
- Citation key should let you identify the paper at a glance
- Add blank line between entries for readability

## Tools Recommendations

### LaTeX vs Word

**STRONGLY RECOMMEND LaTeX:**
- Easier to switch templates
- Better bibliography management with .bib and .bst files
- Standard skill for graduate students
- Professional typesetting

**LaTeX Editors:**
- Overleaf (online)
- TexStudio (lightweight)
- TexLive (comprehensive)
- WinEdt (slower updates)

### If Using Word

- Enable ALL spell-checking options
- For equations: use "Insert → Formula" but change font to Times New Roman
  - Formula tools → abc text → select Times New Roman → italicize
  - Note: brackets, numbers, superscripts should NOT be italic
- Use "References → Insert Footnote" (don't create manually)
- Check that all references appear in text (delete unused ones)

### Drawing Tools

- Preferred: Python (matplotlib), Matlab, Geometer's Sketchpad, Visio, PPT
- Export as .pdf or .eps (vector formats) for LaTeX
- DO NOT export as .jpg/.png (raster formats)
- Keep original files - don't discard after creating figures

### Email Guidelines

- Use .edu email or Gmail/Hotmail/Foxmail
- DO NOT use QQ, 126, 163 emails

## Quick Checklist

### Before Submission:
- [ ] Spell check enabled and run
- [ ] All Chinese punctuation removed
- [ ] "we" usage appropriate (active in abstract/contributions)
- [ ] Tenses correct (past in Related Work, present elsewhere)
- [ ] No contractions (don't, can't, it's)
- [ ] All abbreviations defined on first use
- [ ] Terminology consistent throughout
- [ ] Reference format consistent
- [ ] All figures/tables have explanation before and after
- [ ] Figure/table captions in correct position
- [ ] Equations use "where" (lowercase)
- [ ] .bib file cleaned (removed 5 unnecessary items)
- [ ] No "can be"/"may be" in abstract/conclusions
- [ ] All citations in text appear in references
- [ ] All references in text are cited
- [ ] Sentence length reasonable (20-30 words average)
- [ ] No dangling participles (subject matching)
- [ ] Font consistency (Times New Roman for body)
- [ ] LaTeX indentation follows section hierarchy
- [ ] No large whitespace gaps (5+ lines)
- [ ] Mathematical symbols italicized in LaTeX
- [ ] References authoritative (no Wikipedia/Baidu Baike)
- [ ] Paper folder has meaningful name

## Common Issues and Solutions

### Issue: Skill not triggering
**Solution:** Check your description field includes specific trigger phrases like "academic writing", "paper format", "LaTeX", "abstract", "introduction"

### Issue: Punctuation confusion
**Solution:**
- English: `. space` (period then space)
- Chinese: `.` (no space after)
- English quotes: ``text''
- Chinese quotes: "text"

### Issue: "we" overuse
**Solution:** Use "we" for author actions, NOT for model behavior
- RIGHT: "We propose a novel framework."
- WRONG: "The framework uses X, so we can achieve Y." → "The framework uses X to achieve Y."

### Issue: Uncertain language
**Solution:**
- Avoid: "maybe", "perhaps", "sometimes" (reduces credibility)
- Use: "may", "usually", "often", "is likely to", "probably"
- In abstract/conclusion: Use "is", "are" (NOT "can be", "may be")

---
## First Principles

**The First Principle: "Write Correctly"**

Before worrying about style, length, sophistication, or elegance:
1. **Write what you actually did** - express your thoughts and methods clearly
2. **Write what you actually want to say** - be direct and honest
3. **Get it down first** - refinement and polishing come SECOND

**Do NOT worry about:**
- "Is this too long?"
- "Is this too simple?"
- "Is this too Chinese-style?"
- "Is this too wordy?"

**Common anxiety that holds writers back:**
- Fear of imperfect English
- Over-thinking sentence structure
- Premature polishing before content is complete

**Remember:**
- You can always improve a complete draft
- You cannot improve a blank page
- Clarity of expression beats stylistic flourishes
- Content is king; presentation is queen

**When in doubt:**
- Choose clarity over complexity
- Choose consistency over variety
- Choose directness over circumlocution
- Academic writing prioritizes **precision and readability**

---
## Summary

This guide provides comprehensive coverage of academic writing pitfalls identified across 100+ papers. Use it as a reference before submission, but remember: the first principle is to **write correctly** and express your ideas clearly. Refinement comes second.

**Key takeaways:**
- Use active voice and "we" in abstract/contributions
- Eliminate Chinese punctuation and colloquialisms
- Maintain consistency in terminology, formatting, and style
- Focus on clarity over complexity
- Write for the reader, not for yourself
- Cite authoritative sources (peer-reviewed, not encyclopedias)
- Follow LaTeX/Word best practices for academic templates
