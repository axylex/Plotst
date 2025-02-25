---
title: "Plotting with CtEZ"
description: "Simple plotting library"
author: "Mateen Sharief, Jahan Zaib and Omer Mohammed"
date: "2/25/2025"
---

# Typst
Typst is a markup-based typesetting system designed to be an easier, faster, and more intuitive alternative to LaTeX. It combines simplicity, real-time compilation, and flexibility, making it ideal for academic papers, reports, presentations, and technical documents.

## How to install

```bash
Linux: View Typst on Repology
macOS: brew install typst
Windows: winget install --id Typst.Typst
```
## Usage

Once you have installed Typst, you can use it like this:
```sh
# Creates `file.pdf` in working directory.
typst compile file.typ

# Creates PDF file at the desired path.
typst compile path/to/source.typ path/to/output.pdf
```

- **Simpler Syntax**: Compared to LaTeX, Typst uses a more readable and concise syntax.  
- **Real-time Compilation**: Instant preview of changes without the need for complex build processes.  
- **Customizable Templates**: Users can create their own layouts and formatting rules.  
- **Mathematical Typesetting**: Supports equations and mathematical symbols, similar to LaTeX.  
- **Vector Graphics & Diagrams**: Allows integration of charts, graphs, and figures.  


$$
y = x^2
$$


I can create lists easily:

- One
- Two

I can also create numbered lists:

1. One
2. Two


Or, create a table:

| Name  | Age |
|-------|-----|
| Alice | 20  |
| Bob   | 21  |

