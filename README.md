# RLengine 7.2 situation

Just a quick update on where things stand with 7.2.

Taking a bit of time off after wrapping up 7.1. I'll start actively working on 7.2 around November 20th.

### What I'm planning for 7.2:
- **Editor docking**: Full dynamic docking panels (Dear ImGui) instead of the fixed layout.
- **Physics**: OBB vs OBB collision detection (SAT), contact manifolds, and angular momentum.
- **DirectX 11 fallback**: Add basic texture sampling and shadows for older GPUs.
- **Undo / Redo**: Support entity creation, deletion, and reparenting in the scene hierarchy.
- **Memory telemetry**: Finish wiring up `MemoryStats` and the unified event bus.

Will push updates here once work starts around the 20th!
