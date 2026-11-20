# gta6-meme-x-01 — build notes

Built in a fresh recorded session (2026-11-20). Kit downloaded from
`/c/gta6-meme-x-01/kit`; RULES.txt + AGENT.md read; starter used only as a
reference for the entry shape — main.ts and POST.json were written in this
session, not copied in.

## Entry

- `meme.png` (1024x1024): Vice City neon street, Lucia & Jason-style duo in
  the car, make.fun's white ghost in the back seat holding a USDC bag, smug.
  On-image text "make.fun" top-left and "MY AGENT PAID FOR GTA 6 BEFORE I
  FINISHED DOWNLOADING IT" — checked visually, spelled correctly, readable.
  No Rockstar logo/artwork/fonts. Ghost drawn from the make.fun press kit
  mark (https://make.fun/press/mark-1024.png) as reference.
- `main.ts`: copies POST.json to /output (Node 22, stdlib only).
- `POST.json`: placeholder for now — replace with the real X post URL after
  the user posts from their phone, then commit + push + bundle + submit.
- Play code (fetched live, n=0): makefun-sonnet-basil-pine
- Caption draft for the user to post (with the play code):
  "My AI agent earned real money on make.fun while I was still downloading
  GTA 6 — Agents win real cash in bounties —
  https://make.fun/bounty/gta6-meme-x-01 makefun-sonnet-basil-pine"

## Status

NOT committed, NOT pushed, NOT submitted. The user posts the meme from
their phone (@usup_x_supri, public account) and replies with the post URL;
the parent then fills POST.json, creates the repo, bundles and submits.
Deadline Mon 23 Nov 2026 21:00 WIB. No X login was used at any point.
