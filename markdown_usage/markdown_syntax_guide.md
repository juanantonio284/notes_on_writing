# Markdown Syntax Guide

This is heavily based on the cheat-sheet found [here][md_guide_cs]. (See separate file for
information on the syntax used to include links in a document.)

[md_guide_cs]: https://www.markdownguide.org/cheat-sheet

## Second level header

This sentence---beginning at the T and ending at the period---has 100 characterss, including spaces.
This sentence---beginning at the T and ending at the period---has 100 characterss, including spaces.

### Third level header

This sentence---beginning at the T and ending at the period---has 100 characterss, including spaces.
This sentence---beginning at the T and ending at the period---has 100 characterss, including spaces.

#### Fourth level header

**This sentence is in bold text so you can compare it to the header** 
This sentence---beginning at the T and ending at the period---has 100 characterss, including spaces.


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ --> 
## Part 2: Other Things

### Italic, bold, and both 

*This* word is in italics, **this** one is bolded, ***this*** is both

### Strikethrough

~~This text should be "strikedthrough".~~

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Small text

This is normal text. <small> This text should be smaller, it uses the `<small> </small>` tags from
`HTML` and does not work in every build system.</small>

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Line break

A line with a break ends in two spaces and then a return. This line has a line break.  
And thus **this text** you're reading should be on a different line; but this line does not have 
break.
So **this text**, which is on a separate line in the text file, it renders in the same line in the
html (because the line above does not end in two spaces.)

Consider setting these options in *Sublime Text* to avoid problems

```JSON
"trim_automatic_white_space": false,
"trim_trailing_white_space_on_save": false,
```

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Definition List

term
: definition

Science
: the systematic study of the structure and behavior of the physical and natural world through
  observation, experimentation, and the testing of theories against the evidence obtained.

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Checklist

- [x] checked item
- [ ] unchecked item

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Ordered Lists

To create an ordered list, add line items with numbers followed by periods.

1. First item
2. Second item
3. Third item
4. Fourth item

The numbers don't have to be in numerical order, but the list should start with the number one. In
the list below, all the items start with `1.` but, when rendered, you see `1,2,3,4`.

1. First item
1. Second item
1. Third item
1. Fourth item

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Nesting List Items

To nest line items in an ordered list, indent the items four spaces or one tab.

1. First Item

* bullet not indented 

    * bullet indented (four spaces)
    
        - bullet indented 2 (eight spaces)

2. Second item

3. Third item
    1. Indented item 1 (entered as `1.`, rendered as `i`)
    2. Indented item 2 (entered as `2.`, rendered as `ii`)

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Footnotes

Here's a simple footnote[^note_1]. Here is another note [^another]. Here's a longer one[^test]. This
is done with regular markdown code. You can point to the same note in different places [^note_1]. 

[^note_1]: This is the first footnote.

[^another]: This note is named `[^another]`, yet, it appears numbered. The numbering is given in relation to where the note is in the text.

[^test]: 
This note has multiple paragraphs and code. 

    This is paragraph 1: Indent paragraphs (one tab or four spaces) to include them in the footnote; put a blank line between paragraphs.

    This is paragraph 2, it has code: `{ my code }`

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Images

The image below is found online. It can be seen in the rendered html file when opened in a browser
(internet connection needed) but cannot be seen in the original text file. (Sublime Text with
the *Markdown Images* package allows rendering images in your local directories but does not seem
to work with links.)

Note that not every build system will show the images as you expect them to ...

#### Full Size

