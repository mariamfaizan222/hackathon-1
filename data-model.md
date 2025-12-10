# Data Model: Docusaurus Book

This document describes the data model for the Docusaurus book, which is based on the file system structure.

## Entities

### 1. Chapter

A chapter is a container for a group of related lessons.

-   **Representation**: A directory within the `docs` directory.
-   **Naming Convention**: The directory name should be prefixed with a two-digit number to define its order (e.g., `01-introduction`).
-   **Attributes**:
    -   `title`: The title of the chapter, defined in the `_category_.json` file within the chapter's directory.

### 2. Lesson

A lesson is a single piece of content within a chapter.

-   **Representation**: A markdown file (`.md` or `.mdx`) within a chapter directory.
-   **Naming Convention**: The file name should be prefixed with a two-digit number to define its order within the chapter (e.g., `01-what-is-docusaurus.md`).
-   **Attributes**:
    -   `title`: The title of the lesson, typically the `h1` heading in the markdown file.
    -   `content`: The body of the lesson, written in markdown.
    -   `front-matter`: Optional metadata at the top of the file (e.g., for custom tags, author information).
