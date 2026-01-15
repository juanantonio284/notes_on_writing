# Model Peer-Review Rubric

[July 31, 2025]

## Introduction

In the peer-review process, reviewers are often given a blank field to write anything about
manuscripts under consideration. Maybe some journals have quality control so that peer-reviewers
actually take the time to understand what they're reading and try to provide organized, insightful,
comments but, **in the real world, reviewers are largely unchecked**. And this results in the
paper's authors being left with non-trivial, time-consuming, tasks. 

For example:

* If the reviewer writes poorly (punctuation, grammar, organization), the author has the task of
  trying to understand what the reviewer meant. 
* If the reviewer is not clear about what's more or less important, the author has to infer what
  should be prioritized in the response. 
* If the reviewer is rude, the author has to separate the insult from the real criticism (if there
  is one) and answer as politely and technically as possible.
* If the reviewer was too busy to read in detail, the author must clarify to the reviewer that—for
  example—a concept was already explained in an earlier section, or that a certain word/concept is
  a regular "dictionary" word and not a theory or piece of data that requires a citation or going
  in depth on a theory.
* If the reviewer has taken it upon himself to check style or spelling (without knowing the
  journal's house style, or without taking into account differences in international and American
  spelling), the author must then defend the spelling/style or change it. (Even though this belongs
  in a different part of the publishing process and is the purview of the copy-editor, not of an
  anonymous peer reviewer.)

Thus, **before even fixing any actual problems with the research, authors must spend great time and
energy appeasing reviewers**. (Let's be honest, journal publishing is not all philosophical and
scientific discussion. There is a lot of *appeasing* and just trying to get to the next stage.)

But if reviewers are given power to criticize in anonymity and stop publication, they should be held
to basic standards: 
  
  1. Give clear criticism
  1. Don't be disrespectful
  1. Don't cause unnecessary delays in the production process

Anonymity is necessary to curb politics in scientific publishing, but it shouldn't be used as a way
to dump comments without any sense of collegiality to fellow researchers. Some of these people have
an attitude like "I have a PhD, I took 5 minutes to read your paper, here's a stream of
consciousness of opinions (with poor punctuation, misspellings, and no clear order), you figure it
out, I don't care if you're published or not".

Let's be clear, **it's not all the reviewers' fault. Where are the journals in all of this?** Some
journals (not all ...) decide to provide blank fields for comments and don't seem to hold their
peer reviewers to any standard. And some journals (not all ...) assume that it's OK to let the work
fall on authors, copy-editors, and typesetters. So some journals (not all ...) should consider a
tool like the one proposed in the next section. 


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
## Basic Description of the Tool

A sort of grid/checklist that should be conceived as an online form/tool with controlled fields,
dropdown menus, sorting capabilities, etc.

**To critics:**

* Keep in mind that tools like these are already used in the typesetting process. (A checklist/grid
  is attached to the proofs and specific issues are numbered/organized and explained.) This speaks
  to a desire from the production team to actually correct problems in a timely fashion. But, for
  some reason (arrogance), the peer-review process does not require PhDs to explain their
  criticisms ...
* Yes, journals are very "selective" as to whom they allow to become a reviewer; yes, journals
  provide guidelines for reviewers. But selection of reviewers is related to knowledge of the
  subject matter, and it seems guidelines are mostly abstract. How many journals actually have and
  enforce standards and procedures for communication from reviewer to author?
* This tool can help reviewers too: at some point reviewers will receive the author's responses; so
  if the first batch of reviewer comments is clear and well-organized, the author's responses will
  be clear and well-organized. Thus the reviewer can also save time and energy
* A tool such as this might also increase anonymity in a positive sense (it would make it more
  difficult to trace the writing style to a specific person, group, nationality)
* A tool such as this might facilitate gathering data: journals would only need to take a few more
  steps to be able to collect general statistics. It would be simple to answer questions such as
  "what are the most common errors that reviewers are finding in submitted manuscripts
   (grammar, missing citations, expected topics missing from sections, etc)"?


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
## Model

