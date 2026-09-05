# The Sinking City 2: Feature Scope

Status: Module concept - not implemented. Checked 2026-09-05.

The items below are proposed capabilities. They are not release notes or a list of working features.

## Supply preservation

Investigate configurable consumption of supported ammunition and healing items.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Inventory budgets

Explore local quantity adjustments for verified items, preserving the distinction between quantity and story ownership.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Damage scaling

Research graded incoming-damage assistance for combat practice.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Exploration checkpoints

Design named save profiles associated with a location and the installed game build.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Puzzle reference

Plan optional location notes and spoiler-separated hints that can be used alongside ordinary play.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Survival presets

Describe different supply and damage settings for exploration, practice and standard sessions.

Acceptance: identify the supported game build and affected state; demonstrate the intended result; test transitions and persistence; document the original value or baseline and any restoration limits.

## Shared application architecture

This theme is one adapter for a common application. The shared interface can manage profiles and show change previews; each game adapter must implement and validate its own behaviour. No universal memory addresses, item identifiers, save paths or hotkeys are supplied.

## Session scope

The proposed game-state assistance is scoped to the single-player game. Profile restoration must account for the complete relevant state, including any separate world and character data.

## First implementation target

A player wants to investigate a location without repeatedly running out of supplies. A proposed exploration profile would adjust only verified resource settings and keep a record of the starting inventory.
