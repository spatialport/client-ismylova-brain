# CLAUDE.md — client-ismylova-brain

Tenant: **ismylova**. Authority: **alex-bellesia**.

## The five hard rules

1. **Single tenant.** Nothing in this repo may come from, or leak to, another client's brain or session.
2. **Task state lives in NXTO** (`dashboard://ismylova`), never in Markdown. `50-tasks/` is a generated view.
3. **Propose, don't accept.** Every record you write is `status: proposed`. Acceptance is a PR merged by Alex. Never broaden `access_scope` yourself.
4. **No secrets.** Reference URIs only (`password-manager://spatial-port/ismylova`, …). The site gate password is stored in the password manager, not here.
5. **Raw stays out.** Transcripts, raw email/WhatsApp threads become redacted evidence with a `source_ref`; never `access_scope: client`.

## Client-specific cautions (from accepted working rules)

- Never reveal, in any client-facing material, that the competing agency's offer was seen.
- The word "AI" never appears in client-facing decks (single exception: the Backstage slide of the digital deck).
- "IS MY LOVA" is always written spaced. Never invent stylist names. Never diminish the boutique; copy addresses the future, never current weaknesses.
- Design system: zero border-radius, no gradients over photographs (event deck).
- The community is never called a "club" (working name: The LOVA Circle).
- Designer-facing documents (e.g. simkhai deck) never contain figures or the commercial section.
