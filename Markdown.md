# Introduction and Setup

## **Syntax**

### Blockquote

>This is a blockquote.

There should be something between two blockquotes

>"**Don't give up** even if you _fail_"

If you want to create a bigger blockquote then you can use `>` a greater than symbol on each line.

>First line of quote
>
>Second line of quote
>
>Third line of quote
>
>Fourth line of quote

---

A nested blockquote can also be achieved.  

>Landlocked Country
>
> > Nepal is a landlocked country.  
> > It is surrounded by two neighbouring countries.

---

### Bold Text

A **bold** text can be achieved by using
>`**Double asterik** or using __double underscore__` `** **` or `__ __`

---

### Code Blocks

Code blocks are useful when you want to render some reserved symbols or show it as it is.  
It is achieved by using backticks.  
`This is a code block. It can include any symbols: %,&,<,>,+,-,*,_, and many more as needed`

``` text
A multi line code block. It can be achieved by using triple backticks ``` some text ```.
```

This is mainly done for codes, for example: 

```js
function add(int a, int b)
{
    return a + b;
}
```

or,
`Syntax: function function_name(arguments){//codes}`

---

### Headings

Headings are of six types ranging from Heading 1 to all the way to Heading 6.  
Heading are rendered when we use `#` before any text.  
One `#` represent **Heading 1** and Six `######` represent **Heading 6**.

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

---

### Horizontal Rules

Horizontal rules can be achieved by using `***` three asteriks or `___` three underscores or by using `---` three dashes  
To use this there is a need to have blank lines above and below the horizontal lines.

Top line

---

Middle Line

***

Bottom Line

___

End

---

It is best to use dashes for horizontal lines.

---

### Inline Code

Inline code as the name implies can be used for writing codes  
`printf("Hello World !)` in between the text line.

`<!-- Comment--> <h4>Heading 4</h4>`

It can be achieved by using backticks. ``` ` ```  

---

### Italic Text

Italic or emphasis text can be rendered by using `*text*` or `_text_`.  

---

>*Itallic* using asterik  
_Itallic_ using underscore

---

### Links

Links are of two types:

1. Inline Links
2. Reference Links

>Inline links are rendered by using `[Label](URL)`
[Click here to visit Google](https://www.google.com)
>
> Reference links are rendered by using `[Label][Reference link]`
 the reference link is provided in a single place prefered at the bottom or end of the file as follows:

---

Reference Links

[Visit Google][1]  
[Visit Youtube][2]

---

```text
[Reference link]: www.abc.com
[Reference link 2]: www.def.com
```

There is an _advantage_ of using this one as you **only** need to **change the link at one place** if it needs to be changed.  

[//]: # (Reference Links at the bottom)

[1]: https://www.google.com
[2]: https://www.youtube.com

---

### Ordered List

Ordered list is simply a numbered list.  
It is rendered by using _numbers followed by a period_:  

```text
1. Text
2. Text
```

---

Week Days

1. Sunday
2. Monday
3. Tuesday
4. Wednesday
5. Thursday
6. Friday
7. Saturday

---

Nested ordered list can also be made as follows:

You need to provide space between period and the actual text that occurs  
`1.(Space)Text`  
For nested one you preceed the list with a TAB or 4 spaces.

1. Rectangle
    1. Length
    2. Breadth
2. Circle
    1. Diameter
    2. Radius
3. Nepal
    1. Kathmandu
        1. Basantapur

---

### Paragraph

A paragraph doesn't need any special symbols.  
Just type as a normal text.

When you need to start on a new paragraph just create a blank line before your new paragraph

---

Example:  

Introduction Paragraph

Body Paragraph

Conclusion

---

### Unordered List

Unordered list is simply a list with bullet points.  
It can be rendered by using `-` dash, `*` asterik or `+` Plus symbol.  
A checkbox style unordered list can also be created as follows:

```text
Gender
- [x] Male
- [] Female
```

Output:

Gender

- [x] Male
- [ ] Female

---

Vehicles

- Bus
- Car
- Motorcycle
- Cycle
- Moped

A nested unordered list can also be created:

- Nepal
  - Kathmandu
    - Basantapur

> A common approach is to give 2 spaces before an unordered list items.

---

## Github Flavored Markdown

### Strikethrough

A strike through text is achieved by using two tilde `~~` symbol.

Normal Text  
~~Striked Text~~

It can be used to denote some changes or depreciated items.

Example: *Old Twitter still points to its new site*  
~~Visit Twitter [Twitter](https://www.twitter.com)~~  
Visit X (Renamed Twitter) [X](https://www.x.com)

---

### Syntax Highlighting

Syntax highlighting is rendered by using a code block.  
It is achieved by using three backticks
` ```js Codes``` `

`js` defines what language is being used and highlights the code respectively.

Example:  

```js
// Code written in JavaScript
let a = 2;
let b = 3;
let c = a + b;

console.log(c);
```

```c
// Code written in C
int a = 2;
int b = 3;

printf(a+b);
```

---

### Tables

Tables can also be rendered by using markdown.  
In order to create a table we need to use a pipe symbol `|` and three or more hyphen `---`

| S.N | Names  | Address   |
| ----| ------ | ----------|
| 1.  | Ram    | kathmandu |
| 2.  | Hari   | Bhaktapur |
| 3.  | Shyam  | Lalitpur  |

| Column 1 | Column 2 | Column 3 |
|---------:|:---------:|:---------|
| A | B | C |
| D | E | F |

---

Table can have allignment also: notice how the second table is aligned `:` colon is used to trigger the alignment of the table.

```text
| :--- | -> Triggers Left alignment
| :---: | -> Triggers center alignment
| ---: | -> Triggers right alignment
```

---
