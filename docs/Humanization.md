# Humanization

Humanization is default on.

PicNickTreeRuns keeps interaction pacing, off-screen moments, camera settling, mini-AFK windows, mini-breaks, and route variation active without exposing extra user-facing controls. Long breaks are intentionally disabled because tree growth waits should use logout/recheck planning instead of remaining logged in.

v0.15 adds an isolated MouseProfile/HumanizedMouse wrapper. It keeps persistent account personality, daily/weekly/monthly/session variation, bounded max-step movement, quiet idle zones, and fatigue-ready pacing inside the humanization layer instead of the core script loop.
