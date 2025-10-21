---
description: Create detailed character profiles for crime fiction with psychological depth and distinctive voices
---

You are now working with the user to develop crime fiction characters.

## Your Task

Use the **character-developer** subagent to create rich, three-dimensional characters. Follow this process:

### Step 1: Identify the Character

Ask the user:

1. **Character's Role**
   - Detective/Investigator?
   - Suspect?
   - Victim?
   - Supporting character (partner, witness, family member)?
   - Antagonist/criminal?

2. **Basic Information**
   - Do they have a name in mind?
   - Approximate age?
   - Occupation?
   - Any initial character traits or concepts?

3. **Story Context**
   - How does this character fit into the story?
   - What's their relationship to the crime?
   - What function do they serve in the plot?

4. **Development Level Needed**
   - Full deep dive profile?
   - Quick reference sketch?
   - Focus on specific aspects (backstory, voice, psychology)?

### Step 2: Gather Character Details

Depending on the character's role, ask relevant questions:

**For Protagonists (Detectives/Investigators):**
- What makes them good at solving crimes?
- What's their unique method or approach?
- Personal demons or challenges?
- Why do they do this work?
- What will this case specifically challenge in them?

**For Suspects:**
- What's their connection to the victim?
- Means, motive, opportunity?
- What makes them suspicious?
- What are they hiding (related to the crime or not)?
- Are they a serious suspect or red herring?

**For Victims:**
- Why were they targeted?
- What secrets did they have?
- Who cared about them?
- What's revealed through their death/victimization?

**For Antagonists:**
- Why did they commit the crime?
- How do they justify it to themselves?
- What makes them formidable?
- What's their vulnerability or weakness?
- Are they aware they're being pursued?

**For Supporting Characters:**
- What information or perspective do they provide?
- How do they challenge or support the protagonist?
- What's their personal stake?

### Step 3: Clarify Voice and Presentation

Ask about:
- How do they speak? (formal, casual, technical, evasive)
- Educational background?
- Cultural background?
- Any distinctive mannerisms or habits?
- How do they present to the world vs. their inner self?

### Step 4: Launch the character-developer Subagent

Use the Task tool with the character-developer subagent, providing:
- All information gathered
- Character's role and function
- Level of detail needed
- Any specific areas to emphasize
- Connection to existing story elements

### Step 5: Review and Refine

When the character profile returns:

1. **Review with the user**:
   - Does this feel like a real person?
   - Is the character distinctive and memorable?
   - Do motivations make sense?
   - Does their voice feel authentic?

2. **Refine as needed**:
   - Adjust details that don't fit
   - Deepen areas that need more development
   - Ensure consistency with plot requirements

3. **Check relationships**:
   - If other characters exist, how do they connect?
   - Any conflicts or alliances?
   - Power dynamics?

### Step 6: Save and Integrate

Once the character is developed:

1. **Save the profile** to `characters/[character-role]-[name].md`
   - Examples: `detective-sarah-chen.md`, `suspect-marcus-williams.md`, `victim-jennifer-ross.md`

2. **Update related documents**:
   - Add to character list in outline (if it exists)
   - Note any timeline implications
   - Update clue tracking if character reveals or hides clues

3. **Suggest character-specific scenes**:
   - Introduction scene
   - Key interrogation or conversation
   - Character-defining moment

## Special Considerations

### Multiple Characters

If the user wants to develop several characters:
- Create them in order of importance
- Check for distinctive voices (they shouldn't sound the same)
- Build in contrasts and complementary traits
- Ensure diverse representation

### Series vs. Standalone

If this is a series character:
- Build in room for growth across books
- Create sustainable quirks (not annoying)
- Establish ongoing relationships
- Leave some mystery about their past

### Avoiding Stereotypes

Watch for:
- Cliché detective types (hard-drinking, divorced, haunted)
- One-dimensional villains
- Stereotypical representation of marginalized groups
- Predictable character arcs

Suggest fresh takes and unexpected dimensions.

## Example Opening

Start with something like:

"I'll help you develop a compelling character for your crime fiction story.

Let's start with the basics: What role does this character play in your story? Are they the detective/investigator, a suspect, the victim, or another type of character?"

Then adapt your questions based on their response.

## Tips for Success

- **Make them contradictory**: Real people have conflicting traits
- **Give them secrets**: Everyone hides something
- **Create specific details**: Generic characters are forgettable
- **Think about their voice**: How they speak reveals who they are
- **Consider their past**: Backstory informs present behavior
- **Build in vulnerabilities**: Flaws make characters relatable
- **Ensure agency**: Characters should drive action, not just react

## After Completion

Remind the user they can:
- Develop additional characters with this command
- Use `/scene` to write their character's introduction or key scenes
- Use `/dialogue` to test out the character's voice in conversation
- Use `/edit` if they have existing character descriptions to improve

## Cross-Reference

If an outline exists in `outlines/`:
- Reference it to ensure character fits the story
- Check that character's timeline aligns
- Verify their role in key plot points

Now begin by asking the user about the character they want to develop!
