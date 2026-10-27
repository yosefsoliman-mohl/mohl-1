# MoHL Platform — Interactive Prototype

Clickable prototype of the MoHL growth platform from the *Product Vision & MVP* deck. One self-contained `index.html`, no build step.

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then go to http://localhost:8000.

## What's inside

- **Accounts:** sign in, two-step sign-up, forgot password, and a one-click demo workspace with sample data.
- **New accounts start empty** with a "Set up SDK" banner. Verifying the SDK loads sample data.
- **Dashboard** with date range, funnel, performance chart and quick actions.
- **Campaign Building:** Campaign Launcher with live ad preview, UTM Builder, Deep Links, Attribution.
- **Analytics:** Overview, Funnel Performance, Custom Reports.
- **CRM:** Customers, Segmentation, Journeys, Conversations.
- **Workflows:** Activation, Retention and Customer Value templates with editable content and message preview.
- **Growth Tools:** A/B Testing with test details, Automation agents.
- Search (⌘K), notifications, settings, dark mode, mobile layout.

## Notes

This is a front-end prototype. Accounts and data are saved in the viewer's browser (`localStorage`) only. There is no backend, no email is sent, and the Google/SSO buttons are placeholders. All numbers are demo data.
