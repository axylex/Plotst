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
### Advantages
- **Simpler Syntax**: Compared to LaTeX, Typst uses a more readable and concise syntax.  
- **Real-time Compilation**: Instant preview of changes without the need for complex build processes.  
- **Customizable Templates**: Users can create their own layouts and formatting rules.  
- **Mathematical Typesetting**: Supports equations and mathematical symbols, similar to LaTeX.  
- **Vector Graphics & Diagrams**: Allows integration of charts, graphs, and figures.  


# Typst CeTZ

CeTZ, short for "ein Typst Zeichenpaket," is a drawing library for Typst inspired by LaTeX's TikZ and the Processing programming language. It offers an intuitive API for creating vector graphics directly within Typst documents, facilitating the creation of diagrams, plots, and various visual elements. 

## How to install

To install the CeTZ package under your local typst package dir you can use the install script from the repository.
```sh
just install
```

## Usage
For information, see the [online manual](https://cetz-package.github.io/docs).
The installed version can be imported by prefixing the package name with @local.

```typst
#import "@local/cetz:0.3.2"

#cetz.canvas({
  import cetz.draw: *
  // Your drawing code goes here
})
```

## Examples

<img src="c:\Users\FARHAT\Downloads\WhatsApp Image 2025-02-26 at 12.11.50 AM.jpeg" alt="Description" width="500">


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

