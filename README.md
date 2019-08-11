# Assyrian Wordlists

A repository for Assyrian wordlists that cover a wide range of topics, such as:

- grammar
- greetings
- family
- fashion
- entertainment
- food
- furniture
- house items
- general verbs
- sports
- politics
- and so on...

## Format

Text files will be used for data entry until a platform has been developed for easier entry of data.

In order to make the text files more programmatically consumable for conversion to other formats (such as JSON, XML, CSV), an ordered schema is required. Order is sufficient, programmatically. However, to make it more easily parsable by the human eye, symbols will be used after the first 5 lines. 

The following schema is to be implemented in the text files.

**Schema**

English Word <BR>
Eastern Phonetic <BR>
Eastern Assyriac <BR>
Western Phonetic <BR>
Western Assyriac <BR>
\# Akkadian <BR>
^ Aramaic <BR>
? English Definition <BR>
\- Part of speech (noun, verb, adjective, adverb, pronoun, preposition, conjunction, interjection) <BR>
@ Word list category <BR>
: Example 1 in English <BR>
: Example 1 in Eastern Phonetic <BR>
: Example 1 in Eastern Assyriac <BR>
: Example 1 in Western Phonetic <BR>
: Example 1 in Western Assyriac <BR>
: Example 2 in English <BR>
: ... <BR>

**Indicators**

\*Indicator for potential loan word <BR>
... Indicator for absence of data (not yet filled) <BR>

**Example**

and <BR>
u <BR>
ܘ <BR>
u <BR>
ܘ <BR>
\# u <BR>
^ wǝ <BR>
? Connects parts of speech together where each part is included jointly with the other connected part(s). <BR>
\- conjunction <BR>
@ conjunctions <BR>
: This and that. <BR>
: aha u a'ya <BR>
: ܐܵܗܵܐ ܘ ܐܲܝܵܐ <BR>
: oho u ayo <BR>
: ܐܳܗܳܐ ܘ ܐܰܝܳܐ <BR>
: Ink and paper. <BR>
: ...  <BR>

**Requirements**

It is required to notate and include each row up to the 10th one. Where there is no data available, indicate it so with ..., like the following – showing acknowledgement of the absence of data:

? ... <BR>

It is not required to add an 11th row where there is no example. After row 10, the word entry is complete. The absence of example(s) for the word is assumed where it is not noted. Such as below:

and <BR>
u <BR>
ܘ <BR>
u <BR>
ܘ <BR>
\# u <BR>
^ wǝ <BR>
? ... <BR>
\- conjunction <BR>
@ conjunctions <BR>

## Contribution

Everyone is encouraged to join the effort and contribute to this open source repository. One may contribute by:

- joining the group and making changes directly (contact Ron Rihoo at rihooron@gmail.com);
- forking the repository, making changes, and creating a pull request; or
- creating an issue with the suggested changes/additions.

This repository eagerly awaits for your contributions.
