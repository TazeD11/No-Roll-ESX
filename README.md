# No-Roll-ESX
Fivem No-Roll/ESX
# skyway-noroll

A lightweight FiveM script designed to prevent unwanted rolling while aiming with a scoped weapon, helping eliminate awkward movement states and freeze-like glitches during combat.

## Overview

This script is built for players who want smoother and more stable aiming behavior in FiveM. When a player is scoped in, the script blocks the roll action, preventing the character from entering unintended movement states that can feel broken or cause visual glitches.

## How it works

The script listens for the player's aiming state and checks whether the player is currently scoped or using a weapon that should not allow rolling. If the player attempts to roll while in that state, the script cancels or blocks the action.

This keeps movement consistent and prevents situations where:
- rolling triggers at the wrong time
- aiming + movement feels unstable
- player gets stuck in an awkward combat state
- the character appears to freeze or behave incorrectly

## Features

- Blocks roll actions while aiming with a scope
- Improves combat stability
- Lightweight and resource-friendly
- Simple integration with FiveM servers
- Easy to maintain and customize

## Installation

1. Download the script.
2. Place the folder in your `resources` directory.
3. Add this line to your `server.cfg`:

```cfg
ensure skyway-noroll

Requirements
FiveM server
ESX-based server environment
Standard FiveM resource setup
Usage
Once installed, the script works automatically. There is no complicated setup required for basic use.

The logic is simple:

if player is scoped/aiming
if the roll action is triggered
then the action is canceled
This makes the gameplay feel smoother and more controlled.

Notes
This script is designed to be minimal, fast, and easy to adapt. It focuses on one clear goal: prevent roll glitches during aiming.

Support
If you want updates, fixes, or custom modifications, feel free to contact me or open an issue in the repository.