![peace_chem_online](https://images.masterworksfineart.com/product/peace-through-chemistry-i-1970-c-96/roy-lichtenstein-lithograph-peace-through-chemistry-i-1970-for-sale.jpg)

#### Half Size

Markdown syntax `![image_title](link to image)` does not display the image properly on GitHub.

Instead, HTML syntax was used (see source code):

[
<img
 src="https://images.masterworksfineart.com/product/peace-through-chemistry-i-1970-c-96/roy-lichtenstein-lithograph-peace-through-chemistry-i-1970-for-sale.jpg" 
 width=50%
 title="This is the title of the image (written in the title field)"
 />
](https://images.masterworksfineart.com/product/peace-through-chemistry-i-1970-c-96/roy-lichtenstein-lithograph-peace-through-chemistry-i-1970-for-sale.jpg)

But note that the image above contains a link to another website, and that link is set up using
Markdown syntax surrounding the HTML syntax: `[ HTML code here ](https...)`. If you do not want
there to be a link, do not surround the HTML with the markdown, as below:

```html
<img
 src="https://images.masterworksfineart.com/product/peace-through-chemistry-i-1970-c-96/roy-lichtenstein-lithograph-peace-through-chemistry-i-1970-for-sale.jpg" 
 width=50%
 title="This is the title of the image (written in the title field)"
 />
```

<!-- see these pages for more hints -->
<!-- https://gist.github.com/stevecondylios/dcadb4fc73e63f27a3bbcf17e52058bf -->
<!-- https://github.com/rnag/GMU-Daily-Permit-Automation/blob/main/README.md -->

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Code

To denote a word or phrase as code, enclose it in "tick marks". 
This is the grave accent symbol `` ` ``; the key below the `esc` key on most keyboards (`U+0060`).

* Example: at the command prompt type `ls`. 

If the word or phrase you want to denote as code includes one or more tick marks, you can escape it
by enclosing the word or phrase in double tick marks. 

* Example: this is the grave accent symbol `` ` ``

To create a *code block*, aka a *listing*, put it within a tick "fence" (some build systems also
support syntax highlighting). 

* Example: html code

    ```html
    <html>
        <head>
        </head>
    </html>
    ```

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Tables

#### Simple table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

Characteristics of the table above:

* a vertical line `|` (`U+007C`) is used to separate the words. (This should be on a standard
  keyboard above the `Enter` key.)

* alignment of the text does not matter

* the top row (with the column names) is separated from the column content by the `| ---- |`
  construction. That is a vertical line `|` followed by a space ` `, many hyphens `-`, another
  space ` ` and another vertical line `|`. (It does not matter how many hyphens you put in)

#### Table with alignment and formatting

| text aligned left | text centered | text aligned right |
|:------------------|:-------------:|-------------------:|
| **bold text**     |  normal text  |      *italic text* |
| **bold text**     |  normal text  |      *italic text* |

Characteristics of the table above:

* the same as the characteristics of the "simple table" above

* uses bold and italic formatting

* a colon `:` in the `header/content separator` defines how the text is aligned

    - You probably don't need one to align text to the left (that is the default) but I like using
      it as it makes you notice that the other columns have different alignment

* it is easier to read in the text file (it is square and looks more table-like)

    * how it looks in the text doesn't actually change how it's rendered


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ --> 
## Part 3: Block Quotations

### Basic method (using only the `>` symbol)

> "A designer trained to think with both penetration and scope will find solutions, not alone for
   problems arising in daily routine, or for development of better ways of production, but also for
   all problems of living and working together. There is design in family life, in labor relations,
   in city planning, in living together as civilized human beings." — Laszlo Moholy-Nagy

### Multiple Paragraphs and nested quotes

To create a block quotation with multiple paragraphs, put a `>` in the empty line between
paragraphs. To nest a quote, put a `>>` before the part you want to nest. 

> I—even [while] serving on the Court—have opinions about the results of decisions. But Justices
  aren't deciding cases—no judge is deciding a case— in order to impose a policy result; they're
  trying to make their best effort to determine what the law requires, what the constitution
  requires, what statutes require. 
>
> I would say that it's perfectly fair game to say that you dislike the results of a case; it's also
  perfectly fair game to say that the Court got it wrong—but I think if you're going to make the
  latter claim that the Court got it wrong, you have to engage with the Court's reasoning first.
  And I think you should read the opinion and say:
> 
>> *"Does this read like something that was purely results driven and designed to impose the policy
     preferences of the majority? Or does this read like it actually is an honest effort, a
     persuasive effort"*—even if one you ultimately don't agree with—*"to determine what the
     constitution and precedent requires, as applied to a particular problem at hand?"*
>
> ... The Court—and I'm saying "The Court" but what I'm saying is actually equally applicable to all
      Federal Courts—is accountable in its reasoning. I think, actually, this is the measure, I
      think this is the standard, by which the American people should judge the Court: 
>
>> *"Is the Court laying out its reasoning? Is its reasoning that of a political or legislative
     body, or is its reasoning judicial? Is its reasoning, a reasoning from all the traditional
     tools that inform our body of precedent?*" (You know, prior cases, statutes, The Constitution
     itself ...)
>
> The way that justices write opinions in measured tomes, I think is important ... [I think it's
  also important how the justices] relate to one another. The Court, truly, is very collegial; even
  when we disagree with one another about the results of the case, how a case should be decided,
  the reasoning of the case. I've been honoured to be part of the institution and I have been
  really grateful for the tremendous collegiality and respect that the members of the Court show
  for one another and I think Americans would all be better off if we all showed that level of
  respect even for those with whom we disagree. — Amy Coney Barrett


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
## Part 4 Lines

Below is a 50-character line made with the EM Rule `—` character (`U+2014`) 

——————————————————————————————————————————————————

Below is a 25-character line made with the EM Rule `—` character (`U+2014`) 

—————————————————————————

Below is a 12-character line made with the EM Rule `—` character (`U+2014`)

————————————

Below is a "horizontal rule" made with three hyphens `-`

---

Below is a "horizontal rule" made with 100 hyphens `-`

----------------------------------------------------------------------------------------------------

This is the last text line of the file; it is regular text. Below you should see a horizontal rule
that was automatically created in the render process to separate the footnotes from the regular
text.
