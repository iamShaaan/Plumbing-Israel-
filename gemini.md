# Data Schema: Business Customization

```json
{
  "business": {
    "name_he": "מיילי שרותי אינסטלציה",
    "owner": "מיילי",
    "phone": "+972 52-688-3212",
    "location": "גוש דן והמרכז",
    "specialty": "אינסטלטור מומחה, מתנדב למען הקהילה",
    "website_fb": "https://www.facebook.com/mailiplumbing"
  },
  "localization": {
    "language": "he",
    "direction": "rtl",
    "font_family": "'Heebo', sans-serif"
  },
  "repository": {
    "name": "Plumbing Israel",
    "owner": "iamShaaan",
    "remote_url": "git@github.com:iamShaaan/Plumbing-Israel-.git",
    "branch": "main"
  }
}
```

# Data Schema: Booking Webhook Payload

```json
{
  "name": "string",
  "phone": "string",
  "service": "string",
  "message": "string",
  "address": "string",
  "timestamp": "ISO-8601 string",
  "metadata": {
    "source": "landing-page",
    "version": "1.0.0"
  }
}
```

# Maintenance Log

## 2026-04-13: Hebrew Localization & Deployment
- **Event:** Started customization for Miley Plumbing Services (Israel).
- **Action:** Extracted business details, localized website to Hebrew (RTL), and prepared for deployment to `iamShaaan/Plumbing-Israel-`.
- **Status:** Complete.
