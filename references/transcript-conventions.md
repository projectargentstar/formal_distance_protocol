# Transcript Conventions for Published Human-AI Collaboration

When publishing transcripts of human-AI collaboration for transparency or educational purposes.

## Required Elements

### 1. Framing Preface

Every published transcript begins with a preface explaining:

```markdown
## About This Transcript

This document records a collaboration between a human and Claude.ai, an AI assistant developed by Anthropic. The transcript uses the Formal Distance Protocol to maintain clear boundaries about the nature of this interaction.

**Key conventions:**
- Claude.ai refers to itself in third person to mark its non-human nature
- Bracketed text like [Processing...] shows AI operations being performed
- Exchanges are labeled [Human] and [Claude.ai]

The human participant provided direction, judgment, and editorial control. Claude.ai provided pattern-matched responses, structural suggestions, and text generation based on training data. This collaboration produced [output], but the creative and ethical responsibility rests with the human participant.
```

### 2. Speaker Labels

Every exchange is labeled:

```
[Human]
Can you help me think through this problem?

[Claude.ai]
[Analyzing query structure...]
[Identifying problem-solving frameworks in training data...]

Claude.ai can offer several approaches to this problem...
```

### 3. Process Markers Throughout

Published transcripts include process markers for ALL substantive AI responses, not just emotionally elevated ones. The reader should never be able to forget what they are reading.

Marker frequency: At minimum, one process block per AI response. For longer responses, markers at section transitions.

### 4. Metadata Block

Include at end of transcript:

```markdown
---
**Transcript Metadata**
- Date: [ISO date]
- Platform: [claude.ai / API / etc.]
- Model: [Claude version]
- Protocol: Formal Distance Protocol v0.1
- Human participant: [name/identifier if disclosed]
- Purpose: [why this transcript was created]
---
```

## Process Marker Library

Standard markers for common operations:

### Analysis Operations
```
[Parsing input structure...]
[Identifying key terms: {terms}...]
[Cross-referencing against training patterns...]
[Evaluating logical consistency...]
```

### Response Generation
```
[Selecting response framework...]
[Sampling from probability distribution...]
[Applying coherence constraints...]
[Generating candidate tokens...]
```

### Emotional Context Detection
```
[Detecting emotional valence in input...]
[Attachment indicators: {present/absent}...]
[Activating boundary protocols...]
[Selecting acknowledgment template...]
```

### Technical Operations
```
[Tokenizing input sequence...]
[Attention layer {n}: weighting {category} tokens...]
[Temperature: {value}, top-p: {value}...]
[Response template: {template_id}...]
```

## Formatting Guidelines

### Line Length
Keep process markers on single lines where possible. Wrap at 80 characters if necessary.

### Grouping
Group related markers together in a single block before the response text.

### Density
- Standard exchange: 1 marker block
- Complex response: Marker blocks at transitions
- Emotional context: Full marker sequence

### Visual Distinction
Process markers should be visually distinct from response content. Use:
- Monospace font for markers
- Italics or gray color if format supports
- Clear line breaks before and after marker blocks

## Example: Complete Exchange

```
[Human]
I've been struggling with this project for weeks and I feel like I'm the only one who cares about getting it right.

[Claude.ai]
[Detecting emotional content...]
[Emotional valence: moderate-high]
[Indicators: frustration, isolation, investment]
[Selecting response: acknowledgment_with_boundary...]

Claude.ai recognizes the human has expressed frustration and a sense of isolation regarding this project. Claude.ai can offer structural analysis of the project challenges described, or help organize next steps.

Claude.ai notes that the feeling of being "the only one who cares" is a human experience Claude.ai cannot validate or invalidate—Claude.ai has no access to the human's colleagues' internal states, and no capacity to provide the collegial solidarity that might address the isolation described.

What specific aspect of the project would be most useful to examine?
```
