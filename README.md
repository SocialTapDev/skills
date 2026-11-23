# SocialTap Agent Skill

SocialTap is the social media scraper API for developers and AI agents. Send a public link, a handle or a search and get live data back in one schema. Failed requests are free.

This skill teaches your coding agent when to use the SocialTap API and how to call it, with every endpoint and its inputs. It works in Claude Code, Codex, Cursor, Grok Build and any agent that loads skills (SKILL.md).

## Install

```sh
npx skills add SocialTapDev/skills
```

## Skills

| Skill | What it does |
| --- | --- |
| [socialtap](skills/socialtap/SKILL.md) | Get live public social media data with the SocialTap API: activity, ads, albums, comments, communities, contribution calendars, downloads, effects, embeds, engagement stats, events, hashtags, issues, jobs, livestreams, offers, places, playlists, podcasts, posts, products, profiles, readmes, relationships, releases, repositories, reviews, sounds, suggestions, topics, transcripts, trends, usernames, web pages and web results from Amazon, Apple Music, Bluesky, Facebook, Facebook Ad Library, Facebook Marketplace, Facebook Events, GitHub, Google Ads Transparency Center, Hacker News, Instagram, Kick, Komi, Kwai, Lnk.Bio, LinkedIn, LinkedIn Ad Library, Linkme, Linktree, Pillar, Pinterest, Reddit, Rumble, Snapchat, SoundCloud, Spotify, Telegram, Threads, TikTok, TikTok Ad Library, TikTok Shop, Truth Social, Twitch, X and YouTube. One API key, one schema per kind of data, and you pay only for successful requests. Use when the user asks to get, scrape, search, download or analyze public data from any of these platf… |

## More

- Get an API key: https://socialtap.dev/signup/
- Docs for agents: https://socialtap.dev/llms.txt
- The same skill on the site: https://socialtap.dev/.well-known/agent-skills/socialtap/SKILL.md
- MCP server: https://github.com/SocialTapDev/socialtap-mcp
- SDKs: [Go](https://github.com/SocialTapDev/socialtap-go) · [Python](https://github.com/SocialTapDev/socialtap-python) · [TypeScript](https://github.com/SocialTapDev/socialtap-node)

---

This repository is generated from the SocialTap catalog. Questions: support@socialtap.dev.
