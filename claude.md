# Project Constitution: Miley Plumbing Services (Hebrew)

## Data Schemas (gemini.md)
### Business Profile
- `name`: "מיילי שרותי אינסטלציה" (Miley Plumbing Services)
- `owner`: "מיילי" (Miley)
- `phone`: "+972 52-688-3212"
- `location`: "Gush Dan / Central Israel"
- `language`: "Hebrew"
- `direction`: "RTL"

## Behavioral Rules
1. **RTL Logic:** Ensure all layouts are mirrored for Right-To-Left reading.
2. **Cultural Tone:** Professional, reliable, and community-focused (volunteer spirit).
3. **Deterministic Localization:** If a string is in English, it must be translated to Hebrew.

## Architectural Invariants
- Core logic in `Plumbing project/`.
- Local ephemeral files in `.tmp/`.
- RTL overrides in `style.css` or a new `rtl.css`.
