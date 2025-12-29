# Git By Example Anton

A guide to git led by example.

## Details

**website:** https://antonz.org/git-by-example/
**visit date**: 27-nov-2025

## Commands

### Change branch name

#### 1. Rename the local branch

If you are currently on the `master` to `main`

```bash
git branch -m master main
```

#### 2. Push the new branch to the remote

You need to push the new `main` branch to the remote repo.

```bash
git push -u origin main
```

#### Deeper Sub-section (H4 Header)

## Section 2: Text Formatting

*   **Bold text** with `**asterisks**` or `__underscores__`.
*   *Italic text* with `*single asterisks*` or `_single underscores_`.
*   ***Bold and Italic text*** can be combined.
*   ~Strikethrough text~ with `~~tilde symbols~~` (GFM extension).

## Section 3: Lists

### Unordered List

*   Item 1
*   Item 2
    *   Nested item 2a (indent with spaces or tabs).
    *   Nested item 2b

### Ordered List

1.  First item
2.  Second item
3.  Third item
    *   You can nest bullet points within ordered lists.

## Section 4: Links and Images

You can create [inline links](www.markdownguide.org).

Images use a similar syntax, preceded by an exclamation mark:
![Alt text describing the image](https://octodex.github.com/images/minion.png "Optional title text")

## Section 5: Code Blocks

Inline code snippets are wrapped in backticks: `const example = "hello";`.

Fenced code blocks use three backticks and can specify the language for syntax highlighting:

```python
def greet(name):
    print(f"Hello, {name}!")

greet("World")
