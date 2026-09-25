# Crime Fiction Writing Workflow for Claude Code

Welcome to your Crime Fiction Writing Agent! This repository is configured with Claude Code to help you write compelling mysteries, thrillers, and detective stories.

## Quick Start

This agent helps you:
- Develop intricate plots with proper mystery structure
- Create complex, believable characters
- Write vivid scenes with tension and atmosphere
- Craft authentic dialogue with subtext
- Edit and polish your work

## Available Commands

Use these slash commands to quickly access specialized functionality:

- **`/outline`** - Generate a complete story outline with plot structure, characters, and clues
- **`/character`** - Create detailed character profiles with psychological depth
- **`/scene`** - Write specific scenes with proper pacing and atmosphere
- **`/dialogue`** - Generate authentic dialogue with character-specific voices
- **`/plot-twist`** - Brainstorm and develop surprising plot twists
- **`/edit`** - Edit and improve existing text for clarity and impact

## Project Structure

This repository is organized to keep your writing projects tidy:

```
Crime-fiction-writer/
├── .claude/
│   ├── subagents/          # Specialized AI agents for different tasks
│   └── commands/           # Slash command definitions
├── characters/             # Character profile files
├── outlines/              # Story outline files
├── scenes/                # Individual scene drafts
├── manuscript/            # Full chapters and manuscripts
├── timeline.md           # Chronological timeline of events
├── clues.md              # Tracking clues and red herrings
└── Claude.md             # Main agent configuration
```

## Workflow Suggestions

### Starting a New Story

1. Use **`/outline`** to create your story structure
2. Use **`/character`** to develop your main characters (detective, suspects, victim)
3. Review and update `timeline.md` with key events
4. Update `clues.md` to track mystery elements

### Writing Your Story

1. Use **`/scene`** to write individual scenes
2. Use **`/dialogue`** when you need to focus on conversations
3. Save scenes to `scenes/` directory
4. Organize complete chapters in `manuscript/`

### Improving Your Draft

1. Use **`/edit`** to polish individual scenes or chapters
2. Use **`/plot-twist`** if you need to add complications
3. Review `timeline.md` and `clues.md` for consistency

## Specialized Subagents

This agent uses specialized subagents for deep expertise:

- **character-developer**: Creates rich, three-dimensional characters
- **plot-outliner**: Develops detailed plot structures and outlines
- **scene-writer**: Writes vivid, engaging scenes
- **dialogue-writer**: Crafts authentic, character-specific dialogue
- **editor**: Improves existing text for clarity and impact

You don't need to call these directly—the slash commands will use them automatically.

## Tips for Great Crime Fiction

1. **Fair Play**: Ensure attentive readers can solve the mystery with the clues provided
2. **Character-Driven**: Even plot-heavy mysteries need compelling characters
3. **Pacing**: Balance investigation with action and character moments
4. **Clue Placement**: Plant clues throughout, not all at the end
5. **Red Herrings**: Use 2-3 false leads that have believable explanations
6. **Stakes**: Make it matter—give readers a reason to care about solving the mystery
7. **Atmosphere**: Use setting and sensory details to create mood
8. **Consistency**: Track timeline, alibis, and evidence carefully

## File Organization Best Practices

### Characters
Save as: `characters/[role]-[name].md`
- Example: `detective-sarah-chen.md`
- Example: `suspect-marcus-williams.md`

### Scenes
Save as: `scenes/[number]-[description].md`
- Example: `01-crime-scene-discovery.md`
- Example: `15-interrogation-marcus.md`

### Outlines
Save as: `outlines/[story-title]-outline.md`
- Example: `outlines/the-midnight-killer-outline.md`

## Getting Help

Ask your Crime Fiction Writing Agent:
- "How do I structure a mystery plot?"
- "Help me create a detective character"
- "What makes a good plot twist?"
- "How can I improve this dialogue?"
- "What clues should I plant in Act 1?"

The agent has deep knowledge of crime fiction techniques, mystery structure, and writing craft.

## Subgenres Supported

- **Cozy Mysteries**: Amateur sleuths, small town settings, lighter tone
- **Hard-Boiled Detective**: Cynical PI, urban setting, gritty realism
- **Police Procedurals**: Realistic investigation, teamwork, procedure
- **Psychological Thrillers**: Mind games, unreliable narrators, suspense
- **Noir**: Moral ambiguity, dark atmosphere, fatalism
- **Legal Thrillers**: Courtroom drama, lawyers as protagonists
- **Amateur Detective**: Ordinary person turned investigator

## Additional Resources

The agent follows best practices from:
- Classic mystery structure (Agatha Christie, Dorothy Sayers)
- Modern thriller pacing (Gillian Flynn, Tana French)
- Character-driven crime fiction (Kate Atkinson, Louise Penny)
- Procedural accuracy (Michael Connelly, Karin Slaughter)

---

**Ready to write?** Start a conversation with your agent and begin creating your crime fiction masterpiece!

Example: "I want to write a locked-room mystery set in a tech startup. Can you help me outline it?"
