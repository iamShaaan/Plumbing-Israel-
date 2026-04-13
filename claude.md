# Project Constitution: Miley Plumbing Services (Israel)

## 🎯 North Star
Recreate a premium, Hebrew-localized plumbing landing page for "Miley Plumbing Services" using deterministic business data from Google Maps.

## 🛠️ Data Schema (gemini.md)
```json
{
  "business": {
    "name_he": "מיילי שרותי אינסטלציה",
    "owner": "Daniel Miley",
    "phone": "+972 52-688-3212",
    "location": "גוש דן והמרכז",
    "specialty": "אינסטלטור מומחה, מתנדב למען הקהילה",
    "website_fb": "https://www.facebook.com/mailiplumbing"
  },
  "visuals": {
    "primary_color": "#0A3D91",
    "accent_color": "#4DA6FF",
    "logo_desc": "Blue circular logo with wrench and Hebrew text"
  }
}
```

## ⚖️ Behavioral Rules
1. **RTL First:** All layouts must be Right-To-Left (RTL).
2. **Community Focus:** Highlight the "Volunteer Plumber" aspect prominently.
3. **No Placeholders:** Professional images only (generate if needed).
4. **Consistency:** Ensure phone numbers and names are synced across all components.

## 🏗️ Architectural Invariants
- **Layer 1 (Architecture):** Markdown SOPs in `architecture/`.
- **Layer 2 (Navigation):** Agent-led logic.
- **Layer 3 (Tools):** Simple HTML/CSS/JS in `Plumbing project/`.
