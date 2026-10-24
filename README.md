# Stellaris Immersive Council Mod

Stellaris mod to make councilors more dynamic and influential through:

- Per-councilor **approval** (0–100 variable on each leader) that shifts based on empire performance.
- Opinion-driven events (e.g. military parade from high-approval commanders, tech leaks from unhappy scientists).
- Periodic **council meetings** on ongoing issues (famine, border tensions, etc.). Skipping a meeting hurts approval of all councilors.
- Government-type flavor can be added by checking `has_authority` in event triggers/options.

## Installation
1. Copy the contents (or the folder structure) into your Stellaris `mod/` directory.
2. Enable the mod in the launcher.

## Expanding the Mod
- Add more performance checks in `events/pc_events.txt` (resource income, wars, ethics divergence, etc.).
- Create additional events and register them in `common/on_actions/pc_on_actions.txt`.
- Define static modifiers in `common/static_modifiers/pc_modifiers.txt`.
- Use `is_councilor_type` for position-specific logic.
- For government flavor: `has_authority = auth_imperial` vs `auth_democratic`.

Requires Stellaris 3.8+ (council system). Starter scaffolding ready for expansion.
