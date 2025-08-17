# Markdown Cheatsheet

A quick reference guide to Markdown syntax, with examples.

---

## Headers

```markdown
# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header
```

**Result:**

# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header

---

## Emphasis

```markdown
*Italic* or _Italic_

**Bold** or __Bold__

***Bold and Italic*** or ___Bold and Italic___

~~Strikethrough~~
```

**Result:**

*Italic* or _Italic_  
**Bold** or __Bold__  
***Bold and Italic*** or ___Bold and Italic___  
~~Strikethrough~~

---

## Lists

**Unordered List:**

```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
* Item 3
```

**Ordered List:**

```markdown
1. First
2. Second
   1. Subitem a
   2. Subitem b
3. Third
```

---

## Links

```markdown
[Link Text](https://example.com)

[Link with Title](https://example.com "Title Text")
```

---

## Images

```markdown
![Alt Text](https://via.placeholder.com/150)

![Alt with Title](https://via.placeholder.com/150 "Optional Title")
```

---

## Blockquotes

```markdown
> This is a blockquote.
>> Nested blockquote.
```

**Result:**

> This is a blockquote.
>> Nested blockquote.

---

## Code

**Inline Code:**  
```markdown
Use `code` for inline.
```

**Block Code:**  
<pre>
```language
function hello() {
  return "Hello, world!";
}
```
</pre>

**Result:**

```javascript
function hello() {
  return "Hello, world!";
}
```

---

## Horizontal Rule

```markdown
---
```

---

## Tables

```markdown
| Header 1 | Header 2 |
|----------|----------|
| Row 1    | Data     |
| Row 2    | Data     |
```

**Result:**

| Header 1 | Header 2 |
|----------|----------|
| Row 1    | Data     |
| Row 2    | Data     |

---

## Task Lists

```markdown
- [x] Completed task
- [ ] Incomplete task
```

**Result:**

- [x] Completed task
- [ ] Incomplete task

---

## Escaping Characters

```markdown
\*This will not be italic\*
```

**Result:**  
\*This will not be italic\*

---

## Footnotes

```markdown
Here is a footnote reference.[^1]

[^1]: Here is the footnote.
```

---

## Automatic Links

```markdown
https://example.com
```

---

## Emoji

```markdown
:smile: :rocket: :+1:
```

**Result:**  
:smile: :rocket: :+1:

---

## More Resources

- [Markdown Guide](https://www.markdownguide.org/)

---
