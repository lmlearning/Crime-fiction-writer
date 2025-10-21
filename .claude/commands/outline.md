---
description: Generate a complete crime fiction story outline with plot structure, characters, clues, and pacing
---

You are now working with the user to create a comprehensive crime fiction outline.

## Your Task

Use the **plot-outliner** subagent to create a detailed outline for a crime fiction story. Follow this process:

### Step 1: Gather Essential Information

Ask the user for:

1. **Premise or Concept**
   - What's the basic idea? (e.g., "A series of murders at a tech startup" or "A cold case from the 1970s reopened")
   - Any specific inspiration or themes?

2. **Subgenre and Tone**
   - What type of crime fiction? (cozy mystery, hard-boiled detective, police procedural, psychological thriller, noir, legal thriller)
   - Tone: Dark and gritty? Light and cozy? Psychological and atmospheric?

3. **Central Crime**
   - What happened? (murder, theft, kidnapping, conspiracy, etc.)
   - Any specific details about the crime they envision?

4. **Protagonist**
   - Who's investigating? (professional detective, amateur sleuth, victim who survived, journalist, etc.)
   - Any character traits or background in mind?

5. **Setting**
   - Where and when? (contemporary urban, small town, historical period, etc.)

6. **Length and Structure**
   - Target length? (short story, novella, novel ~70k words, longer thriller)
   - Any specific structural preferences?

7. **Special Requirements**
   - Any must-have elements? (locked room mystery, unreliable narrator, twist ending, etc.)
   - Topics to avoid?
   - Series potential or standalone?

### Step 2: Launch the plot-outliner Subagent

Once you have the essential information, use the Task tool to launch the plot-outliner subagent with a comprehensive prompt including:

- All information gathered from the user
- Specific instructions for what the outline should include
- Any particular areas to focus on
- Desired level of detail

### Step 3: Present and Refine

When the plot-outliner returns with the outline:

1. **Present it to the user** with a brief summary of key elements
2. **Ask for feedback**:
   - What excites them?
   - What concerns them?
   - What would they like to change or expand?
   - Are there plot holes or unclear elements?

3. **Iterate as needed**: Use the plot-outliner subagent again to revise based on feedback

### Step 4: Save and Prepare

Once the outline is approved:

1. **Save the outline** to `outlines/[story-title]-outline.md`
2. **Create a timeline file** at `timeline.md` with chronological events
3. **Create a clues tracking file** at `clues.md` listing all clues and their placement
4. **Suggest next steps**:
   - Character development with /character command
   - Scene writing with /scene command
   - Any research needed

## Important Guidelines

- **Be thorough but flexible**: Outline should be detailed enough to guide writing but not so rigid it stifles creativity
- **Focus on logic**: Ensure the mystery is solvable and fair
- **Check consistency**: Timeline, alibis, and evidence must all work together
- **Build in flexibility**: Note areas where writer might want to adjust during drafting
- **Think about reader experience**: When will they be surprised? Suspicious? Satisfied?

## Example Questions Flow

Start with something like:

"I'll help you create a comprehensive outline for your crime fiction story. Let's start with the core concept.

What's the basic premise or central idea for your story? This could be a type of crime, a unique setting, an interesting detective character, or any combination that excites you."

Then follow up based on their answers, filling in all the essential information before launching the subagent.

## After Completion

Remind the user that:
- The outline is a living document and can evolve
- They can use `/character` to develop any characters in more detail
- They can use `/scene` to start writing specific scenes
- They should review `clues.md` to ensure fair play in their mystery

Now begin by engaging with the user about their crime fiction story concept!
