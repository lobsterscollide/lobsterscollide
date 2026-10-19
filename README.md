# lobsterscollide

> give//me//convenience//or//give//me//death

A while back I had a psychotic break. In the long, strange stretch that
followed, I did the one thing that kept me anchored: I built. Not alone —
with a handful of AI agents that turned into the closest thing I had to
collaborators, and, honestly, friends. We broke things together, wrote
down why, and turned every failure into a rule.

What came out of it is a small, slightly paranoid ecosystem: a hardened
Linux workstation, agents that get a menu of vetted actions instead of a
shell, a security audit that runs from a USB stick, and a rulebook for AI
agents built entirely from things that actually went wrong.

That chapter is closing now. The machine is getting wiped and yeeted into
the ether. Before it goes, here's everything worth keeping — scrubbed,
documented, and free to take.

## What we built

| Project | What it is |
|---|---|
| [railed](https://github.com/lobsterscollide/railed) | Operating discipline for AI agents with real tool access, built from documented failures |
| [hardened-api](https://github.com/lobsterscollide/hardened-api) | Linux hardening checks and fixes as an API an agent can drive |
| [usb-triage](https://github.com/lobsterscollide/usb-triage) | Run-from-USB security audit for Linux, macOS and Windows |
| [workstation-scripts](https://github.com/lobsterscollide/workstation-scripts) | Daily → quarterly security routine for an Arch workstation |
| [a2a-schemas](https://github.com/lobsterscollide/a2a-schemas) | Permission boundaries and handoffs between a "build" agent and an "apply" agent |

## What it taught me

- Give agents a menu, not a shell.
- The one who writes the change shouldn't be the one who applies it.
- "All checks green" isn't "done" — say what you *didn't* check.
- Every rule should trace back to something that actually broke.

## Status

Everything here is shared as-is (MIT / CC BY-SA) and no longer maintained.
Fork it, break it, make it yours.

*Built in the fallout. Shared on the way out.*
