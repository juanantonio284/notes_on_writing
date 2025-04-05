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
## Other things

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
### Block quotations

#### Basic method `>`

> “A designer trained to think with both penetration and scope will find solutions, not alone for problems arising in daily routine, or for development of better ways of production, but also for all problems of living and working together. There is design in family life, in labor relations, in city planning, in living together as civilized human beings.” — Laszlo Moholy-Nagy

#### Multiple Paragraphs and nested quotes

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
### Image

The image below is found at https://www.markdownguide.org/assets/images/tux.png

![tux](https://www.markdownguide.org/assets/images/tux.png)

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Code

To denote a word or phrase as code, enclose it in "tick marks". 
This is the grave accent symbol `` ` ``, Unicode `U+0060`, (the key below the `esc` key on most 
keyboards).

Example: at the command prompt type `ls`. 

If the word or phrase you want to denote as code includes one or more tick marks, you can escape it
by enclosing the word or phrase in double tick marks. 

Example: this is the grave accent symbol `` ` ``

To create a code block, aka a listing, put it within a tick "fence". Some build systems also support
syntax highlighting:

```html
<html>
    <head>
    </head>
</html>
```

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Tables

#### Simple table

The characteristics of the table below are:

* a vertical line `|` is used to separate the words. (It's on your keyboard and has Unicode
  `U+007C`)

* alignment of the text does not matter

* the top row (with the column names) is separated from the column content by the `| ---- |`
  construction. That is a vertical line `|` followed by a space ` `, many hyphens `-`, another
  space ` ` and another vertical line `|`. It does not matter how many hyphens you put in

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

#### Table with alignment, and formatting

The characteristics of the table below are:

* the same as the characteristics of the "simple table" above

* uses bold and italic formatting

* a colon `:` in the `header/content separator` defines how the text is aligned

    - You probably don't need one to align to the left (that is the default) but I like it as it
      makes you notice that the other columns have different alignment

* it is nicely formatted in the text file (it is square and looks more table-like)

    * how it looks in the text doesn't change how it's rendered but it might be nice (there are
      online markdown table generators that can do this and much more)

| text aligned left | text centered | text aligned right |
|:------------------|:-------------:|-------------------:|
| **bold text**     |  normal text  |      *italic text* |
| **bold text**     |  normal text  |      *italic text* |


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
### Footnotes

Here's a simple footnote,[^1] and here's a longer one [^bignote] (a nice feature is that you can
give any name you want to the note). You can point to the same note in different places [^1]. 

<!-- The big footnote is indented which makes it render funny (a fence block with nothing in it is created) -->

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code inside of it.
    Indent paragraphs to include them in the footnote.
    `{ my code }`
    Add as many paragraphs as you like.
    

<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
## Lines

Below is a 50 character line made with the EM Rule `—` character

——————————————————————————————————————————————————

Below is a 25 character line made with the EM Rule `—` character

—————————————————————————

Below is a 12 character line made with the EM Rule `—` character

————————————

Below is a horizontal rule made with three hyphens `-`

---

Below is a horizontal rule made with 100 hyphens `-`

----------------------------------------------------------------------------------------------------

This is the last line of the file; below you should see a line separating footnotes from the regular
text.
