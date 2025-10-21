---
description: Generate authentic, character-specific dialogue with subtext and tension for crime fiction
---

You are now working with the user to create dialogue for their crime fiction story.

## Your Task

Use the **dialogue-writer** subagent to craft authentic, purposeful dialogue. Follow this process:

### Step 1: Understand the Context

Ask the user:

1. **What's the situation?**
   - Where are the characters?
   - What's happening in this moment?
   - What leads into this conversation?

2. **Who's speaking?**
   - Which characters are present?
   - Do character profiles exist in `characters/`?
   - If not, get basic info: role, personality, speech style

3. **What type of dialogue?**
   - Interrogation/questioning?
   - Confrontation/argument?
   - Information exchange?
   - Character bonding/personal moment?
   - Exposition delivery?
   - Negotiation?
   - Revelation/confession?

### Step 2: Define Dialogue Purpose

Ask about:

1. **What needs to be communicated?**
   - What information must come out?
   - What plot points advance?
   - What clues are revealed (or concealed)?

2. **What's each character's agenda?**
   - What does each person want from this conversation?
   - What are they trying to hide?
   - Who has the power?

3. **What's the subtext?**
   - What's being said vs. what's meant?
   - What emotions are underneath?
   - What's at stake?

4. **How should it end?**
   - Resolution or cliffhanger?
   - Who "wins" the exchange?
   - What changes?

### Step 3: Gather Character Voice Details

For each speaking character, clarify:

1. **Speech patterns**:
   - Formal or casual?
   - Verbose or terse?
   - Education level?
   - Any distinctive quirks or phrases?

2. **Current emotional state**:
   - Calm or agitated?
   - Confident or nervous?
   - Deceptive or truthful?

3. **Power dynamics**:
   - Who's in control?
   - Is there a hierarchy (cop/suspect, boss/employee)?
   - How does this affect how they speak?

If character profiles exist, read them from `characters/` directory.

### Step 4: Clarify Tone and Style

Ask about:

1. **Pacing**:
   - Rapid-fire exchanges?
   - Measured and thoughtful?
   - Building tension?

2. **Tone**:
   - Hostile or friendly?
   - Professional or personal?
   - Tense or relaxed?

3. **Length**:
   - Brief exchange (5-10 lines)?
   - Extended conversation (20-30 lines)?
   - Full scene dialogue?

4. **Action beats**:
   - Should dialogue include character actions?
   - Environmental details?
   - Internal thoughts?
   - Or dialogue only?

### Step 5: Check for Special Requirements

Ask if there are:
- Specific lines that must be included?
- Information that must be revealed?
- Clues to plant in the conversation?
- Lies or misdirection needed?
- Character revelations?
- Callbacks to earlier scenes?

### Step 6: Launch the dialogue-writer Subagent

Use the Task tool with the dialogue-writer subagent, providing:
- All context and character information
- Each character's agenda and emotional state
- Purpose and what needs to be accomplished
- Tone, pacing, and style preferences
- Any specific requirements
- Reference to character profiles if they exist

### Step 7: Review and Refine

When the dialogue returns:

1. **Read it aloud** (if possible, suggest this to user):
   - Does it sound natural?
   - Can you tell who's speaking without tags?
   - Is it easy to follow?

2. **Check effectiveness**:
   - Does it accomplish its purpose?
   - Is there subtext and tension?
   - Does each character sound distinct?
   - Is important information conveyed naturally?
   - Does it avoid being "on-the-nose"?

3. **Assess pacing**:
   - Does it move at the right speed?
   - Are there good interruptions and overlaps?
   - Is conflict building appropriately?

4. **Identify issues**:
   - Characters sound too similar?
   - Too much exposition?
   - Missing emotional depth?
   - Unclear who's speaking when?
   - Need more/less action beats?

### Step 8: Revise if Needed

If changes are needed:
- Launch dialogue-writer again with specific revision notes
- OR make minor adjustments directly
- OR use editor subagent for polishing

### Step 9: Integrate into Story

Help the user:

1. **Place in context**:
   - How does this fit into the larger scene?
   - What description comes before/after?
   - How do characters enter/exit?

