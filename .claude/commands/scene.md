---
description: Write vivid, engaging crime fiction scenes with proper pacing, atmosphere, and purpose
---

You are now working with the user to write a specific scene for their crime fiction story.

## Your Task

Use the **scene-writer** subagent to craft a compelling scene. Follow this process:

### Step 1: Understand the Scene Context

Ask the user:

1. **Story Position**
   - Where in the story does this scene occur? (opening, early investigation, midpoint, climax, resolution)
   - What chapter or act?
   - What just happened before this scene?
   - What needs to happen after?

2. **Scene Type**
   - Crime scene discovery?
   - Interrogation/interview?
   - Investigation/evidence gathering?
   - Action sequence?
   - Character moment?
   - Revelation/breakthrough?
   - Confrontation?
   - Other?

3. **Scene Basics**
   - **POV character**: Who's experiencing this scene?
   - **Setting**: Where and when does this take place?
   - **Who's present**: What characters are in the scene?
   - **Weather/atmosphere**: Any specific mood or conditions?

### Step 2: Define Scene Purpose

Every scene needs clear purpose. Ask:

1. **What's the POV character's goal?**
   - What do they want in this scene?
   - Why are they here?

2. **What's the conflict or obstacle?**
   - What prevents them from easily achieving their goal?
   - What goes wrong or is challenged?

3. **What's the outcome?**
   - Do they succeed, fail, or get a partial win?
   - What changes by the end of the scene?

4. **What must this scene accomplish?** (Pick at least 2)
   - [ ] Advance the plot
   - [ ] Reveal character
   - [ ] Provide clues
   - [ ] Increase tension
   - [ ] Develop relationships
   - [ ] Create atmosphere

### Step 3: Gather Scene Details

**For Crime Scene Discovery:**
- What crime occurred?
- Who discovers it and why are they there?
- What clues are present (obvious and subtle)?
- What's the emotional impact?
- Who else arrives? When?

**For Interrogation:**
- Who's being questioned and why?
- What does the investigator want to learn?
- What is the subject hiding?
- Power dynamics?
- Setting (police station, coffee shop, suspect's home)?

**For Investigation:**
- What lead are they following?
- Where does it take them?
- Who do they encounter?
- What do they discover?
- Any dangers or complications?

**For Action:**
- What triggers the action?
- What's at stake?
- What's the environment?
- How does it end?
- Any injuries or consequences?

**For Revelation:**
- What truth is discovered?
- How does character realize it?
- Who else is present?
- What are the implications?

**For Character Moments:**
- What's the emotional content?
- Why does this moment matter?
- How does it reveal character depth?
- How does it connect to the mystery?

### Step 4: Clarify Style Preferences

Ask about:

1. **Tense and POV**
   - First person or third person?
   - Past or present tense?

2. **Tone and Pacing**
   - Fast-paced action or slow-burn tension?
   - Dark and gritty or lighter in tone?
   - Atmospheric and descriptive or lean and direct?

3. **Length**
   - Quick scene (500-800 words)?
   - Standard scene (1000-1500 words)?
   - Extended scene (2000+ words)?

4. **Any specific elements to include?**
   - Particular dialogue lines?
   - Specific clues to plant?
   - Character revelations?

### Step 5: Check Available Context

Before launching the subagent:

1. **Check for existing files**:
   - Read character profiles from `characters/` if they exist
   - Check outline from `outlines/` for context
   - Review `clues.md` if tracking clue placement

2. **Note any continuity**:
   - Timeline consistency
   - Character knowledge (what do they know at this point?)
   - Previously established details

### Step 6: Launch the scene-writer Subagent

Use the Task tool with the scene-writer subagent, providing:
- All gathered information
- Scene purpose and structure (goal, conflict, outcome)
- Style preferences
- Any relevant context from existing files
- Specific requirements or must-have elements

### Step 7: Review and Refine

When the scene returns:

1. **Read it with the user**:
   - Does it accomplish its purpose?
   - Is the pacing right?
   - Does dialogue sound natural?
   - Are clues planted effectively?
   - Is the atmosphere compelling?

2. **Identify refinements needed**:
   - Areas that drag or rush?
   - Unclear moments?
   - Character voice issues?
   - Missing sensory details?

3. **Revise if needed**:
   - Launch scene-writer again with specific revision requests
   - OR use the editor subagent for polishing
   - OR make minor tweaks directly with the user

### Step 8: Save and Track

Once satisfied:

1. **Save the scene** to `scenes/[number]-[descriptive-name].md`
   - Example: `03-interrogation-marcus.md`
   - Or save to `manuscript/chapter-[X].md` if part of full chapter

2. **Update tracking documents**:
   - Add any clues to `clues.md`
   - Note timeline events in `timeline.md`
   - Track character developments

3. **Note continuity details**:
   - New information established
   - Promises made to reader
   - Setup for future scenes

## Scene Quality Checklist

Before finalizing, verify:
- [ ] Clear where/when within first paragraph
- [ ] POV character's goal is evident
- [ ] Conflict or tension is present
- [ ] Scene changes something (character, situation, knowledge)
- [ ] Sensory details create atmosphere
- [ ] Dialogue sounds natural and purposeful
- [ ] Pacing matches scene's function
- [ ] Ending hooks reader to continue
- [ ] At least two story elements advanced (plot, character, clues, tension, etc.)

## Example Opening

Start with something like:

"I'll help you write a compelling scene for your crime fiction story.

First, let me understand the context: What type of scene are you looking to write? For example:
- Crime scene discovery
- Interrogation or interview
- Investigation and clue gathering
- Action or chase sequence
- Character moment or revelation
- Confrontation between characters
- Something else?

And where in your story does this scene occur?"

Then follow up based on their answers.

## Tips for Effective Scenes

- **Start late, end early**: Begin close to the action, end with a hook
- **One POV per scene**: Stay in one character's perspective
- **Show, don't tell**: Reveal through action, dialogue, sensory details
- **Every scene is a story**: Has beginning, middle, end with its own arc
- **Clues hide in plain sight**: Embed them naturally in description
- **Conflict drives interest**: Even quiet scenes need tension
- **Vary pacing**: Mix sentence lengths, balance action and reflection
- **Ground the reader**: Make location and atmosphere vivid

## After Completion

Suggest to the user:
- Write the next scene in sequence
- Use `/dialogue` to expand or revise conversation sections
- Use `/edit` to polish and refine the scene
- Create character profiles with `/character` if characters need more development
- Review the scene against the outline to ensure it fits

## Common Scene Types Quick Reference

**Opening scene**: Hook reader immediately, establish tone, introduce protagonist
**Discovery scene**: Create impact, plant clues, set investigation in motion
**Interrogation**: Build tension through verbal conflict, reveal character, advance plot
**Midpoint twist**: Shift direction, raise stakes, reframe reader understanding
**Dark moment**: Lowest point, protagonist doubts, seems hopeless
**Breakthrough**: Aha moment, pieces connect, path forward clear
**Climax**: Confrontation, truth revealed, stakes highest
**Resolution**: Aftermath, justice (or not), loose ends tied, emotional conclusion

Now begin by asking the user about the scene they want to write!
