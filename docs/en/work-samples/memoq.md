# memoQ (Version 9.7.12)

## Content

1. [What is memoQ?](#what-is-memoq)
2. [What is a memoQ project?](#what-is-a-memoq-project)
3. [Create a new memoQ project](#create-a-new-memoQ-project)
4. [What is a Translation Memory?](#what-is-a-translation-memory)
5. [Upload a Translation Memory](#upload-a-translation-memory)
6. [What is a Termbase (Glossary)](#what-is-a-term-base-glossary)
7. [Upload a Termbase (Glossary)](#upload-a-term-base-glossary)
8. [](#)
9. [](#)

---

## What is memoQ?

**memoQ** is a professional translation environment used by translators,
reviewers, and localization teams to manage and perform translation work.

It supports the translation of multilingual content by combining source files
with linguistic resources such as **Translation Memories (TMs)** and
**Glossaries (Term Bases)**.

memoQ is commonly used in professional translation workflows to ensure
consistency, quality, and efficiency across translation projects.

![memoQ – start view](../../assets/images/memoq-start.png)

---

## What is a memoQ project?

A **memoQ project** is the central workspace in which all translation-related
resources and files are managed.

A project defines the source and target languages, contains the files to be
translated, and serves as the container for translation resources such as
**Translation Memories (TMs)** and **Glossaries (Term Bases)**.

All further steps in memoQ—such as assigning TMs, adding glossaries, or starting
the translation—are performed within the context of an existing project.

---

## Create a new memoQ project

Create a new memoQ project that serves as the basis for managing translation
files and resources.

1. Open **memoQ**.
2. From the **Dashboard**, select **New project**.
   ![Create a new project in memoQ](../../assets/images/memoq-new-project.png)
3. Enter a **project name** that clearly identifies the translation task.
   ![New memoQ project dialog with project name and language selection](../../assets/images/memoq-new-project-2.png)
4. Select the required **source language** and **target language**.
5. Click **Next** to continue in the project creation wizard.
6. Add the files to be translated, if required.
7. Click **Finish** to create the project.

The memoQ project is created and ready to be enriched with translation resources
such as **Translation Memories** and **Glossaries**.

---

## What is a Translation Memory?

A translation memory (TM) is a database that stores previously translated text segments as source–target pairs. When translating, memoQ compares new content with existing entries in the translation memory and suggests:

- exact matches
- similar (fuzzy) matches

Using a translation memory helps translators:

- work more efficiently
- ensure consistency across projects
- reuse existing translations for recurring content

Translation memories are typically imported into a project and assigned to the project’s language pair.

---

## Upload a Translation Memory

This task describes how to add an existing translation memory (TM) to a memoQ project so that previously translated content can be reused during translation.

### Prerequisites

- A memoQ project is created and open.
- A translation memory file is available (for example, a `.tmx` file).

### Steps

1. Open the memoQ project to which you want to add the translation memory.
2. Select **Translation memories** in the project navigation.
   ![Translation memories section in memoQ](../../assets/images/memoq-new-TM.png)
3. Right-click the TM list and select **Create/Use New**.
4. Enter a name that matches your project.
5. Right-click the new entry in the list and select **Import TM**.
6. Browse to the location of the term base file, select it, and confirm.
7. In **Translation memory TMX import settings**, verify the **Source** and **Target** language codes and review the import    options as needed.
   ![Translation memory TMX import settings](../../assets/images/memoq-TM-settings.png)
8. Click **OK** to complete the import.

The translation memory is added to the project and can be used to automatically suggest existing translations during the translation process.

---

## What is a Term Base (Glossary)?

A term base (also called a glossary) stores **approved terminology** and its translations.

Unlike a translation memory, a term base contains individual terms, not full sentences. During translation, memoQ highlights terms from the term base to support correct and consistent terminology usage.

Term bases are commonly used to:

- enforce preferred terminology
- maintain consistency in technical or regulated content
- avoid incorrect or outdated term usage

Term bases are usually imported into a project and assigned to the relevant languages.

---

## Upload a Term Base (Glossary) from an Excel sheet

### Prerequisites
- A memoQ project is created and open.
- A term base file is available as an Excel sheet.

### Steps

1. Open the memoQ project to which you want to add the term base.
2. Select **Term bases** in the project navigation.
   ![Term Base section in memoQ](../../assets/images/memoq-new-TB.png)
4. Right-click the term base list and select **Create/Use New**.
5. Enter a name that matches your project.
6. Right-click the new entry in the list and select **Import term base**.
7. Browse to the location of the term base file, select it, and confirm.
8. Review the **term base import settings** and map the language columns as required.
   ![Term base Excel import settings](../../assets/images/memoq-TB-language.png)
9. Click **OK** to complete the import.

### Result

The term base is added to the project and approved terminology is highlighted during translation to support consistent term usage.

