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
* If the reviewer has taken it upon him/herself to check spelling and style (without knowing the
  journal's house style, or without taking into account differences in international and American
  spelling), the author must then defend the spelling and style or change it. But this would be a
  different part of the publishing process and the purview of the copy-editor, not of an anonymous
  peer reviewer.

Thus, **before even fixing any actual problems with the research, authors must spend great time and
energy appeasing reviewers**. (Let's be honest, that is what that is: *appeasing*. Journal
publishing is not all philosophical and scientific discussion.)

But if reviewers are given power to criticize in anonymity and stop publication, they should be held
to basic standards: 
  
  1. give clear criticism
  1. don't be disrespectful
  1. don't cause unnecessary delays in the production process

Anonymity is necessary to curb politics in scientific publishing, but it shouldn't be used as a way
to dump comments without any sense of collegiality to fellow researchers. Some of these people have
an attitude like "I have a PhD, I took 5 minutes to read your paper, here's a stream of
consciousness of opinions (with poor punctuation, misspellings, and no clear order), you figure it
out, I don't care if you're published or not".

But let's be clear, **it's not all the reviewers' fault. Where are the journals in all of this?**
Some journals (not all ...) decide to provide blank fields for comments and don't seem to hold
their peer reviewers to any standard. And some journals (not all ...) assume that it's OK to let
the work fall on authors, copy-editors, and typesetters. 

So some journals (not all ...) should consider a tool like the one proposed in the next section. 


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
## Basic Description of the Tool

A sort of grid/checklist that—although it could be printed on paper—should be conceived as an online
form/tool with controlled fields, dropdown menus, sorting capabilities, etc.

**To critics:**

* Keep in mind that tools like these are already used in the typesetting process. (A checklist/grid
  is attached to the proofs and specific issues are numbered/organized and explained.) This speaks
  to a desire from the production team to actually correct problems in a timely fashion. But, for
  some reason (arrogance), the peer-review process does not require PhDs to explain their
  criticisms ...
* Yes, journals provide ethical guidelines for reviewers. Yes, journals are very "selective" as to
  whom they allow to become a reviewer. But how many journals actually have (or enforce) standards
  for communication?
* This tool can help reviewers too: when authors respond to comments, reviewers have to deal with
  those responses (in some way or another); so if the first batch of comments is clear and
  well-organized, the responses will be clear and well-organized and the reviewer can also save
  time and energy
* A tool such as this might also increase anonymity in a positive sense (it would make it more
  difficult to trace the writing style to a specific person, nationality, or group/institution)
* A tool such as this might facilitate gathering data: journals would only need to take a few more
  steps to be able to collect general statistics. For example, what are the most common errors that
  reviewers are finding in submitted manuscripts (grammar, missing citations, expected topics
  missing from sections, etc)?


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
## Model

| **Lines on Manuscript** | **Type** | **Category** |    **Priority**   | **Comment** |
|:-----------------------:|:--------:|:------------:|:-----------------:|:-----------:|
|           (1)           |    (2)   |      (3)     |         (4)       |     (5)     |
|          ...            |    ...   |      ...     |         ...       |    ...      |
|          ...            |    ...   |      ...     |         ...       |    ...      |
|          ...            |    ...   |      ...     |         ...       |    ...      |

### (1)

Two text fields that allow entering a beginning and an ending line number to mark where the reviewer
has a question or comment.

* Fields should only allow entering numbers (prohibit letters or symbols)
* Presuposes that the manuscript's lines are properly numbered. (In other words, the latex template
  provided by the journal should be well-configured so that every line that the author has control
  over is numbered. It would be disruptive if the reviewer wants to refer to something that is not
  numbered.)
  
### (2)
 
Drop-down menu with options: "Question", "Comment"
 
### (3)
 
Drop-down menu with options: "Grammar", "Spelling", "Punctuation", "Style", "Reference
missing", "Research theory"

* *Grammar*, *Spelling*, *Punctuation*: should automatically set the *Priority* field to "low" 
  (it is possible to change automatically set levels)

* The *Style* option would be used if the reviewer believes that the author was not clear enough and
  the problem is not due to grammar, spelling, or punctuation. For example, if the author wrote
  something like "as discussed in an earlier section, the conclusions will ..."; the reviewer might
  write a comment like "Specify section, add linked reference. Clarify which conclusions are in
  question."
    - *Style*: should automatically set the *Priority* field to "high". The reason for "high" is
       that sometimes when things are revised and written better in terms of style/diction,
       problems that exist with the theory are revised (or disappear) in the process

* The *Reference missing* option would automatically populate a text field with a comment like 
  "Clarify where this concept/result comes from."
      
* The *Research theory* option would be used if the reviewer wants to comment on the theory itself.
  The reviewer could have a comment such as "Smith's concept from 2005 is used but, be aware, that
  this concept was revised by Smith himself in 2008."
    - Should automatically set the *Priority* field to "high"
    - [The option could be called something other than "Research theory" (probably should be). There
      could be other options added to the menu; one that comes to mind in when reviewers say that X
      type of study should have Y type of analysis. Maybe an option called "Concepts missing"?]

### (4)

Drop-down menu with options: "Low", "Medium", "High", "Critical"(?)

### (5)

Text field that becomes larger or shorter depending on options selected. 

* Provisions should be in place so that reviewer doesn't "hack" the system by mis-selecting a
  category on purpose to get the maximum text field that allows for rambling


<!-- ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈***≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ -->
## Sample Usage

| **Lines on Manuscript** | **Type** | **Category** | **Priority** | **Comment** |
|:-----------------------:|:--------:|:------------:| :--------------:  |:-----------:|
|    5                    | Comment  |   Spelling   |   low        | behavior to behaviour| 
|    8                    | Comment  |   Spelling   |   high     | ostensibly to ostensively| 
|    25 | Comment | Style | high | avoid phrases like "as mentioned earlier" |



<!-- ## Things to consider -->

<!-- The links below may be helpful in continuing to design this tool but they seem to make more emphasis on ethics than in how to pragmatically analyse a text and make comments to the author. Read later ... -->

<!-- https://authorservices.wiley.com/Reviewers/journal-reviewers/how-to-perform-a-peer-review/index.html -->

<!-- https://authorservices.wiley.com/Reviewers/journal-reviewers/how-to-perform-a-peer-review/step-by-step-guide-to-reviewing-a-manuscript.html -->

<!-- https://publicationethics.org/guidance/guideline/ethical-guidelines-peer-reviewers -->
