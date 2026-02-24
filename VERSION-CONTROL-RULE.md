# VERSION CONTROL RULE

## Before ANY major edit to Claw Deck:

1. Save current version:
   ```bash
   cp dashboard.html clawdeck-vX-YOURNAME.html
   ```

2. Commit checkpoint:
   ```bash
   git add -A && git commit -m "Checkpoint before [change]"
   ```

3. Make changes

4. If things break: restore from git or versioned file

## Version Naming
- v1 - Original beautiful (Feb 22)
- v2 - Structure locked
- v3 - Consolidated tools
- v4 - Teams reorganized
- v5 - Current

## Never Lose Work
- Git history = backup
- Versioned files = quick recovery
- Checkpoint before change = safety

---

# TuneVault Version Control

## Before ANY major edit to TuneVault:

1. Save current version:
   ```bash
   cp tunevault.html tunevault-vX.html
   ```

2. Commit checkpoint:
   ```bash
   git add -A && git commit -m "Checkpoint before [change]"
   ```

## TuneVault Version History
- v1 - Tip jar added (Feb 24)
- Current - tunevault.html (always the latest)

---
*Remember: Build ON TOP, not replace!*
