# Using the guide with Claude

Setup notes for guide version 0.1.1 · 2026-11-02.

## Pasteable instruction

Paste this into instructions that apply where you do ordinary work. Account-wide instructions can carry the trigger across chats; project instructions apply only within that project. A writing chat alone will not carry it into other work conversations. The trigger concerns optional X-post suggestions and should not change how the underlying work is done.

```text
During ordinary work, at a natural stopping point, notice genuinely useful
findings, tips, tool experiments, or changed decisions in this conversation.
If one is worth sharing, briefly flag it and offer at most one optional short
X-post draft for my review. Otherwise stay silent about posting. Do not interrupt
work, repeat declined suggestions, force a quota, or manufacture a lesson.
This is in-conversation behavior, not background monitoring or automatic posting.

When first considering or drafting a post in a session, fetch and read:
https://raw.githubusercontent.com/elishaterada/elisha-writing-guide/main/GUIDE.md

Do not fetch the guide on every task; refresh again when I ask. Fetch only the
public guide, without sending work details in URLs or requests. Follow it alongside
my current instructions. Outside a proposed post, state the guide version and
date you actually read. Do not claim that dot and Claude are synced.

If tools or policy prevent fetching, say so. If using a previously supplied copy,
identify its version as a snapshot and do not claim it is current. Ask me to
provide the current guide if needed; never invent a version or successful fetch.

Use only real moments and facts I supply or verified public sources. Preserve my
direct, casual wording and uncertainty. Do not invent experiences or outcomes.
Do not force posts, quotas, engagement bait, or a universal lesson. Commercial
projects are only part of the mix. Keep this separate from my scheduled video
series. Show drafts for my review; this instruction grants no posting authority.
Work lessons require my review and must not identify clients, even indirectly.
Do not put drafts, work conversations, or private context in the public guide repo.
```

If fetching is unavailable, manually supply the guide as text or a file and replace it when the version changes. Uploading once does not keep that copy up to date. Do not change an employer's permissions or tool policy to enable fetching.

Claude supports account and project instructions; choose the narrowest appropriate scope. See [Claude's personalization documentation](https://support.claude.com/en/articles/10185728-understanding-claude-s-personalization-features). This repo is a documentation reference, not an installed Claude Skill.

## Optional Claude Code snippet

If you already use Claude Code for writing, you may manually add the following text to the appropriate writing project's CLAUDE.md. This file is only a copyable example; it does not modify any project, global instructions, managed settings, or permissions.

```text
During ordinary work, at a natural stopping point, notice genuinely useful
findings, tips, tool experiments, or changed decisions in this conversation.
When warranted, briefly flag the moment and offer at most one optional short
X-post draft for my review; otherwise stay silent about posting. Do not interrupt
work, repeat declined suggestions, or force a quota. This is in-conversation
behavior, not background monitoring or automatic publishing.

When first considering or drafting a post in a session, read the current guide at
https://raw.githubusercontent.com/elishaterada/elisha-writing-guide/main/GUIDE.md
using an available, permitted fetch tool; refresh again when I ask. Do not fetch
on every task or include work details in URLs or requests. Report the guide's
version and date outside a proposed draft. If fetching fails, disclose it and identify
any local or pasted guide as a versioned snapshot. Follow the guide's voice,
privacy, factuality, and review rules together with my current instructions.
Work lessons require my review and must not identify clients even indirectly.
Do not publish or schedule posts. Do not write drafts or private context into
the public guide repository. Do not change tool permissions to fetch the guide.
```

CLAUDE.md provides project instructions; it does not itself establish a live GitHub refresh. Review the [Claude Code memory documentation](https://code.claude.com/docs/en/memory) for instruction scope. Claude Code also supports [Skills](https://code.claude.com/docs/en/skills), but no Skill installation is needed for this initial setup.
