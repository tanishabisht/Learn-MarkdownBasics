# Learn - Markdown basics

This README file contains basic formatting used in Markdown to style text. It introduces new users to various Markdown features. Markdown is a lightweight markup language that allows for the easy formatting of text using plain text syntax.

For more information please visit [this website](https://help.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github).

## Paragraphs and Emphasis
Text can be emphasized by using asterisks (`*`) for *italics*, double asterisks (`**`) for **bold**, and triple asterisks (`***`) for ***bold and italics*** combined. This is useful for highlighting key parts of your text.

## Blockquotes
The `>` character is used to create blockquotes. This is often used for highlighting quotes or important sections of text.

> Practice makes a man perfect

## Links
Links are added using brackets and parentheses. For example, `[Link Text](URL)` creates a clickable text that redirects to the given URL.

- [Headings](https://github.com/tanishabisht/Learn-MarkdownBasics#Headings)
- [Lists](https://github.com/tanishabisht/Learn-MarkdownBasics#Lists)
- [Code](https://github.com/tanishabisht/Learn-MarkdownBasics#Code)
- [Tables](https://github.com/tanishabisht/Learn-MarkdownBasics#Tables)

## Headings

Lets talk about headings. Well it's actucally very simple *more number of hashes smaller the heading you get !!* yes, and the hashes limit to maximum of 6 hashes.

# one hash
## two hash
### three hash
#### four hash
##### five hash
###### six hash

## Lists
Markdown supports ordered (numbered) and unordered (bulleted) lists. It also supports nested lists for more complex structures.

### Ordered list
1. one dot
2. two dot
3. three dot
4. four dot

### Unordered list
- one dash 1
- one dash 2
- one dash 3

### Nested list
1. some main heading
   - sub heading-1
     - some info
     - some more info
   - sub heading-2
     - some info in 2
2. some main heading 2
   - sub heading-1
     - some info
     - some more info
   - sub heading-2
     - some info in 2

the following will be some task list:
[] some task
[x] task done

## Code
Code blocks are created using triple backticks (```). This is essential for repositories that contain code, as it allows the code to be presented in an easy-to-read format.

```js
  function clear() {
    document.form.textview.value="";
  }
```

## Tables
Tables are created using vertical bars (`|`) and dashes (`-`). This can organize data neatly, which is especially useful in technical documentation.

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |


| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |