# Findings: Hebrew Customization for Miley Plumbing

## Business Profile (Source: Google Maps)
- **Name**: מיילי שרותי אינסטלציה (Miley Plumbing Services)
- **Primary Service**: Plumber (אינסטלטור)
- **Phone**: +972 52-688-3212
- **Website**: facebook.com/mailiplumbing
- **Location**: Central Israel (Gush Dan, Tel Aviv, Petah Tikva, etc.)
- **Highlights**: Professional, quick response, community volunteer (assists people in distress).

## Technical Research (Codebase)
- **Current Lang**: English (LTR)
- **Current Styling**: Poppins font, flex/grid layouts with many left-to-right properties.
- **Localization Needs**:
    - **index.html**: Full translation of header, hero, services, about, why-us, testimonials, FAQ, and footer.
    - **style.css**:
        - Import Hebrew-friendly fonts (e.g., 'Heebo' or 'Assistant').
        - `dir: rtl` on `html`.
        - Mirror `margin`, `padding`, `left`, `right`, and `flex-direction` where needed.
        - Reverse absolute positioning and floating elements.
    - **script.js**: Update any English confirmation messages or validation logic.

## Constraints
- Must be professional and tailored to the Israeli market.
- Must support Right-to-Left (RTL) layout properly.
- No Webhook/API setup required for this phase.
