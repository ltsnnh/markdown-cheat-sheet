
# Markdown Guide

I really like using Markdown.  
I think I'll use it to format all of my documents from now on.

---

## Basic Syntax

### Emphasis

I just love **bold text**  
But I love *italicized text* too  
This text is very ***important***

### Blockquote

>This is block quote.
>
>Dorothy followed her through many of the beautiful rooms in her castle.  
>The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
>>*Everything* is going according to **plan**.

### List

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

- 1997\. A great year!
- I think 1999 was second best.

* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

### Code Block

At the command prompt, type `nano`.

``Use `code` in your Markdown file.``

    int main() {
        return 0;
    }

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

### Images

[![Markdown logo](https://live.staticflickr.com/65535/51911691444_48acb51ca9_b.jpg "Markdown is simple!")](https://flic.kr/p/2n6fZhQ)

### Links

My favorite search engine is [Goole](https://www.google.com/ "The best search engine")  
***<https://www.markdownguide.org>***

---

## Extended Syntax

### Table and Alignment

| Syntax | Description | Test Text |
| :--- | :----: | ---: |
| Header | Title | Here's this |
| Paragraph | Text | And more |

### Fenced Code Block and Highlight

```c
int main() {
    return 0;
}
```

### Strikethrough

~~The world is flat.~~

### Task Lists

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Subscript and Superscript

H<sub>2</sub>O  
X<sup>2</sup>

### Disabling Automatic URL Linking

`http://www.example.com`

---

## Hacks

### Underline

Some of these words <ins>will be underlined</ins>.

### Indent (Tab)

&nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.

### Image Size

<img src="https://live.staticflickr.com/65535/51911691444_48acb51ca9_b.jpg" width="200" height="100">

### Table Formatting

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragragh. <br><br> Second paragraph. |

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |

### Video

[![Arduino blink led](https://img.youtube.com/vi/KA-P1ZKnn8I/0.jpg)](https://www.youtube.com/watch?v=KA-P1ZKnn8I)
