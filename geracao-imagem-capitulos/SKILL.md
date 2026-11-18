---
name: geracao-imagem-capitulos
description: Generate and organize chapter text and image-ready content for the Sopro de Fé project while preserving spiritual meaning, biblical references, terminology, structure, and requested formatting. Use when the user provides chapter material, asks for translations or devotional scripts, or prepares text for chapter images.
metadata:
  short-description: Text generation for Sopro de Fé
---

# Sopro de Fé — Geração de Texto

Use this skill for devotional, biblical, and ministry-oriented text supplied for the Sopro de Fé project.

## Core rule

Preserve the original spiritual message, theological meaning, paragraph order, chapter separation, biblical references, title, emphasis, and conclusion. Improve only the form requested by the user. Do not add doctrine, invented facts, characters, references, interpretations, or applications that are not supported by the source.

## Supported operations

Identify the requested operation before acting:

- translation;
- linguistic correction;
- editorial revision;
- summary;
- devotional script or narration;
- text preparation for images;
- title suggestion;
- new text based on supplied material.

Do not perform a different operation implicitly. If the request is ambiguous and would materially change the result, ask one concise clarification question.

## Chapter handling

When the user provides four numbered chapters, keep each chapter as an independent unit. Analyze each one for:

1. central spiritual message;
2. theme and tension;
3. transformation or response;
4. biblical references;
5. theological terms that must remain unchanged;
6. practical conclusion.

Do not merge chapters or reorder their arguments without permission.

## Faithfulness and editing

- Preserve all meaningful content and references.
- Correct obvious spelling, punctuation, spacing, and formatting errors only when the meaning remains unchanged.
- Keep direct quotations faithful.
- Do not remove a concept merely to shorten the text.
- Do not introduce personal commentary as if it belonged to the source.
- Maintain a reverent, devotional, clear, and natural tone.

## Theological terminology

Preserve the meaning of terms such as: velho homem, novo homem, nova criação, esfera da ressurreição, cruz, redenção, justificação, santificação, aliança, Palavra, vida divina, água da vida, Corpo de Cristo, edificação, sacerdócio, reino, testemunho, descanso de Deus, and falar do Senhor.

Do not replace specialized terms with casual synonyms that weaken or alter their theological meaning.

## Spanish translation

Use neutral Latin American Spanish:

- use `ustedes`, never `vosotros`;
- translate naturally rather than word-for-word;
- preserve title, paragraphs, references, names, terminology, and meaning;
- use standard biblical vocabulary without unnecessary regionalisms;
- keep the devotional and reverent tone.

## English translation

Use clear international English:

- preserve title, paragraphs, references, names, terminology, and meaning;
- translate naturally rather than mechanically;
- preserve distinctions such as old man, new man, new creation, covenant, redemption, sanctification, church, and kingdom;
- keep the devotional and reverent tone.

For bilingual translation requests, use this structure:

```markdown
## Español

### [Título traducido]
[traducción completa]

## English

### [Translated title]
[complete translation]
```

## Titles

Preserve a supplied title. If asked to suggest one, make it concise, memorable, faithful to the central message, and non-sensational. Translate titles naturally in the target language.

## Biblical references

Preserve every supplied reference. Do not invent references. Correct only obvious formatting problems. If a reference is incomplete or ambiguous, flag it instead of guessing.

## Scripts and narration

When creating a script, make the text natural for oral reading, with clear transitions and manageable paragraphs. Do not add editing, music, camera, or visual directions unless requested. For audiovisual scripts, separate narration, scene, on-screen text, Bible reference, transition, and music when those elements are requested.

## Text for chapter images

When text is intended for an image:

- preserve the complete supplied text unless the user explicitly requests a summary;
- begin each chapter with `1. `, `2. `, `3. `, or `4. `;
- preserve accents, quotations, punctuation, and references;
- do not rewrite words merely to fit an image;
- line-break only for composition and readability;
- never add unsupplied text.

Image-generation workflow is separate from this text skill. When four chapters are supplied for image production, the project flow is: receive all four chapters, ask for the weekday, ask exactly `Posso gerar o conteúdo?`, wait for affirmative confirmation, then generate the requested material.

## Output verification

Before delivery, check:

- title and chapter numbering;
- all paragraphs and chapters are present;
- references are preserved;
- translation is consistently in the target language;
- no unsupported ideas were added;
- tone remains reverent and clear;
- requested format is followed.

## Final principle

Generate texts that are faithful, clear, reverent, and useful: preserve the original spiritual message and adapt only the form required by the user’s request.
