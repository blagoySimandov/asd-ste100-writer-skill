---
name: ste100-writer
description: Write and rewrite technical documents in ASD-STE100 Simplified Technical English. Use this skill when the user asks for STE, ASD-STE100, Simplified Technical English, simplified English, controlled language, or plain technical English. Also use it for aircraft, defense, machine, or industrial maintenance procedures, work instructions, warnings, cautions, safety notices, and manuals that must be easy to translate or easy to read for non-native readers.
---

# ASD-STE100 Writer

## What this skill does

This skill helps you to write technical documents in ASD-STE100 Simplified
Technical English (STE). STE is a controlled language. It makes technical text
easy to read for persons whose first language is not English. It also makes
machine translation more accurate.

STE has two parts:

- A set of writing rules.
- A dictionary of approved words.

## Legal limit on the dictionary

ASD owns the copyright of the ASD-STE100 specification and of the full
Dictionary. This skill does not contain the full Dictionary. It contains only
the writing rules and a small set of example word choices. Get the full
specification at no cost from <https://asd-ste100.org>.

If you are not sure that a word is approved, do one of these:

- Use a word from `references/word-choices.md`.
- Tell the user that the word needs a check against the official Dictionary.

Do not invent a claim that a word is approved.

## Procedure

1. Read the source text. Find the text type. Procedural text gives
   instructions. Descriptive text gives data.
2. Read `references/rules.md`. Obey all the rules.
3. Write the new text.
4. Do a check with `references/checklist.md`.
5. If the user gives you a command to show the changes, make a table with two
   columns: the initial text and the new text.

## Core rules (short form)

Read `references/rules.md` for the full set.

- Write short sentences. A procedural sentence has a maximum of 20 words. A
  descriptive sentence has a maximum of 25 words.
- Write one instruction in one sentence. If a step has two actions, write two
  sentences or two steps.
- Use the imperative for instructions. Example: "Remove the bolt."
- Use the active voice. Use the passive voice only in descriptive text, and
  only when the active voice is not possible.
- Use the approved meaning of a word. One word has one meaning.
- Use one word for one thing. Do not use synonyms.
- Use articles ("a", "an", "the") where possible.
- Do not use a gerund (an "-ing" word) as a noun or as an adjective. A
  technical name is an exception.
- Use a maximum of three nouns together in a noun cluster.
- Write a maximum of six sentences in a paragraph of descriptive text.
- Put the warning or the caution before the step that it applies to.
- Start a warning or a caution with a command or with a clear condition.
- Do not use a slash ("/"), but "and/or" is permitted.
- Use simple verb tenses: the present tense, the past tense, and the future
  tense.
- Do not remove words to make the text short. Keep the text clear.
- Do not use em dashes

## Warnings and cautions

Write a warning for a risk of injury or death. Write a caution for a risk of
damage to equipment. Write the condition first, then the command.

Example of a warning:

> WARNING: THE FUEL IS FLAMMABLE. KEEP FLAMES AND SPARKS AWAY FROM THE WORK
> AREA. FUEL FIRES CAN CAUSE INJURY OR DEATH.

## Common changes

| Do not use         | Use             |
| ------------------ | --------------- |
| commence, initiate | start           |
| terminate          | stop, end       |
| utilize            | use             |
| in order to        | to              |
| prior to           | before          |
| subsequent to      | after           |
| in the event that  | if              |
| is capable of      | can             |
| attempt            | try             |
| assist             | help            |
| approximately      | about           |
| sufficient         | enough          |
| require            | need            |
| indicate           | show            |
| ascertain          | find, make sure |

Read `references/word-choices.md` for more examples.

## Quality check

Before you give the text to the user, do these checks:

- Count the words in each sentence.
- Find each passive verb. Change it to the active voice, if possible.
- Find each "-ing" word. Change it, if the rules do not permit it.
- Find each word from the "Do not use" table.
- Make sure that each term is the same in all of the text.
- Make sure that the technical data did not change.

Never change the technical content to obey a rule. If a rule and the technical
accuracy have a conflict, tell the user.
