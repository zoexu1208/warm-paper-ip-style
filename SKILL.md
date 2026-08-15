---
name: warm-paper-ip-style
description: Apply a warm, tactile, hand-painted visual language consistently across personal IP characters, illustrations, websites, portfolios, content cards, and social assets. Use when Codex needs to extend the user's approved watercolor-gouache-crayon style into a new medium, create or review a personal website in the same visual world, or generate/refine a person-based IP while preserving identity anchors.
---

# Warm Paper IP Style

## Overview

Treat this as a cross-media visual system, not a narrow illustration preset. It combines warm paper texture, matte hand-painted materials, organic rounded contours, gentle colors, rounded character forms, playful everyday emotion, and disciplined whitespace. The goal is for a person, illustration, website, and content artifact to feel authored by the same person without making every medium look like a literal painting.

The detailed fingerprint and medium translations live in [references/style-system.md](references/style-system.md). When the work involves the user's established person-based IP, also read [references/character-lock.md](references/character-lock.md).

## Operating Rules

1. Separate identity from style. Identity includes a person's visible, authorized anchors; style includes material, line, shape, proportion, palette, light, texture, composition, and emotional register.
2. Use the selected style fingerprint as the source of truth. Do not substitute a generic “cute,” “watercolor,” “editorial,” or “minimal” style without stating the change.
3. Preserve function. For websites and content systems, visitors must still understand who the person is, what they do, and what to explore. Hand-painted decoration is not a replacement for hierarchy, readability, or clear actions.
4. Use one memorable visual risk at a time. Keep the surrounding layout quiet and intentional; remove decorative elements that do not reinforce the subject or improve navigation.
5. Keep the style warm and tactile, never plastic, glossy, neon, photoreal, or over-rendered. Do not drift toward 3D toy, BJD, collectible figure, generic vector, or busy scrapbook aesthetics.
6. Do not store user portraits in this skill. Use only authorized photos or approved IP images supplied at runtime. Do not infer sensitive attributes.

## Workflow

### 1. Define the medium and its job

State whether the task is a person-based IP, original character, illustration, personal website, portfolio, content card, presentation, or another artifact. Name the audience and the single job of the output. For a website, prioritize visitor understanding and useful next actions over decoration.

### 2. Load the right references

- Always read `references/style-system.md` for any task.
- Read `references/character-lock.md` when the user's established IP or a real person is involved.
- For image generation or person-based IP creation, also follow the `personal-ip-generator` skill and its required references. Do not bypass its one-question-at-a-time wizard or approval gates.

### 3. Build a compact style lock

Before implementation or generation, record:

- medium and audience;
- identity anchors or original-character brief, separately from style;
- line, shape, proportion, material, palette, light, texture, composition, and background;
- emotional keywords and negative constraints;
- which parts are fixed and which parts may vary.

### 4. Translate instead of copying

Apply the medium-specific guidance from `references/style-system.md`. Keep the shared DNA visible, but let the medium retain its own grammar: characters can be expressive, while a website must remain scannable; a content card can be tactile, while body copy must remain readable.

### 5. Review for drift

Check the result against these questions:

- Does it feel warm, tactile, human, and quietly playful?
- Are the paper/material cues visible but restrained?
- Are the character's identity anchors stable when a person is involved?
- Does the color palette feel coordinated rather than loud?
- Is the layout readable without the illustration?
- Would the next artifact from another medium still belong to the same visual world?

## Person-Based IP Guardrails

When creating or refining the user's established person-based IP, use the approved character lock in `references/character-lock.md`, but do not treat it as a general rule for all characters. Preserve recognizable, non-sensitive anchors from an authorized source; change only the approved style, outfit, pose, expression, or scene variables. Never copy a style reference's depicted person, pose, props, text, logo, watermark, or composition.

For generation, keep the staged flow from `personal-ip-generator`: resolve IP mode and authorized source, resolve style, collect enhanced traits and palette, show the prompt lock, obtain approval, generate the six-variant overview, select a candidate, and only then generate final avatar/expression deliverables.

## Prompt Assembly

Use this order when writing a prompt or implementation brief:

1. medium and purpose;
2. identity lock or original-character brief;
3. shared warm-paper style fingerprint;
4. medium-specific translation;
5. palette and composition;
6. fixed elements and allowed variations;
7. negative constraints.

Do not reduce the style to the phrase “彩绘风.” Use concrete visual variables from the reference file.

## Handoff Format

When handing off a completed style decision, provide:

```markdown
风格名称：温暖纸感手绘风
适用媒介：人物 / 插画 / 网页 / 内容展示
共享视觉 DNA：...
人物身份锁：...
媒介转译：...
固定规则：...
允许变化：...
禁止漂移：...
```