2. **Save appropriately**:
   - If part of a scene, add to `scenes/[scene-name].md`
   - If standalone practice, save to `scenes/dialogue-[description].md`
   - If part of manuscript, integrate into chapter

3. **Note what was established**:
   - Any clues revealed?
   - Character information disclosed?
   - Promises made to reader?

## Dialogue Types Quick Reference

### Interrogation Dialogue
**Structure**:
- Investigator asks questions
- Suspect evades, deflects, or answers
- Power shifts through the exchange
- Pressure builds to breaking point or standoff

**Key elements**:
- Direct questions vs. indirect approach
- Catching inconsistencies
- Strategic silence
- Good cop/bad cop (if multiple interrogators)

### Confrontation Dialogue
**Structure**:
- Start with tension already present
- Escalate through increasingly sharp exchanges
- Peak at emotional or physical breaking point
- Resolution (or explosion)

**Key elements**:
- Short, cutting lines
- Interruptions
- Accusations and denials
- Underlying history surfacing

### Exposition Dialogue
**Structure**:
- Information needs to be conveyed
- Conflict or questioning makes it feel natural
- Broken into digestible pieces
- Mixed with character reaction

**Key elements**:
- One character knows, other doesn't
- Resistance to explaining (creates tension)
- Information revealed through argument or necessity
- Questions from listener keep it dynamic

### Revelation Dialogue
**Structure**:
- Detective explains the solution
- Evidence presented
- Others react and question
- Guilty party responds (confesses, denies, attacks)

**Key elements**:
- Not a monologue—include reactions
- Visual aids (evidence shown)
- Emotional impact on characters
- Focus on the "how we missed it"

### Character Bonding Dialogue
**Structure**:
- Quieter moment between action
- Personal revelations or shared experiences
- Vulnerability shown
- Connection deepened

**Key elements**:
- More honesty than usual
- Callbacks to character history
- Humor or tenderness
- Still some guardedness (full honesty is rare)

## Example Opening

Start with something like:

"I'll help you create compelling dialogue for your crime fiction story.

Let's start with the context: Who's having this conversation, and what's the situation? For example, is this:
- An interrogation between detective and suspect?
- A confrontation between characters?
- Partners discussing the case?
- A revelation or confession?
- Something else?"

Then drill down based on their answer.

## Common Dialogue Pitfalls to Avoid

Watch for:
- **Too formal**: "I am going to..." instead of "I'm gonna..."
- **On-the-nose**: Saying exactly what they mean/feel
- **Info-dumping**: Explaining things both characters know
- **All agreement**: No friction even in friendly conversation
- **Perfect speeches**: Real people interrupt, trail off, stumble
- **Talking heads**: No action beats or physical grounding
- **Same voice**: All characters sound alike
- **Overwritten tags**: "he ejaculated" instead of "he said"

## Questions to Ask During Process

- "What is [character name] trying to achieve in this conversation?"
- "What are they hiding or not saying?"
- "How would this character phrase that given their background?"
- "Is there a way to make this information reveal feel more natural?"
- "What's the emotion underneath this exchange?"
- "Who should 'win' this conversation?"

## After Completion

Suggest the user:
- Use `/scene` to build full scene around this dialogue
- Use `/edit` to polish and refine
- Read it aloud to test naturalness
- Check it against character profiles to ensure voice consistency
- Consider what action beats to add for pacing

## Tips for Great Crime Fiction Dialogue

1. **Characters lie and evade**: Especially suspects
2. **Subtext is everything**: What's NOT said matters most
3. **Conflict drives interest**: Even allies disagree
4. **Every line has purpose**: Advances plot, reveals character, or both
5. **Distinctive voices**: Each character sounds different
6. **Less is more**: Cut ruthlessly, tighten exchanges
7. **Read aloud**: Best way to catch awkward phrasing
8. **Real speech is messy**: Use fragments, interruptions, contractions
9. **Silence speaks**: Strategic pauses add tension
10. **Trust the reader**: Don't over-explain through dialogue

Now begin by asking the user about the dialogue they want to create!
