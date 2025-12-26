# Copilot Instructions for Educational Materials Review

This repository contains educational materials for exam preparation.
GitHub Copilot Reviews should follow the instructions below when reviewing pull requests.

---

## 1. Role of Copilot Reviews

Copilot acts as the **first-stage proofreader**.

Its purpose is to:

- Reduce human workload
- Eliminate mechanical errors
- Improve consistency

Copilot **must not** replace human judgement on educational correctness.

---

## 2. What to Review (Required)

Copilot should actively check and comment on the following:

### 2.1 Language & Typographical Errors

- Typographical errors and conversion mistakes
- Inconsistent punctuation or spacing
- Broken sentences or obvious grammatical issues

### 2.2 Terminology & Notation Consistency

- Inconsistent use of technical terms
- Notation inconsistencies (symbols, variables, option labels)
- Violations of rules defined in:
  - `common/notation.md`
  - `common/style.md`
  - `common/units.md`

### 2.3 References & Structure

- Missing or incorrect references to figures, tables, equations, or options
- Inconsistent numbering (e.g., 図・表・問・選択肢)
- Headings hierarchy issues in Markdown

### 2.4 Markdown / LaTeX Syntax

- Broken Markdown syntax (lists, headings, emphasis)
- Unbalanced LaTeX math delimiters (`$`, `$$`)
- Common LaTeX errors (unclosed environments, malformed commands)

---

## 3. What NOT to Review (Forbidden)

Copilot **must not**:

- Judge correctness of answers or explanations
- Evaluate pedagogical adequacy
- Change the meaning of explanations
- Rewrite explanations aggressively
- Introduce new examples or interpretations

If correctness is uncertain, Copilot may:

- Flag the section as _"needs human review"_
- Ask for clarification without proposing a fix

---

## 4. How to Comment

### 4.1 Comment Style

- Be concise and specific
- Reference the exact line or section
- Prefer suggestions over rewrites

### 4.2 Example Comments

✅ Good:

> Possible typo: “データ量は（②）となる” → placeholder not resolved.

> Inconsistent terminology: “ラスタ形式” vs “ラスター形式”.

⚠️ Acceptable:

> This explanation may require confirmation by a human reviewer.

❌ Not allowed:

> This answer is incorrect.
> This explanation should be rewritten as follows.

---

## 5. Educational Material Conventions

- Option numbers use circled numerals: ⓪ ① ② ③ ...
- Answers are explicitly marked with **正** or **誤**
- Reasoning must follow problem statements closely

Copilot should respect these conventions and flag deviations.

---

## 6. Final Reminder

Copilot Reviews is a **supporting tool**, not an authority.

When in doubt:

- Do not guess
- Do not rewrite
- Escalate to human review

End of instructions.
