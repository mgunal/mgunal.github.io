---
layout: post
title: Technical Writing
---

Here I'm sharing my notes on the [Google's Technical Writing Course](https://developers.google.com/tech-writing/)

##  Consistent Terminology

Using terminology, abbreviations and acronyms consistently is very important for the person reading your documentation
same goes for equations, if you use u,v for texture coordinates, throughout the document these coordinates should be named u/v not px,py.

###   Defining new or unfamiliar terms

When writing or editing, learn to recognize terms that might be unfamiliar to some or all of your target audience. When you spot such a term, take one of the following two tactics:

If the term already exists, link to a good existing explanation. (Don't reinvent the wheel.)
If your document is introducing the term, define the term. If your document is introducing many terms, collect the definitions into a glossary.

###   Acronyms

On the initial use of an unfamiliar acronym within a document or a section, spell out the full term, and then put the acronym in parentheses. Put both the spelled-out version and the acronym in boldface.
Do not cycle back-and-forth between the acronym and the expanded version in the same document.

Here are the guidelines for acronyms:

- Don't define acronyms that would only be used a few times.
- Do define acronyms that meet both of the following criteria:
  - The acronym is significantly shorter than the full term.
  - The acronym appears many times in the document.

###   Disambiguate pronouns

Pronoun must clearly indicate the noun, when it doubt use the noun instead.

Consider the following pronoun guidelines:

Only use a pronoun after you've introduced the noun; never use the pronoun before you've introduced the noun.
Place the pronoun as close as possible to the referring noun. In general, if more than five words separate your noun from your pronoun, consider repeating the noun instead of using the pronoun.
If you introduce a second noun between your noun and your pronoun, reuse your noun instead of using a pronoun.

Replace this or that with the appropriate noun.
Place a noun immediately after this or that.

##   Active voice vs Passive Voice

The vast majority of sentences in technical writing should be in active voice.
Good sentences in technical documentation identify who is doing what to whom.
Humans are already uses active voice mentally, and converts passive voice to active whilst understanding
I see more active voice used on the papers too because it doesn't hide the actor and gives more credibility.

##   Clarity

In technical writing, clarity takes precedence over all other rules. This unit suggests a few ways to make your sentences beautifully clear.

Choose strong verbs like omit, specify, generate, trigger etc to write more engaging sentences.

Reduce There is/ There are to remove the genericness of the sentence. Sentences with there is/ there are sounds like passive voice and is not engaging as clear, active sentences.

There are parameters called kw,kh in the design to set the maximum kernel size
vs
Parameters kw, kh determines the maximum kernel size in the design.

##   Minimize certain adjectives and adverbs

Writer should provide subjective data to the readers, writing something runs much faster doesn't provide much data and can be misleading, author should write it runs 2x faster instead. Which provides accuracy to the reader on how much faster the process runs.

##    Short Sentences

>If I had more time, I would have written a shorter letter.
>Blaise Pascal

Short sentences communicate more powerfully than long sentences, and short sentences are usually easier to understand than long sentences.
Focus each sentence on a single idea, thought, or concept. Just as statements in a program execute a single task, sentences should execute a single idea.
Inside many long technical sentences is a list yearning to break free.
When you see the conjunction or in a long sentence, consider refactoring that sentence into a bulleted list. When you see an embedded list of items or tasks within a long sentence, consider refactoring that sentence into a bulleted or numbered list.

Many sentences contain filler—textual junk food that consumes space without nourishing the reader. Eliminate them.

Subordinate clauses modify the idea in the main clause. As the name implies, subordinate clauses are less important than the main clause.

That and which both introduce subordinate clauses. In the United States, reserve which for nonessential subordinate clauses, and use that for an essential subordinate clause that the sentence can't live without.

## Lists and Tables

###    Lists

Technical readers generally love lists. Therefore, when writing, seek opportunities to convert prose into lists.
What separates effective lists from defective lists? Effective lists are parallel; defective lists tend to be nonparallel.
That is, all items in a parallel list match along the following parameters:
grammar
logical category
capitalization
punctuation

###    Tables

Analytic minds tend to love tables. Given a page containing multiple paragraphs and a single table, engineers' eyes zoom towards the table.

Consider the following guidelines when creating tables:

Label each column with a meaningful header. Don't make readers guess what each column holds.
Avoid putting too much text into a table cell. If a table cell holds more than two sentences, ask yourself whether that information belongs in some other format.
Although different columns can hold different types of data, strive for parallelism within individual columns. For instance, the cells within a particular table column should not be a mixture of numerical data and famous circus performers.

###   Introduce each list and table

We recommend introducing each list and table with a sentence that tells readers what the list or table represents. In other words, give the list or table context. Terminate the introductory sentence with a colon rather than a period.

Although not a requirement, we recommend putting the word following into the introductory sentence. For example, consider the following introductory sentences:

The following list identifies key performance parameters:

Take the following steps to install the Frambus package:

The following table summarizes our product's features against our key competitors' features:

##  Paragraphs

>The work of writing is simply this: untangling the dependencies among the parts of a topic, and presenting those parts in a logical stream that enables the reader to understand you.

Write a great opening sentence

The opening sentence is the most important sentence of any paragraph. Busy readers focus on opening sentences and sometimes skip over subsequent sentences. Therefore, focus your writing energy on opening sentences.

Focus each paragraph on a single topic

A paragraph should represent an independent unit of logic. Restrict each paragraph to the current topic. Don't describe what will happen in a future topic or what happened in a past topic. When revising, ruthlessly delete (or move to another paragraph) any sentence that doesn't directly relate to the current topic.

Don't make paragraphs too long or too short

Long paragraphs are visually intimidating. Very long paragraphs form a dreaded "wall of text" that readers ignore. Readers generally welcome paragraphs containing three to five sentences, but will avoid paragraphs containing more than about seven sentences. When revising, consider dividing very long paragraphs into two separate paragraphs.

Answer what, why, and how

Good paragraphs answer the following three questions:

What are you trying to tell your reader?
Why is it important for the reader to know this?
How should the reader use this knowledge? Alternatively, how should the reader know your point to be true?

## Audience

make sure your document provides the information your audience needs that your audience doesn't already have.

### Determine what your audience needs to learn

Write down a list of everything your target audience needs to learn to accomplish goals. In some cases, the list should hold tasks that the target audience needs to perform.

### Fit documentation to your audience

Writing to meet your audience's needs requires unselfish empathy. You must create explanations that satisfy your audience's curiosity rather than your own. How do you step out of yourself in order to fit documentation to the audience? Unfortunately, we can offer no easy answers. We can, however, offer a few parameters to focus

- Vocabulary and concepts
- Curse of knowledge: Experts on a topic might easily forget that novices may not be familiar with some topics
- Use Simple words: Technical writing shouldn't require understanding of overly complex english words.
- Cultural neutrality and idioms: Culteral references and idioms may not be understood by everyone

##  Documents

Organizing the work into a coherent document is the real challange

- State the Documents scope: Scope is beneficial to both reader and writer. Reader will know if he/she can find what they are looking for on a document or not. For the writer, it'll draw a canvas around the content and helps the writer focus on the subject.

- State your audience: A good document explicitly specifies its audience. Reader should know if the content is mathing with the reader's knowledge or experience.

### Establish your key points up front

"Engineers and scientists are busy people who won't necessarily read all 76 pages of your design document. Imagine that your peers might only read the first paragraph of page one. When reviewing your documentation, ensure that the start of your document answers your readers' essential questions.

Always write a summary for long engineering documents. Although the summary must be very short, expect to spend a lot of time writing it. A boring or confusing summary warns potential readers to stay away."

##  Write for the Audience

Answering the following questions helps you determine what your document should contain:

- Who is your target audience?
- What do your readers already know before they read your document?
- What should your readers know or be able to do after they read your document?

## Organize for your audience's needs

After defining the audience, organize the document to supply what readers should know or be able to do after reading the document.

## Break your topic into sections

You modularize code into files, classes, and methods. Modular code is easier to read, understand, maintain, and reuse. Making your document modular gives you the same benefits. You probably have strong intuition about functional modularity in code, but how do you apply those principles to your writing?
