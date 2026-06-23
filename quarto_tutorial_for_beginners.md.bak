# Quarto Tutorial for Complete Beginners

Welcome! This tutorial is written for people who are completely new to **Quarto** and may also have **no background in R**.

Quarto is a tool for creating:
- reports
- blogs
- websites
- books
- presentations
- PDFs and Word documents

You write content in simple plain text using **Markdown**, and Quarto turns it into polished output.

---

## 1. What is Quarto?

Quarto is an open-source publishing system.

In simple words:
- You write text in a file
- You can add headings, lists, images, tables, and code
- Quarto converts that file into HTML, PDF, Word, slides, and more

You do **not** need to know R to start using Quarto.

Quarto can work with:
- plain Markdown only
- Python
- R
- Julia
- Observable JavaScript

If you are a beginner, you can first learn Quarto as a **document writing tool** without writing any code.

---

## 2. Why use Quarto?

Quarto is useful because it helps you:
- write once and create multiple output formats
- keep text, code, and results in one place
- create professional-looking documents
- make reproducible reports
- build personal websites, course notes, and books

### Example uses
You can use Quarto to create:
- class notes
- project reports
- resumes
- research papers
- tutorials
- data analysis reports
- technical blogs
- slide presentations

---

## 3. Do I need R to use Quarto?

**No.**

This is very important.

You can use Quarto without knowing R.

There are two common ways to use Quarto:

### Option A: Write only text
You write Markdown and create a document. No programming needed.

### Option B: Write text plus code
Later, if you want, you can add Python or R code blocks.

So if you are a complete beginner, start with **text-only documents**.

---

## 4. What do I need to install?

To use Quarto comfortably, install the following:

### Required
1. **Quarto**
2. **A text editor or IDE**

### Recommended editors
- **VS Code** (great for beginners)
- **RStudio / Positron** (optional, even if you do not use R)

### Optional tools
- **Python** if you want to run Python code later
- **R** if you want to run R code later
- **TinyTeX or TeX Live** if you want to create PDFs

### Install Quarto
Go to the official site:
- https://quarto.org/docs/get-started/

Download and install Quarto for your operating system.

### Check installation
Open your terminal and run:

```bash
quarto --version
```

If Quarto is installed correctly, you will see a version number.

---

## 5. What is Markdown?

Markdown is a very simple way to format text.

Instead of clicking buttons for bold headings or lists, you type small symbols.

### Examples

#### Heading
```markdown
# Main Title
## Section Title
### Smaller Section
```

#### Bold and italic
```markdown
**bold text**
*italic text*
```

#### List
```markdown
- item one
- item two
- item three
```

#### Numbered list
```markdown
1. First step
2. Second step
3. Third step
```

#### Link
```markdown
[Quarto Website](https://quarto.org)
```

This is one reason Quarto is beginner-friendly.

---

## 6. Your first Quarto document

Quarto documents usually use the `.qmd` extension.

Create a file called:

`hello.qmd`

Add this content:

```markdown
---
title: "My First Quarto Document"
format: html
---

# Hello

This is my first Quarto document.

## About Me

I am learning Quarto.

- It is simple
- It is beginner-friendly
- I do not need to know R to start
```

### What is the part between `---` and `---`?
That section is called **YAML**.

It stores document settings like:
- title
- author
- date
- output format

In this example:
- `title` sets the title of the document
- `format: html` tells Quarto to create an HTML page

---

## 7. How to render a Quarto file

To convert a `.qmd` file into output, Quarto uses the word **render**.

### Render from terminal
Run:

```bash
quarto render hello.qmd
```

Quarto will create an HTML file, usually:

`hello.html`

Open that file in your browser.

### Render in VS Code
If you use VS Code with Quarto installed, you can often preview or render directly from the editor.

---

## 8. Understanding a Quarto document structure

A simple Quarto document has two main parts:

### 1. YAML header
This controls document settings.

Example:

```yaml
---
title: "Beginner Tutorial"
author: "Your Name"
date: "2026-06-12"
format: html
---
```

### 2. Body content
This is where you write:
- headings
- paragraphs
- lists
- images
- tables
- code blocks

---

## 9. Basic formatting in Quarto

### Headings
```markdown
# Heading 1
## Heading 2
### Heading 3
```

### Paragraphs
Just write normal text.

### Line break
Leave a blank line between paragraphs.

