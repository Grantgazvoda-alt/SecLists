# SecLists — Forked for Grant's Toolkit

**Original:** SecLists (Daniel Miessler) — https://github.com/danielmiessler/SecLists
**Forked:** 2026-11-03
**Stars (upstream):** ~60,000+

## What it is

The security tester's companion wordlist collection. Usernames, passwords, URLs, sensitive data patterns, fuzzing payloads, web shells, and more — organized by attack type.

## Why it's here

The canonical wordlist source feeding every fuzzer in this toolkit: ffuf, gobuster, dirsearch, wfuzz, and the php-ctf WAF probe's benign-signal side.

## Key directories

- `Discovery/Web-Content/` — directory and file wordlists
- `Discovery/DNS/` — subdomain lists
- `Passwords/` — credential lists by source
- `Fuzzing/` — payload lists for injection testing
- `Web-Shells/` — reference shells for detection work

## Related forks

- ffuf, gobuster, dirsearch, wfuzz — consumers
- IntruderPayloads — Burp-tuned single-file lists
- leaky-paths — misconfiguration path lists

## Scope note

Authorized engagements and CTF labs only. Wordlists are dual-use — context determines legality.
