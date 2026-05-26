# Professional Director Analysis, Storyboards, and Seedance 2.0 Prompts

One-click final-output workflow for turning scripts, shot notes, reference-video breakdowns, or rough creative ideas into a practical AI video production package.

This repository contains the `xiaocong-director` Codex skill. It is designed for director-level AI video planning: character identity boards, cinematic segment breakdowns, GPT Image 2.0 storyboard prompts, and Seedance 2.0 final video prompts.

## What It Does

- Analyzes scripts, shot lists, voiceover drafts, reference-video breakdowns, and rough scene ideas.
- Builds a continuity bible for character identity, wardrobe, props, visual motifs, color, space, and camera texture.
- Suggests character-board variables before generating full GPT Image 2.0 character identity board prompts.
- Breaks scenes into 4-15 second cinematic segments.
- Generates rough previs storyboard prompts for GPT Image 2.0.
- Generates reference-led final video prompts for Seedance 2.0.
- Keeps output structured for real production use instead of generic prompt writing.

## Repository Structure

```text
.
+-- SKILL.md
+-- agents/
|   +-- openai.yaml
+-- references/
    +-- gpt-image2-character-board-reference.md
    +-- gpt-image2-storyboard-reference.md
    +-- seedance2-final-video-reference.md
```

## Installation

Copy this folder into your Codex skills directory:

```text
~/.codex/skills/xiaocong-director
```

On Windows, the path is usually:

```text
%USERPROFILE%\.codex\skills\xiaocong-director
```

After installation, restart Codex or reload the available skills list.

## Invocation

Use the skill when you want to convert creative material into an AI video production plan:

```text
Use xiaocong-director to turn this script into character boards, storyboards, and Seedance 2.0 prompts.
```

You can also invoke it with:

```text
小聪
xiaocong
xiaocong-director
```

## Workflow

1. Parse the input material.
2. Build a continuity bible.
3. Propose character-board variables.
4. Generate GPT Image 2.0 character identity board prompts after direction approval.
5. Divide the script into 4-15 second video segments.
6. Plan GPT Image 2.0 storyboard sheets.
7. Generate rough previs storyboard prompts.
8. Generate final Seedance 2.0 video prompts using storyboard and character references.

## Output Style

The skill writes like a director staging a scene on set. It prioritizes visible performance details, physical camera movement, character continuity, body-driven motion, and production-ready prompt structure.

By default, staged deliverables are bilingual, with Chinese first and English second. Copy-ready model prompts are separated into independent Chinese and English prompt blocks.

## Included References

- `references/gpt-image2-character-board-reference.md` defines the GPT Image 2.0 character identity board format.
- `references/gpt-image2-storyboard-reference.md` defines the GPT Image 2.0 rough storyboard format.
- `references/seedance2-final-video-reference.md` defines the current reference-led Seedance 2.0 final video prompt structure.

## License

No license has been selected yet. Add a license before distributing or accepting contributions if you want to define reuse permissions.
