---
name: mom-st-joe-time-machine
description: His mom Danielle runs the St. Joe Time Machine local-history page; her Claude setup page and findings live in the Hub.
metadata:
  node_type: memory
  type: project
  modified: 2026-10-21T02:24:47.782Z
---

His mom, Danielle, runs **St. Joe Time Machine** (facebook.com/Stjoetimemachine, also TikTok and Instagram): St. Joseph MO history from old newspapers, mostly Newspapers.com. She got Claude Pro in Oct 2026 and uses it mainly on her phone.

Setup page built 2026-10-20: https://claude.ai/artifact/NT67SajQoKL2iEqVJPEQzu (source `Hub\06 Creative Projects\St Joe Time Machine\claude-setup.html`). It holds her Project instructions, a screenshot workflow for Newspapers.com (no connector exists that I could find), 8 prompts, and her page stats.

**Why:** a 63-post read on 2026-10-20 showed videos at a median of 293 reactions and 19K views against 19 for text/photo posts. That was the main finding. Same day: TikTok had 1,594 followers and 27 videos (median 2,175 views; top was the Glore Psychiatric Museum tunnels at 21.4K), with the same video getting about 4 to 7 times more views on Facebook. Instagram had 9 posts and 1 follower. Correction from the Reels tab the same day: her all-time biggest Facebook videos are older than the 63-post scan, led by the Glore tunnels (80K, 22s of her own footage, music only), Krug Park (58K), the 1849 ferry fee (57K) and Blacksnake Hills (48K, 299 shares). Places and origin stories beat true crime on both apps. Commenters share memories, convert old prices, and ask follow-up questions. yt-dlp reads her TikToks; TikTok comments via yt-dlp failed; Facebook reel comments read via `[aria-label^="Comment by"]` in Chrome.

A skill for her account (`st-joe-time-machine`, with transcripts of her best videos) is zipped in the same Hub folder; it must be uploaded in a browser signed in to her account, not his. The setup page was made public ("anyone with the link") on 2026-10-20 at his request. Her Blacksnake Hills video says Lewis and Clark passed in 1805; NPS says July 1804 and September 1806.

GitHub repo (public): github.com/pmcgaughy98/St-Joe-Time-Machine, local clone at `D:\dev\st-joe-time-machine`. `knowledge/` syncs into her Project; the repo root is also a plugin marketplace ("time-machine-tools") holding her skill as plugin `st-joe-time-machine`. Update there and push; she taps Sync. Keep it public-safe. Free Library of Congress connector: https://libofcongress.caseyjhand.com/mcp.

**How to apply:** her account is separate from his; never carry his private context into her setup. Update the same artifact URL rather than making a new one. The Gemini MCP was broken that day (retired model, 404). Related: [[claude-surfaces-do-not-share-state]].