| **Lines on Manuscript** | **Type** | **Category** |    **Priority**   | **Comment** |
|:-----------------------:|:--------:|:------------:|:-----------------:|:-----------:|
|          (1)            |    (2)   |      (3)     |         (4)       |    (5)      |
|          ...            |    ...   |      ...     |         ...       |    ...      |
|          ...            |    ...   |      ...     |         ...       |    ...      |
|          ...            |    ...   |      ...     |         ...       |    ...      |

### (1)

Two text fields that allow entering a beginning and an ending line number to mark where the reviewer
has a question or comment.

* Fields should only allow entering numbers (prohibit letters or symbols)
* Presuposes that the manuscript's lines are properly numbered. (In other words: the latex template
  provided by the journal should be well-configured so that every line that the author has control
  over is numbered. It would be disruptive if the reviewer wants to refer to something that is not
  numbered—or if the reviewer refers to something that the author cannot change.)
  
### (2)
 
Drop-down menu with options: `Question`, `Comment`
 
### (3)
 
Drop-down menu with options: `Grammar`, `Spelling`, `Punctuation`, `Style`, `Reference
missing`, `Research theory`

* `Grammar`, `Spelling`, `Punctuation`: should automatically set the `Priority` field to `low` 
  (it is possible to change automatic settings)

* The `Style` option would be used if the reviewer believes that the author was not clear enough and
  the problem is not due to grammar, spelling, or punctuation. For example, if the author wrote
  something like "`As discussed in an earlier section, the conclusions imply that ...`"; the
  reviewer might write a comment like "`Specify section, add linked reference. Clarify which
  conclusions are in question. If this was already discussed, why reiterate? Do you mean "as
  touched upon in section X"? (Revise)`."
    - `Style`: should automatically set the `Priority` field to `high`. The reason for `high` is
      that when things are revised and written better in terms of style/diction, problems with the
      theory are often revised (and may disappear) in the process.

* The `Reference missing` option would automatically populate a text field with a comment like  
  "`Clarify where this concept/result comes from.`" but this field could be changed by the reviewer
      
* The `Research theory` option would be used if the reviewer wants to comment on the theory itself.
  The reviewer could say something like "`Smith's concept from 2005 is used but, be aware, that this
    concept was revised by Smith himself in 2008.`"
    - Should automatically set the `Priority` field to `high`
    - [The option could be called something other than "Research theory" (it probably should be).
      There could be other options added to the menu. There could be one that deals with the common
      case when reviewers say that X type of study should have Y type of analysis. (They mean to
      say that the traditional, rigorous, way of doing it is not being followed.) This option could
      be called "`Concepts missing`"?]

### (4)

Drop-down menu with options: `Low`, `Medium`, `High`, `Critical`(?)

### (5)

Text field that becomes larger or shorter depending on options selected. 

* Provisions should be in place so that reviewer doesn't "hack" the system by mis-selecting a
  category on purpose to get the text field that allows for maximum rambling


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
## Sample Usage

| **Lines on Manuscript** | **Type** | **Category** |    **Priority**   | **Comment**              |
|:-----------------------:|:--------:|:------------:| :--------------:  |:------------------------:|
|    5                    | Comment  |   Spelling   |        low        | behavior to behaviour    | 
|    8                    | Comment  |   Spelling   |        high       | ostensibly to ostensively| 
|    25                   | Comment  |    Style     | high | avoid phrases like "as mentioned earlier" |


<!-- ## Things to consider -->

<!-- The links below may be helpful in continuing to design this tool but they seem to make more emphasis on ethics than in how to pragmatically analyse a text and make comments to the author. Read later ... -->

<!-- https://authorservices.wiley.com/Reviewers/journal-reviewers/how-to-perform-a-peer-review/index.html -->

<!-- https://authorservices.wiley.com/Reviewers/journal-reviewers/how-to-perform-a-peer-review/step-by-step-guide-to-reviewing-a-manuscript.html -->

<!-- https://publicationethics.org/guidance/guideline/ethical-guidelines-peer-reviewers -->
