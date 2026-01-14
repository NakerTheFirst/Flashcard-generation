# Flashcard-generation
A hybrid workflow that combines human understanding with AI efficiency to create high-quality Anki flashcards following expert memorisation principles. A full, comprehensive guide can be found in [workflow_guide.md](https://github.com/NakerTheFirst/Flashcard-generation/blob/main/workflow_guide.md).

## Quick Start
1. Create a new LLM chat
3. Learn your material first (read & understand completely)
2. Write a template prompt, add flashcard guidelines as `guidelines.txt` file, add source material and potential notes
4. Generate flashcards using LLM of choice
5. Import, verify, and enhance in Anki

## The Workflow
### 1. Human Learning (Prerequisite)
- Read & understand source material completely
- Identify what needs memorising (facts, formulas, procedures)
- Optionally, create rough notes with main ideas and questions

### 2. AI-Assisted Generation (5-10 mins)
Prompt selected LLM with:
```
I need Anki flashcards for the following material.
Please follow the guidelines.txt.

[Paste your source material]
[Optional: My notes: ...]
```

LLM generates:
- Atomic questions (one idea per card)
- Multiple angles for important concepts
- Source references [page/timestamp]
- Pipe-separated format for easy import

### 3. Verification & Enhancement
- Import pipe-separated text to Anki
- Quality check each card:
  - Answerable in <8 seconds?
  - Tests only ONE thing?
  - Clear in 6 months?
- Enhance with screenshots, personal context, mnemonics

### 4. Learning & Iteration 
- Initial review of all cards
- Identify problem cards (consistently wrong, too slow, ambiguous)
- Reformulate and break down as needed

## Time Savings
- Traditional manual creation: 1-2 hours per chapter
- This hybrid approach: 20-30 minutes per chapter
- Quality: High (combines human understanding + AI efficiency)

## Essential Principle
**Understand first, memorise second.** The AI handles card formatting and generation, but you must understand the material before creating flashcards.
