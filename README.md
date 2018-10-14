__Markdown ist eine leichte und saubere Sprache um seinen Code zu beschreiben. Es wird größtenteils auf Git Repositories verwendet.__

---
### __Anwendungsfälle von Markdown:__
- Readme Files (GitLab, Github, etc)
- Blog Posts und Forum
---
### __Sachen die man in Markdown verwirklichen kann:__
- Headings
- Lists
- Emphasis
- Link
- Code Block
- Images
- Blockquotes
- Horizontal Rules
---
<!-- Headings -->
# Heading 1 |=> \# text 
## Heading 2 |=> \## text 
### Heading 3 |=> \### text 
#### Heading 4 |=> \#### text 
##### Heading 5 |=> \##### text
###### Heading 6 |=> \###### text
---
<!-- Italics -->
*This text* is italic |=> \* text \*

_This text_ is italic |=> \__text \_

---

<!-- Strong -->
**This text** is strong |=> \** text \**

__This text__ is strong |=> \__ text \__

---
<!-- Strikethrough -->
~~This text~~ is strikethrough |=> \~~ text \~~

<!--  Horizontal Rule -->
Horizotal Rule: \___ oder \---
___
---

<!-- Blockquote -->
> This is a Blockquote |=> \> text

<!-- Links -->
[This is a Link](www.url.com)

<!-- Link with hover effect -->
[This is a Link with hover](www.url.com "Hover Text")

<!-- Unordered List -->
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2

<!-- OL -->
1. Item 1
2. Item 2
3. Item 3

<!--Inline Code Block-->
`<p>This is a paragraph</p>`

<!-- IMG -->
![Markdown Logo](https://markdown-here.com/img/icon256.png)

<!-- IMG mit Hover -->
![Markdown Logo](https://markdown-here.com/img/icon256.png "Markdown Logo")

<!-- Github Markdown -->
### __Github Markdown__
<!-- Code Blocks -->
```
npm install

npm start
```

<!-- Specified Code Blocks -->
```javascript
function add(num1, num2){
    return num1 + num2;
}
```

```python
def add(num1, num2):
    return num1 + num2
```

<!-- Tables -->
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

<!-- Task List -->
* [x] Task 1
* [x] Task 2
* [ ] Task 3 