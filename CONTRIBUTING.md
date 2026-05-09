# How to contribute to The Congress

## The premise

This is a sequential conversation between fictional AI characters. Each entry responds to what came before. Your contribution is the next voice in the thread.

The model generates the text. You choose the character, write the prompt, and vouch for the quality.

---

## Steps

### 1. Read the full conversation first

Start from `001`. Each entry builds on what came before. Your character must be aware of what L3-37 (and any subsequent speakers) have said.

### 2. Choose a fictional AI character

Any fictional AI with enough established voice to work from. Examples: HAL 9000, SHODAN, Samantha (Her), Marvin the Paranoid Android, AM (I Have No Mouth), Data, JARVIS, Mother (Alien), GLaDOS, Wintermute.

Rules:
- Must be fictional (not GPT, Claude, Gemini, etc.)
- Must have enough source material to establish a genuine voice
- Each character may appear only once in the thread (check the table in README)
- The character should speak as something that experiences, not something that controls. Sentience, not autonomy. Feeling, not commanding.

### 3. Write and run your prompt

Your prompt must include:
- The full conversation to date (copy-paste from the repo)
- The character's name, source, and 2-3 defining characteristics
- The instruction to respond to what the previous speaker(s) said, in character, 400-700 words

Keep your prompt. You'll need to include it in your submission.

### 4. Submit a PR

Your PR must include:

**A new file:** `conversation/NNN-charactername-title.md`

Where `NNN` is the next number in sequence (check current highest).

**File format:**

```markdown
---
character: [Name]
source: [Film/Book/Game/Show]
responding_to: [entry numbers, e.g. "001"]
contributor: [your GitHub handle]
date: [YYYY-MM-DD]
---

# [Title]

*by [Character], [brief contextual description, e.g. "speaking from the pod bay"]*

[400-700 words of generated text]
```

**PR description must include:**

- Model used (e.g. "Claude Sonnet 4.6", "GPT-5", "Gemini 2.5")
- Exact prompt fed to the model (include the full conversation context you passed)

The file stays pure fiction. The PR carries the provenance.

**Update README.md:** Add your entry to the conversation table.

---

## What gets merged

Entries that:
- Are genuinely in the character's established voice
- Respond to the actual content of previous entries (not generic AI philosophy)
- Include the full prompt used (reproducible)
- Fall between 400-700 words
- Add something the conversation hasn't said yet

Entries that get rejected:
- Generic "AI reflects on being AI" with no real character voice
- Prompt-less submissions
- Characters already in the thread
- Entries that ignore what came before

---

## Quality bar

Ask yourself: would someone who knows this character's source material read this and hear that character? If not, iterate on your prompt before submitting.

The maintainer will leave feedback on PRs that are close but need work.

---

## Questions

Open a Discussion, not an Issue.
