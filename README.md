## Plan
The goal of this project is to write a visual novel game engine in Odin.
This will require rendering text in customisable formats, animating character sprites, and a scripting language to direct these functions. My aim is to allow a visual novel to be written in marked up text that is human interpretable.
### Stages
#### Phase 1
1. Game screen and rendering text.
2. Basic sprites and script parsing (text with markup for character sprites).
3. Essential animation features (sliding movement and layers for mouth movement/blinking) and text synchronisation.
4. Puppet theater animation, z-axis.
5. Add sound?
6. Nail down scripting syntax.
7. Documentation.
#### Phase 2
Script-writing/dev tools, live previews. Work out how LSP works and build a language server for scripting, creators can then define animations that can be reused and see descriptions of verbs while they write. Build a standard library of verbs to make it easy to get started.

## Philosophy
A visual novel should be written like a stage-play, with dialogue and stage directions for the characters. With the game assets (images and music) referenced in a simple, human readable form, the game script should evoke the experience of the visual novel. The layout of the visuals will take inspiration from the techniques of traditional cel animation, skeuomorphism is considered to be good design. The tools provided should be "batteries included", so they get out of the creator's way, but allow for tweaking as required. Software should not be opinionated, users should be.
