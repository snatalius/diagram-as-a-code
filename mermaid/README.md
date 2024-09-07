# Mermaid

https://mermaid.js.org/

The best about Mermaid is that it integrates natively with markdown renderring processes on GitHub.

```mermaid
graph TD
    A((Start)) --> B[Process 1]
    B --> C{Decide 1}
    C -- yes --> D[Process 2]
    C -- no --> E[Process 3]
    E --> B
    D --> F[fa:fa-file Process 4]
    F --> Z((End))
```

To render in VSCode, use any available extension like `Markdown Preview Mermaid Support`