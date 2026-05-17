# Velvet Forge Compact Realism

A SillyTavern Chat Completion preset built as a modified merge of several roleplay preset styles, including Megumin/Freaky/Frankenstein-style prompt ideas, tuned into a compact short-message format inspired by character.ai pacing.

## What It Is

This preset is intended for fast, compact roleplay replies with a realistic tone and short message rhythm. It keeps the output direct, reactive, and scene-focused instead of long essay-style narration.

The included preset file is:

`Velvet Forge Compact Realism.json`

## Main Traits

- Compact CAI-style responses
- Short-message pacing
- Realistic scene handling
- NanoGPT-oriented configuration
- GLM 5.1 thinking model target
- 65k context setting
- 5k response cap
- Semi prompt post-processing
- Modular prompt blocks for style, permissions, vocabulary, agency, challenge, CYOA, inner thoughts, sound effects, and hybrid POV
- Picture-format module included but disabled by default

## Install

1. Open SillyTavern.
2. Go to `API Connections`.
3. Open the preset/import menu for Chat Completion settings.
4. Import `Velvet Forge Compact Realism.json`.
5. Select the imported preset.

You can also place the JSON file into:

`data/default-user/OpenAI Settings/`

Then restart or refresh SillyTavern so it appears in the preset list.

## Notes

This is a merged and modified preset, not a clean upstream copy of any single preset. It combines compact roleplay formatting, realistic response constraints, optional image/picture formatting, and multiple scene-control modules into one preset.

Basic smoke testing was done and it worked with DeepSeek V4 Pro and GLM 5.1. Other models have not been tested at all.

The preset is designed for private SillyTavern roleplay use. Review and adjust prompt blocks before sharing or using with different model providers.
