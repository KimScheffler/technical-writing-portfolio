# Style Guide – English Software Documentation

This style guide defines binding rules for creating
English, **task-oriented software documentation** in this portfolio.
It applies across projects (for example, the Snipping Tool and memoQ).

---

## Contents

1. [Information types](#information-types)
2. [Writing style](#writing-style)
3. [Sentence structure and tone](#sentence-structure-and-tone)
4. [Terminology](#terminology)
5. [Task structure](#task-structure)
6. [Notes](#notes)
7. [Reference information](#reference-information)
8. [Images and graphics](#images-and-graphics)
9. [Accessibility](#accessibility)
10. [Maintainability](#maintainability)

---

## Information types

The documentation consistently distinguishes between the following
information types:

- **Concept**  
  Explains *what* something is and *what it is used for*.
- **Task**  
  Describes step by step *how* to achieve a goal.
- **Reference**  
  Provides lookup information (for example, formats, options, or keyboard shortcuts).

Information types must **not be mixed**.

---

## Writing style

### Tone
- clear
- neutral
- helpful
- non-promotional

### Addressing the user
- Use **direct address** consistently (imperative form).
- Avoid personal pronouns such as *we* or *I*.

### Active voice
- ✔ *Select **New***  
- ✘ *The **New** button is selected*

---

## Sentence structure and tone

### Short and clear
- One idea per sentence
- Avoid complex or nested sentence structures

### Imperative in tasks
- Each step starts with a verb in the imperative form:
  - *Open …*
  - *Select …*
  - *Click …*

### Order
- **Action → purpose**
  - *Select **New** to start capture mode.*

---

## Terminology

UI labels are used **exactly as they appear in the user interface**.

### Consistency

UI elements:
- are **not translated** if they appear in English in the application
- are **not paraphrased**
- are **formatted consistently** (bold)
- follow the rule: **one term = one meaning**

This applies in particular to buttons, modes, and tool names.

### Examples from this portfolio

| Term | Meaning |
|------|--------|
| Snipping area | Area of the screen to be captured |
| Screen area | The area selected during capture |
| Photo mode | Mode for creating screenshots |
| Video mode | Mode for recording screen videos |
| Color value | Result of selecting a color |

UI labels are formatted in **bold**.

---

## Task structure

Each task consists of:

1. **Heading** (goal of the task)
2. **Steps**
3. **Result** (outcome)

#### Optional:
- **Notes** for options or special cases
- **No feature lists** within tasks

---

### Lists and step sequences

Different list types are used intentionally:

- **Numbered lists** are used when the **order of steps is important**,
  especially in tasks and procedures.
- **Bullet lists** are used when the **order does not matter**,
  for example in options, notes, or reference sections.

#### Length of step sequences

A step sequence should contain **no more than 10 steps**.

If a workflow requires more than 10 steps:
- split it into **two or more logically separated tasks**  
  **or**
- complement the steps with a **clear process diagram or graphic**

The goal is to keep procedures readable, understandable, and maintainable.

---

## Notes

Notes:
- are optional
- appear **after** the steps
- describe options or additional information
- do **not** contain step sequences

Example:
> When copying text, you can optionally enable automatic removal of line breaks.

---

## Reference information

Reference content:
- is designed for lookup
- does not contain full task procedures
- may include tables or lists

Typical reference topics include:
- keyboard shortcuts
- file formats
- settings
- UI elements used in multiple contexts

---

## Images and graphics

### Usage
- Use images only when they add value
- Maximum of 1–2 images per task
- No decorative images

### Placement
- Directly after the step they refer to
- Or centrally in the reference section if reused

### Alt text
- Describes **content and purpose** of the image
- Avoid generic descriptions such as “screenshot”

Example:
> *Button to select Photo mode in the Snipping Tool*

---

## Accessibility

- Use meaningful headings
- Provide descriptive alt text
- Avoid purely visual references (for example, “see above” or “as shown in the image”)

---

## Maintainability

- Avoid redundancy
- Centralize reusable information
- Abstract UI-dependent details where possible

---


