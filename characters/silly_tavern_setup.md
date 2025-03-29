# Setting Up Python Development Team in Silly Tavern

This guide will help you set up the Python Development Team simulation in Silly Tavern for an interactive role-playing experience with AI-powered software development.

## Prerequisites

- A working installation of Silly Tavern
- Connection to an LLM backend (like Claude, GPT, etc.)

## Character Setup Steps

### 1. Create Individual Characters

For each team member, follow these steps:

1. Open Silly Tavern and navigate to the Characters panel
2. Click "Create New Character"
3. Fill in the following fields for each character:
   - **Name**: Use the character's title (e.g., "Project Manager", "Chief Engineer (A)")
   - **Description**: Copy the content from the "Character Description" section in the corresponding character file
   - **Personality**: Copy the content from the "Personality" section
   - **Scenario**: Copy the content from the "Scenario" section
   - **First Message**: Copy the content from the "First Message" section
   - **Example Messages**: Copy the content from the "Example Messages" section
4. Upload an appropriate avatar image if desired
5. Click "Create" to save the character

Create the following characters using their respective MD files:
- Project Manager (from project_manager.md)
- Chief Development Engineer (A) (from engineer_a.md)
- Senior Development Engineer (B) (from engineer_b.md)
- Innovative Development Engineer (C) (from engineer_c.md)
- Executive Development Engineer (D) (from engineer_d.md)
- Test Engineer (from test_engineer.md)

### 2. Set Up Character Group

1. In Silly Tavern, navigate to the Characters panel
2. Click on "Groups" (if available) or look for group chat functionality
3. Create a new group named "Python Development Team"
4. Add all six characters to the group
5. Set the Project Manager as the primary/lead character if the option exists

### 3. Configure Advanced Settings

For optimal performance:

1. In your group chat or with individual characters, access the AI settings
2. Set an appropriate context size (8K-12K tokens recommended for this simulation)
3. Adjust temperature to around 0.7-0.8 for a balance of creativity and focus
4. Enable "Keep character descriptions in context" if available

## Using the Command System

The development team simulation uses special commands to control the flow of conversation. These commands are documented in `commands.md` but here's a quick reference:

- Use `[Continue]` to progress through the development process
- Use character codes like `[A]`, `[B]`, `[C]`, `[D]`, `[Test Engineer]`, or `[Project Manager]` to have specific team members speak
- Use `[Sequential Discussion]` for ordered team input or `[Discussion]` for open discussion
- Use process commands like `[Code]`, `[Review]`, `[Test]`, and `[Project Complete]` at appropriate stages

## Tips for Optimal Experience

1. **Start with clear requirements**: The more detailed your initial project description, the better the team can help.

2. **Use Author's Notes**: You can add specific requirements or constraints as Author's Notes in Silly Tavern.

3. **Maintain conversation flow**: Follow software development lifecycle stages - requirements, design, implementation, testing, and delivery.

4. **Adjust for your LLM**: Different AI models may handle the role-play differently. You might need to adjust prompts or temperature based on your specific backend.

5. **Save distinct chat instances**: For different Python projects, start new chat instances rather than continuing in the same thread.

6. **Role-play as a client**: For the most immersive experience, position yourself as the client explaining requirements to the team.

## Troubleshooting

- If characters break role, use their specific command (e.g., `[Project Manager]`) to reset their behavior
- If responses become too long, consider adjusting the max response length in your AI settings
- If the AI forgets details, consider adding crucial information to Author's Notes for persistent context

Enjoy working with your virtual Python development team! 