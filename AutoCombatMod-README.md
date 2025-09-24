# Auto Combat Mod

AI automatically plays your combat turns with smart action selection and targeting.

## Features

- **F2 Key**: Toggle auto-combat on/off instantly
- **Visual Toggle**: Top-left corner "AUTO-COMBAT: ON/OFF" button with color states
- **Smart AI**: Uses monster's own skills only, validates resource costs
- **Intelligent Targeting**: Heals allies when injured, attacks weakest enemies
- **Resource Aware**: Skips abilities when no orbs/aether available
- **Immediate Takeover**: Activating mid-combat takes over current turn instantly

## AI Behavior

- **Action Priority**: Works backwards through skill list (powerful abilities first)
- **Skill Validation**: Only uses skills the current monster actually possesses
- **Target Selection**: Context-aware (heals allies <80% HP, attacks enemies)
- **Resource Management**: Validates orb/aether costs before using abilities
- **Fallback**: Uses basic attack only when all special abilities fail

## Installation

1. Place `AutoCombatMod.dll` in `BepInEx/plugins/` folder
2. Launch Aethermancer
3. Press F2 to toggle auto-combat during combat

## Usage

- **Enable**: Press F2 or click UI button to activate
- **Monitor**: Watch console for AI decision-making
- **Disable**: Press F2 again to return to manual control

**Author**: MTKUSH (stronger9535)