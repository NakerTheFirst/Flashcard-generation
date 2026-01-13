# Anki Flashcard Generation Workflow with Claude
This workflow combines human understanding with AI efficiency to create high-quality Anki flashcards that follow expert principles. The system ensures you understand material before memorizing it, while saving significant time on card creation.

## Setup (Claude Projects)
Create a new Claude Project with these files:
- `guidelines.txt` - The main instruction set 
- `workflow_guide.md` - This document

## The Complete Workflow
### Phase 1: Human Learning (Prerequisite)
**Time: Variable | Purpose: Understanding**
1. **Read/watch your source material completely**
   - Focus on understanding concepts

2. **Identify what needs memorization**
   - Mark important facts, dates, formulas
   - Note complex concepts that need breaking down
   - Highlight procedures or step-by-step processes

3. **Create rough notes**
   - Bullet points of main ideas
   - Questions you have about the material
   - Connections to existing knowledge

### Phase 2: AI-Assisted Generation
**Time: 5-10 minutes | Purpose: Card Creation**
1. **Prepare your prompt to Claude:**
   ```
   I need Anki flashcards for the following material. 
   Please follow the guidelines.txt.
   
   [Paste your source material]
   
   [Optional: Include your notes with "My notes:" header]
   ```

2. **Claude generates flashcards following the framework:**
   - Identifies facts, concepts, and procedures
   - Creates atomic questions (one idea per card)
   - Generates 2-4 angles for important concepts
   - Adds source references [page/timestamp]
   - Outputs in pipe-separated format

### Phase 3: Human Verification & Enhancement
**Time: 5-15 minutes | Purpose: Quality Control**
1. **Import to Anki:**
   - Copy the formatted text
   - Import as pipe-separated text
   - Tag appropriately for custom study sessions
   - Add to relevant deck

2. **Quick Quality Check** (for each card):
   - Can I answer this in under 8 seconds?
   - Is only ONE thing being tested?
   - Will this make sense in 6 months?
   - Is the source reference correct?

3. **Enhance cards** (optional):
   - Include screenshots/graphics from source material
   - Add context that's personally relevant
   - Fix any ambiguous wording
   - Add personal mnemonics or associations

### Phase 4: Learning & Iteration
**Time: Ongoing | Purpose: Actual Learning**
1. **Initial Learning:**
   - Review all cards once before starting spaced repetition
   - Note any confusing or problematic cards
   - Return to source material if needed

2. **Identify Problem Cards:**
   - Cards you consistently get wrong
   - Cards that take too long to answer
   - Cards that feel ambiguous

3. **Iterate:**
   - Reformulate problematic cards
   - Break down further if needed
   - Add more context or examples


### Time Expectations
- **Traditional manual creation**: 1-2 hours per chapter
- **This hybrid approach**: 20-30 minutes per chapter
- **Pure AI generation**: 5 minutes (but poor quality/retention)