### Bold, italic, and code
```markdown
**bold**
*italic*
`code`
```

### Blockquote
```markdown
> This is an important note.
```

### Horizontal line
```markdown
---
```

### Lists
```markdown
- apple
- banana
- orange
```

### Numbered lists
```markdown
1. Install Quarto
2. Create a file
3. Render the file
```

---

## 10. Adding images

You can add an image like this:

```markdown
![A sample image](images/example.png)
```

Explanation:
- text inside `[]` is alternate text
- text inside `()` is the image path

If your image is in a folder called `images`, the file path might be:
- `images/photo.jpg`
- `images/chart.png`

---

## 11. Adding links

```markdown
[Visit Quarto](https://quarto.org)
```

This creates a clickable link.

---

## 12. Adding tables

Simple Markdown table:

```markdown
| Tool   | Purpose            |
|--------|--------------------|
| Quarto | Create documents   |
| VS Code| Edit files         |
| Python | Run code optional  |
```

This becomes a formatted table in the output.

---

## 13. Code blocks in Quarto

Even if you do not know programming yet, it is helpful to understand the idea.

A code block is a section where you write code.

### Plain code block
```markdown
```bash
quarto render hello.qmd
```
```

This only displays code.

### Executable code block
If you have Python or R installed, Quarto can run code blocks and show results.

Example with Python:

````markdown
```{python}
print("Hello from Python")
```
````

If Python is available, Quarto can run it and include the output.

Again: **this is optional** for beginners.

---

## 14. A text-only beginner example

Create a file named `intro.qmd`:

```markdown
---
title: "Introduction to Quarto"
format: html
---

# Welcome

Quarto helps you create beautiful documents.

## What I learned

- Quarto uses `.qmd` files
- Markdown is easy to write
- I can create HTML pages
- I do not need R to begin

## My Next Step

I will learn how to add images and tables.
```

Render it:

```bash
quarto render intro.qmd
```

---

## 15. Creating different output formats

One powerful feature of Quarto is that you can generate different types of output.

### HTML
```yaml
format: html
```

### PDF
```yaml
format: pdf
```

### Word
```yaml
format: docx
```

### Multiple formats
```yaml
format:
  html: default
  pdf: default
  docx: default
```

Then run:

```bash
quarto render yourfile.qmd
```

### Important note about PDF
Creating PDFs usually requires a LaTeX installation such as TinyTeX.

If PDF rendering fails, start with HTML first.

---

## 16. Working with sections

A bigger document can be organized into sections.

Example:

```markdown
# Chapter 1
## Topic 1.1
## Topic 1.2

# Chapter 2
## Topic 2.1
```

This structure helps readers navigate your content.

In HTML output, Quarto may also generate a table of contents.

---

## 17. Adding a table of contents

You can enable it in YAML:

```yaml
---
title: "My Tutorial"
format:
  html:
    toc: true
---
```

This adds a table of contents automatically.

---

## 18. Changing theme and appearance

For HTML documents, you can choose themes.

Example:

```yaml
---
title: "Styled Document"
format:
  html:
    theme: cosmo
---
```

Some common themes:
- cosmo
- litera
- flatly
- darkly
- minty

You can experiment and see which one you like.

---

## 19. Creating a presentation

Quarto can create slides too.

Example:

```markdown
---
title: "My First Presentation"
format: revealjs
---

# Slide 1
Welcome to my presentation.

# Slide 2
- Point one
- Point two
```

Render it and Quarto will create a slide deck.

---

## 20. Creating a website

Quarto can also build websites.

A basic website project often includes:
- `_quarto.yml`
- `index.qmd`
- other `.qmd` pages

Example `_quarto.yml`:

```yaml
project:
  type: website

website:
  title: "My Website"
  navbar:
    left:
      - href: index.qmd
        text: Home
      - href: about.qmd
        text: About

format:
  html:
    theme: cosmo
    toc: true
```

Example `index.qmd`:

```markdown
---
title: "Home"
---

# Welcome

This is my Quarto website.
```

This is more advanced, but it shows how powerful Quarto is.

---

## 21. What is `_quarto.yml`?

When you work on a Quarto project with multiple files, `_quarto.yml` is the main configuration file.

It can define:
- project type
- website settings
- book settings
- output format defaults
- themes
- navigation

Think of it as the project control file.

---

## 22. How Quarto is different from Word

