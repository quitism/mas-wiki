---
title: Template (for theming purposes)
description: 
published: true
date: 2026-03-14T09:36:20.079Z
tags: 
editor: markdown
dateCreated: 2026-03-14T09:31:55.092Z
---

# h1: the big boss
## h2: the lieutenant 
### h3: the sergeant
#### h4: the corporal
##### h5: the private
###### h6: the recruit

---

## basic styling
this is **bold**, this is *italic*, and this is ~~strikethrough~~.
you can also do ***combined emphasis*** if you're feeling fancy.
need a line break?  
two spaces at the end of a line does the trick.

---

## lists (the essentials)
### unordered
- item alpha
- item bravo
  - sub-item (nested)
  - another sub-item
- item charlie

### ordered
1. first step
2. second step
   1. sub-step 2a
   2. sub-step 2b
3. third step

### task list
- [x] completed task
- [ ] pending task
- [ ] task with `inline code` inside

---

## blockquotes & wiki.js alerts
> standard blockquote for regular quotes or citations.

wiki.js lets you style these using classes:

> **info alert**: use this for general helpful tips.
{.is-info}

> **success alert**: everything is going great!
{.is-success}

> **warning alert**: better watch out for this.
{.is-warning}

> **danger alert**: critical error or stop right there.
{.is-danger}

---

## code & syntax highlighting
here is some `inline.code()` for your sentences.

```javascript
// fenced code block
function greet(name) {
  console.log(`hey ${name}, let's theme this!`);
}
greet('sytesn');