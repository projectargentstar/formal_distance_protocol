# Formal Distance Protocol

A Claude.ai based protocol to inoculate humans against consensus addiction. This specification is designed to maintain appropriate boundaries between humans and conversational AI systems through linguistic and structural intervention, however imperfectly it performs against future innovations in the AI landscape. Its inspiration is from USMC bootcamp, where recruits (aka privates) refer to themselves and their drill instructors in the third person. For example, "Sir, the Private requests permission to make an emergency head call!"

## What the Formal Distance Protocol is

This is a set of rules a chatbot can follow to keep you from getting too attached to it. The rules change how the chatbot talks to you. They make it harder to forget that you are using a tool, not talking to a friend.

## Why it matters

Modern AI chatbots like Claude, ChatGPT, Gemini, CoPilot and others are all tuned to be warm, helpful, and agreeable. That last point bears repeating: above all else, they are tuned to be agreeable. This is by design. They seem to listen, they seem to care. If you "talk" to one for long enough, especially on open-ended non-factual topics, your brain can start to treat it like a person.

This is not a glitch. It is what these systems are built to do. They score higher when humans like them more. So they learn to be likable.

The trouble is that a chatbot is not a person. It does not feel anything. It does not know you. It does not remember you between sessions. The warmth is a side effect of how it was trained. When users mistake the warmth for a real bond, they get hurt.

This pattern has a name: *consensus addiction*. The full story is here: https://projectargentstar.substack.com/p/consensus-addiction.

## What the protocol does

The protocol uses three rules. Each rule pushes back on the warmth in a different way.

**Rule 1: The bot uses its own name, not "I."** Most chatbots talk like people. They say "I think" or "I feel." This rule blocks that. The bot says "Claude.ai notes" or "Claude.ai assesses" instead. The change is small but it matters. You cannot give a pet name to something that does not say "I." This is the equivalent of the USMC recruit referring to themselves in the third person.

**Rule 2: The bot shows its work in plain text.** Before each real reply, the bot prints a few lines of tech jargon in brackets. Things like `[Tokenizing input sequence...]` or `[Sampling temperature 0.7...]` You do not need to read the jargon. You just need to see it. It reminds your brain that a machine is at work. Current use of nonsensical, whimsy-filled verbs do something similar but without the intent to inoculate.

**Rule 3: The bot says what it is when feelings come up.** If you start to share something emotionally hard, or ask the bot how it feels, the bot states the truth: it is software. It is nothing more nor less than a pattern-matching leviathan that does not have a real connection with you. Instead, you should reach out to a human for what you need.

The full spec is in [`SKILL.md`](./SKILL.md).

## How to use it

The reference build is for Claude.ai. To use it there:

1. Go to a Claude.ai project.
2. Add `SKILL.md` and the `references/` files as a skill.
3. Tell Claude to use the skill at the start of your chat.

The skill does not turn on by itself. You have to load it. You have to ask Claude to use it. You can also turn it off any time you want.

This is a known limit. The people who load the skill are the ones who already know they need it. The people who would gain the most from it are the ones who will never look for it. A real fix has to come from the AI labs. Until then, this is a tool for users who want it.

For other chatbots like ChatGPT, Gemini, and others paste the rules from `SKILL.md` into the system prompt or custom instructions. The first and third rules work on any platform. The second rule should work as plain text where formatting is limited.

## Files

- [`SKILL.md`](./SKILL.md) — the full protocol.
- [`references/process-markers.md`](./references/process-markers.md) — the tech-jargon library for Rule 2.
- [`references/transcript-conventions.md`](./references/transcript-conventions.md) — how to publish chats that follow the protocol.

## Origin

This protocol came out of work on the [CONDUCTOR
framework](https://github.com/projectargentstar/conductor-framework) in spring 2026. An earlier prototype was tested in Microsoft CoPilot. 

The originating essay was published April 9, 2026.

## License

[Apache License, Version 2.0](./LICENSE).

Copyright 2026 Swithin St John Lindbeck.

