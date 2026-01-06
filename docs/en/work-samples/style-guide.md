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

### Language Variant

This documentation uses international technical English with American English spelling and terminology,
except for UI labels, which are reproduced as shown in the application.

### Gender-inclusive language

For the sake of readability, this documentation uses gender-neutral language wherever possible.

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
Action → purpose

> **Example:**  
>*Select **New** to start capture mode.*

---

## Terminology

UI labels are **reproduced exactly** as they appear in the user interface. This applies even if the UI spelling differs from the language variant used in the documentation (for example, British vs. American spelling).


### Consistency

UI elements:
- are **not translated** if they appear in English in the application
- are **not paraphrased**
- are **formatted consistently** (bold)
- follow the rule: **one term = one meaning**

This applies in particular to buttons, modes, and tool names.

Binding UI terms are defined in the project-specific glossary and are used consistently throughout the documentation.

When a technical term is widely known under a more general name, the technical term is used as the primary term, followed by the commonly known term in parentheses at first mention (for example, *Term Base (Glossary)*). The primary term is used consistently thereafter.

---

## Task structure

Each task consists of:

1. **Heading** (goal of the task)
2. **Steps** and **Result** (outcome)

#### Optional:
- **Task introduction** (must not paraphrase the task heading; is used only when additional context is required) 
- **Notes** for options or special cases
- **No feature lists** within tasks


### Style

If an introductory sentence is required, it follows a **neutral, goal-oriented structure** and does not reference the information type (for example, “task”).

**Template:**
> This section describes how to <achieve goal>.

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

### Substeps in step sequences

Substeps may be used within a numbered step when they describe
configuration details or supporting actions that belong to a single main step.

**Substeps may be used when:**

- they do not represent standalone actions
- they would not make sense as separate numbered steps
- they clarify options, settings, or parameters

**Substeps must not be used to:**
- hide independent main actions
- bypass the maximum number of steps rule

If multiple substeps describe independent actions, the task must be split into separate steps or a separate task.

---

## Notes

Tasks may include short notes that link to relevant
reference sections (for example, keyboard shortcuts or UI overviews).

The following rules apply:
- Notes are optional.
- Notes appear **after** the steps.
- Notes describe options or additional information.
- Notes do **not** contain step sequences.
- Notes may link to reference sections.

This approach keeps tasks concise while ensuring that additional information
is centralized and easy to maintain.

> **Examples:**  
> - *You can also perform this action using a keyboard shortcut. See Keyboard shortcuts for details.*
> - *When copying text, you can optionally enable automatic removal of line breaks.*

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

> **Example:**  
> *Button to select Photo mode in the Snipping Tool*

### Highlighting UI elements

Rectangular highlights are used to mark UI elements in screenshots.

The following conventions apply:
- Shape: **Rectangle**
- Color: **Standard red** (RGB **255, 0, 0**)
- Stroke weight: **3 pt**
- No fill, outline only

UI elements are highlighted only when this supports the understanding of a task.
Multiple UI elements may be highlighted in the same screenshot if they are explained
within the same context.

Decorative highlights or multiple colors are not used.

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
- Support updates across software releases
