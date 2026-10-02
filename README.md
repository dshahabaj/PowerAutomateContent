# Power Automate Content

A collection of standalone, browser-based presentations and lessons about Power Automate and the Power Platform. No build step or package installation is required.

## Content

### Power Platform Concepts and ALM

- [Connection References: modern deck](ConnectionReference-modern.html) — connectors, connections, architecture, deployment, governance, and best practices.
- [Connection References: new version](ConnectionReferenceNew.html) and [updated version](ConnectionReferenceUpdated.html) — alternate filenames for the same presentation.
- [Connection References: earlier deck](ConnectionRefrence.html) — an earlier overview of architecture, deployment, migration, ALM, and security.
- [Child Flows](childflow.html) — modular flows, input and output, architecture, and common use cases. [childflows.html](childflows.html) is an identical copy.
- [Data Loss Prevention policies](dlp.html) — connector classification, policy behavior, troubleshooting, and best practices.
- [Environment Variables](environmentvariables.html) — variable types, setup, deployment, and common mistakes. [envvariable.html](envvariable.html) is an identical copy.
- [Solutions](solutions.html) — managed and unmanaged solutions, environment portability, and export/import.
- [Azure DevOps task creation](AzureDevOps.html) — an automated task-creation workflow, including SharePoint data and work-item field mapping.

### Data Operations

- [Compose](compose.html) — values, expressions, strings, JSON payloads, logging, date calculations, and when to use variables.
- [Select](select.html) — reshape arrays, map or rename fields, create CSV/HTML output, and compare Select with Filter Array.
- Filter Array lesson versions: [version 1](newtemplate.html), [version 2](newtemplate2.html), [version 3](newtemplate3.html), and [version 4](newtemplate4.html). These cover conditions, common use cases, nested data, pitfalls, and performance.

### Personal

- [Happy Birthday Awais](HappyBirthdayAwais.html) — a standalone birthday page.

## Run Locally

Open any HTML file directly in a browser, or serve the repository root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/` and select a page.

## Content Conventions

- Keep each presentation or lesson self-contained in its HTML file.
- Group new README links by topic and include a concise description of the content.
- When a file is an alternate filename or exact copy, note that relationship to make duplicate content clear.
