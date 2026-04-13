# SOP: Hebrew Localization & RTL Implementation

## Goal
Transform the LTR English website into a professional RTL Hebrew website for "מיילי שרותי אינסטלציה".

## 1. Direction & Language
- Set `<html dir="rtl" lang="he">` in `index.html`.
- Use Hebrew-compatible fonts: **Heebo** (Primary) and **Assistant** (Secondary).

## 2. RTL Styling Rules (style.css)
- **Mirroring:**
  - Logic: `left` properties become `right`, and `right` becomes `left`.
  - `margin-left` ↔ `margin-right`.
  - `padding-left` ↔ `padding-right`.
  - `border-left` ↔ `border-right`.
- **Flexbox/Grid:**
  - `justify-content: flex-start` stays the same logically but moves to the right visually in RTL.
  - `flex-direction: row-reverse` should be checked for components that need explicit ordering.
- **Absolute Positioning:**
  - Elements positioned with `right: X` in LTR must be changed to `left: X` or vice-versa to maintain visual balance.
- **Icon Mirroring:**
  - Arrows (e.g., `fa-plus`, `fa-chevron-right`) and progress bars should be mirrored.

## 3. Translation Strategy
- Use professional, direct Hebrew (Plumbing terminology).
- **Key Terms:**
  - Emergency Service: שרות חירום 24/7
  - Drain Cleaning: פתיחת סתימות
  - Leak Repair: תיקון נזילות
  - Water Heaters: דודי שמש וחשמל
  - Pipe Repair: תיקון צנרת
  - Call Now: התקשרו עכשיו

## 4. Special Customization
- Highlight the **Volunteer** aspect: "מתנדב למען הקהילה".
- Coverage: "גוש דן והמרכז" (Gush Dan and Central Region).
