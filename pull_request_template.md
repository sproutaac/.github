## What does this PR do?

<!-- A clear description of the change and why it's needed. Link the related issue if there is one. Closes # -->

## The Three Rules

Every PR must pass these before it ships. Check each one or explain why it doesn't apply.

- [ ] **Offline-first** — my change works with no network connection. If it involves a network feature, it degrades gracefully when offline.
- [ ] **Motor planning stability** — I have not moved, reordered, or shuffled any existing cells. `rowIndex` and `colIndex` are immutable after creation.
- [ ] **Privacy-safe** — my change does not transmit child data to any server, add analytics, or introduce telemetry that touches child usage data.

## Testing

<!-- How did you verify this works? For UI changes, include screenshots or a screen recording. For grid/cell changes, describe how you confirmed motor planning stability (e.g. "cells don't shift on hot reload / profile switch / app restart"). -->

## Clinical review needed?

<!-- Does this change affect vocabulary, symbol placement, Fitzgerald Key colours, or board structure? If yes, tag an SLP reviewer before merging. -->

- [ ] Yes — tagged @<!-- SLP reviewer -->
- [ ] No
