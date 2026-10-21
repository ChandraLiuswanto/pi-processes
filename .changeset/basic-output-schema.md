---
"@aliou/pi-processes": patch
---

Declare a basic `{ action, ... }` outputSchema for the process tool instead of the full 7-way union, so codemode no longer renders ~12KB of nested TypeScript into the tool description. Scripts still receive the full structured payload.
