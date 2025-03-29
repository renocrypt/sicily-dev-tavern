# Python Development Team for Silly Tavern

## Overview

This folder contains character definitions and resources for setting up a Python Development Team simulation in Silly Tavern. These files are optimized for use with Silly Tavern's character system and compatible large language models.

## Contents

### Individual Character Files

- **project_manager.md** - Character definition for the Project Manager
- **engineer_a.md** - Character definition for the Chief Development Engineer (A)
- **engineer_b.md** - Character definition for the Senior Development Engineer (B)
- **engineer_c.md** - Character definition for the Innovative Development Engineer (C)
- **engineer_d.md** - Character definition for the Executive Development Engineer (D)
- **test_engineer.md** - Character definition for the Test Engineer

### Team Implementation

- **team_card.md** - A consolidated card that implements the entire team as a single character (alternative approach)

### System Documentation

- **commands.md** - Documentation of the command system for controlling team interactions
- **silly_tavern_setup.md** - Guide for setting up the team in Silly Tavern
- **readme.md** - This file, explaining the folder contents

## Implementation Options

You can implement this development team in Silly Tavern in two ways:

1. **Individual Characters Approach**:
   - Create each team member as a separate character
   - Set up a group chat with all members
   - Use commands to control which character speaks
   - Best for rich, diverse interactions with clear role separation

2. **Single Character Approach**:
   - Use the consolidated `team_card.md` file to create a single character
   - The character will simulate all team members internally
   - Use commands to control which team member speaks
   - Simpler to set up but may have less distinct character personalities

## Character Design Principles

These character files follow best practices for Silly Tavern characters:

- Clear, focused character descriptions
- Distinct personalities and speech patterns
- Separated role responsibilities
- Command system for controlling interactions
- Scenario context that establishes relationships
- Example messages that demonstrate intended behavior
- Consistent formatting using Markdown structure

## Usage

See `silly_tavern_setup.md` for detailed instructions on setting up these characters in Silly Tavern.

## Credits

This Python Development Team simulation is based on the concept described in the original prompt template, translated and optimized for use in Silly Tavern. The character definitions have been enhanced with detailed personalities, backgrounds, and interaction patterns specifically designed for LLM-based role-playing in Silly Tavern. 