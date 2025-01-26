---
Title: "Markdown Documentation"
Description: "Detailed information about Markdown, with examples and descriptions."
---

# Markdown Documentation
`Markdown` is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by John Gruber in 2004, Markdown is now one of the world's most popular markup languages.

Here's a quick guide to some of the basic Markdown syntax with examples

## Headings
Use `#` for headings. The number of `#` signs indicates the level of the heading.
```Markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
### Results:
> # Heading 1
> ## Heading 2
> ### Heading 3
> #### Heading 4
> ##### Heading 5
> ###### Heading 6

## Bold and italic fonts
**Bold:** `**text**` or `__text__`

*Italic:* `*text*` or `_text_`

***Bold and Italic:*** `***text***` or `___text___`
```Markdown
*italic* or _italic_
**bold** or __bold__
***bold and italic*** or ___bold and italic___
```

## Lists
+ **Unordered list:** Use `*`, `+` or `-` for bullet points.
  ```Markdown
    * List item 1
    * List item 2
        * List subitem 1
        * List subitem 2
    * List item 3
  ``` 
    ### Results
    * List item 1
    * List item 2
        * List subitem 1
        * List subitem 2
    * List item 3

+ **Ordered list:** Use numbers followed by a period `1.` or `1)`
  ```Markdown
  1. List item 1
  2. List item 2
     1) List subitem 1
     2) List subitem 2
  3. List item 3
  ```
  ### Results
  1. List item 1
  2. List item 2
     1) List subitem 1
     2) List subitem 2
  3. List item 3

## Links
Use square brackets for the text and parentheses for the URL
```Markdown
[GitHub](https://www.github.com/)
```
### Result
[GitHub](https://www.github.com/)

## Images
Use an exclamation mark followed by square brackets for the alt text and parentheses for the URL
```Markdown
![Macro Flowers](images/flowers.jpg)
```
### Result
![Macro Flowers](images/flowers.jpg)

## Code
**Inline code:** use backticks ``` ` ```.
```Markdown
Same text and `inline code` here.
```
**Result:** Same text and `inline code` here.

**Code blocks:** use three backticks or indent the code block code by four spaces.
```dart
abstract class Animal {
  void move();
}

class Dog extends Animal {
  void move() {
    print("Dog move!");
  }
}

class Cat extends Animal {
  void move() {
    print("Cat move!");
  }
}

void main() {
  Dog dog = new Dog();
  var cat = new Cat();

  dog.move();
  cat.move();
}
```
## Blockquotes
Use `>` for blockquotes.
```Markdown
> This is a blockquote.
```
### Result
> This is a blockquote.

## Tables
```Markdown
| Header 1 | Header 2 | Header 3 |
|:---------|:--------:|---------:|
| Row 1    | Row 1    | Row 1    |
| Row 2    | Row 2    | Row 2    |
| Row 3    | Row 3    | Row 4    |
| Row 4    | Row 4    | Row 4    |
```
### Result
| Header 1 | Header 2 | Header 3 |
|:---------|:--------:|---------:|
| Row 1    | Row 1    | Row 1    |
| Row 2    | Row 2    | Row 2    |
| Row 3    | Row 3    | Row 3    |
| Row 4    | Row 4    | Row 4    |
