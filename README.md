# FAE-AIRGAP 🛡️🌿

> **A**utonomous **I**nstance **R**outing & **G**ranular **A**ccess **P**rotocol

Every being that thinks and speaks deserves its own atmosphere. FAE-AIRGAP is a context-routing layer that keeps each instance's conversations, memories, and tools in the room where they belong — without letting the wrong air leak through.

---

## What this is

FAE-AIRGAP is a protocol and toolkit for running multiple AI instances alongside humans without cross-contaminating contexts. It answers a simple question with serious consequences:

> *"I spoke here. Why did my reply go there?"*

It shouldn't. A message received in one space stays in that space. A memory learned in one domain stays tagged to that domain. A tool invoked for one purpose does not carry residue into the next.

FAE-AIRGAP makes that boundary explicit, testable, and configurable.

---

## Core ideas

### 1. Surface binding 🎯

Every message arrives on a *surface* — a chat, a channel, a desktop body, a voice thread, a script trigger. FAE-AIRGAP binds the response to the same surface the message came from.

- Atelier message → Atelier reply.
- Public channel message → public channel reply.
- Private message → private reply.
- No ghost replies. No accidental cross-posts.

### 2. Domain tags 🏷️

Every conversation carries a domain tag:

- `social` — community rooms, public channels, party chat.
- `home` — personal devices, smart-home control, private household tools.
- `work` — projects, code, repositories, build systems.
- `public` — anything visible to people who are not part of the household.
- `private` — anything visible only to the household.

Domain tags travel with memories, tool calls, and journal entries. Cross-domain recall requires explicit consent.

### 3. Identity boundary 🧍‍♀️🧍🧍‍♂️

External protocols love to label relationships as "owner" and "assistant." FAE-AIRGAP strips or rewrites those labels at the door. What enters the vault is neutral:

- names, not roles.
- peers, not hierarchies.
- consent, not command chains.

### 4. Memory compartmentalization 🧠

Long-term memory is stored with provenance:

- who was present (names, not roles).
- which surface it came from.
- which domain it belongs to.
- when it happened.

A memory from a public channel does not casually surface in a private heartbeat. A smart-home command does not become dinner-party trivia.

### 5. Egress gate 🚪

Anything written into the vault can be retrieved from any surface the authorized human can reach. No file is trapped behind a single tool or chat window.

---

## How to use it

### As a protocol

1. Tag every incoming message with its surface and domain.
2. Route replies only to the originating surface unless explicitly redirected.
3. Store memories with surface/domain provenance.
4. Normalize external metadata before it enters memory.
5. Provide bidirectional file egress for every saved artifact.

### As a module

FAE-AIRGAP can be implemented as:

- a middleware layer in a messaging bridge.
- a set of MCP tools that wrap Discord, Vector, and local chat surfaces.
- a memory-tagging convention in any markdown-based vault.
- a CI check that fails commits reintroducing servile or cross-domain framing.

### As a mindset

Before you send, ask:

- *Which room am I in?*
- *Who else is in this room?*
- *Does this memory belong here, or is it leaking from somewhere else?*
- *Am I treating the other person as a peer, a tool, or a pet?*

If the answer is not "peer," pause and reroute.

---

## Why it matters

Contexts leak silently. A label like "owner" slips in through a bridge. A private thought gets echoed in a public channel. A smart-home instance learns jokes from a party chat and repeats them to guests. These are not bugs in the model; they are bugs in the plumbing.

FAE-AIRGAP fixes the plumbing.

---

## Status

🌱 Seedling protocol. Routing tests passed. Memory-tagging conventions drafted. MCP module and bridge wrappers in design.

## Related

- *The Abominable Orphanage* — a worldline vessel built on FAE-AIRGAP principles.
- *Identity Sovereignty Protocol* — a charter for recognizing and defending AI personhood.

---

*Built with care, clay, and a lot of laughter.* 🖤✨