In Word, you usually format things visually.

In Quarto, you write simple plain text with lightweight formatting.

### Benefits of Quarto
- easier version control with Git and GitHub
- reusable documents
- cleaner structure
- can combine writing and code
- easier to publish online

At first it may feel unfamiliar, but many people find it easier over time.

---

## 23. Beginner workflow

Here is a simple beginner workflow:

1. Install Quarto
2. Create a `.qmd` file
3. Write Markdown content
4. Add YAML at the top
5. Render the file to HTML
6. Open the output in a browser
7. Edit and render again

This is enough to get started.

---

## 24. Common beginner mistakes

### Mistake 1: Forgetting the YAML lines
YAML must start and end with `---`.

### Mistake 2: Wrong file extension
Use `.qmd`, not `.txt`.

### Mistake 3: PDF not rendering
This often happens because LaTeX is not installed.

### Mistake 4: Broken image path
Make sure the image file path is correct.

### Mistake 5: Expecting code to run without installing Python or R
If you want executable code blocks, you need the related language installed.

---

## 25. Example: A small personal profile page

Create `profile.qmd`:

```markdown
---
title: "My Profile"
format:
  html:
    toc: true
---

# About Me

My name is Praveen.

I am learning Quarto to create documents and websites.

## Skills I Want to Learn

- Quarto
- Markdown
- GitHub
- Python

## Favorite Resources

- [Quarto](https://quarto.org)
- [Markdown Guide](https://www.markdownguide.org)
```

Render it:

```bash
quarto render profile.qmd
```

---

## 26. Example: A study notes document

```markdown
---
title: "Study Notes"
format: html
---

# Chapter 1

This chapter explains the basics.

## Key Points

- Point A
- Point B
- Point C

## Summary

This chapter introduced the main ideas.
```

This is useful for students and self-learners.

---

## 27. If you later want to learn code in Quarto

Once you are comfortable with text and Markdown, you can gradually add code.

### Python example

````markdown
```{python}
name = "Praveen"
print("Hello", name)
```
````

### R example

````markdown
```{r}
x <- 10
x + 5
```
````

But remember: learning Quarto does **not** require learning R first.

---

## 28. Best practices for beginners

- Start with HTML output
- Write short documents first
- Focus on Markdown before advanced features
- Keep files organized in folders
- Use meaningful file names
- Render often to check your output
- Learn one feature at a time

---

## 29. Suggested learning path

Here is a beginner-friendly order:

### Step 1
Learn:
- headings
- paragraphs
- bold and italic
- lists
- links

### Step 2
Learn:
- YAML title and format
- rendering to HTML
- adding images
- adding tables

### Step 3
Learn:
- themes
- table of contents
- multiple pages
- websites

### Step 4
Optional:
- Python code blocks
- R code blocks
- PDFs
- presentations
- books

---

## 30. Frequently asked questions

### Is Quarto only for data scientists?
No. Anyone can use it for writing and publishing.

### Do I need to know programming?
No. You can start with plain text and Markdown.

### Is Quarto free?
Yes, Quarto is open source and free to use.

### Can I create a website with Quarto?
Yes.

### Can I export to PDF and Word?
Yes.

### Do I need RStudio?
No. VS Code works very well too.

---

## 31. Final beginner checklist

Before starting, make sure you can do these:

- install Quarto
- create a `.qmd` file
- write a title in YAML
- add headings and lists
- render to HTML
- open the output file

If you can do these, you are already using Quarto successfully.

---

## 32. Conclusion

Quarto is a beginner-friendly publishing tool.

Even if you:
- do not know R
- do not know programming
- have never written Markdown before

You can still start learning Quarto today.

The best way to learn is:
- create a small `.qmd` file
- write simple content
- render it
- improve it step by step

Start simple, and build confidence gradually.

---

## 33. Next steps

Try this today:

1. Install Quarto
2. Create `hello.qmd`
3. Paste this content:

```markdown
---
title: "Hello Quarto"
format: html
---

# My First Page

I am learning Quarto.

- I can write text
- I can create headings
- I can render HTML
```

4. Run:

```bash
quarto render hello.qmd
```

That is your first Quarto success.

---

If you want, the next tutorial can be about:
- **Quarto for complete beginners using VS Code**
- **How to create a Quarto website step by step**
- **Markdown for absolute beginners**
- **Quarto with Python for beginners**
