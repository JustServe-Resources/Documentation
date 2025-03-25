# AsciiDoc Style Guide

----

## 1. General guidelines

* Follow AsciiDoc syntax standards.
* Maintain consistent formatting.
* Use proper structure and concise writing for readability.

## 2. Document structure

### 2.a Headers
* Use consecutive `=` symbols for header levels:
```
= Document header (Level 0)
== Section header (Level 1)
=== Subsection header (Level 2)
==== Sub-subsection header (Level 3)
... and so on
```
* Use short and descriptive headings.
* Use a blank line before each header.

### 2.b Paragraphs
* Separate paragraphs with a blank line.
* Do not indent paragraphs.

### 2.c Document attributes
Place the email at the top of the file, under the document title.
```
= Document Title
:email: your.email@company.com
```

## 3.Text format

### 3.a Emphasis
* Use `*<text>*` for **strong emphasis**.
* Use `_<text>_` for _italics_.
* Use two backticks `(``)` for `monospace`.

### 3.b Lists
* For **unordered** lists, use `*` for each item and indentation to create nested items. For example:
```
* First item
  ** Sub-item
* Second item
```
* For **ordered** lists, use `.` for each item and indentation to create nested items. For example:
```
. First item
. Second item
    .. Sub-item
```

### 4. Links
* For external links, use `{url}[Link text]` or `link:{url}[Link text]`\
For example:
`https://example.com[Example]` or `link:https://example.com[Example]`

* For internal links within the document, use `<<section-id, Section Title>>`, where `section-id` is a document element with an identifier.

### 5. Code Blocks

* Use three backticks `(```)` or `[source]` block with language specification.
For example:
```
[source,python]
----
def hello_world():
print("Hello, World!")
----
```

### File extensions

* Use `.adoc` as AsciiDoc file extensions.
