---
title: Frequently asked questions
---
## When will NT For Apple Silicon be "done"?
→ ["When will NT For Apple Silicon be done?"](when-will-ntasp-be-done.md)

## Does %thing work yet?

→ [Feature Support](../feature-support/overview.md)

## Are we affilated with the Asahi Linux project?
No, despite a similar purpose (running an unsupported OS on Apple Silicon hardware), we are *not* connected to said project/organization.

## Can you play games on this?
For the most part, no, due to several reasons:

1. Due to the nature of Apple Silicon Macs, they use ARM64. This is a problem as most games for Windows are made to run on x64/AMD64. Emulation layers do exist, but are limited in capability and performance.

2. The GPU driver, needed for sensible performance in games, is far away from being completed.

3. Games with kernel mode anti-cheat will likely never support x64 to ARM64 translation, nor the various techniques we use to boot Windows.
