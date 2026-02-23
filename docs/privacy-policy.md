# Privacy Policy for Polyglot

Effective date: February 23, 2026

Polyglot is a Chrome extension that translates user-selected text on webpages.

## Data We Process

Polyglot may process the following data only to provide translation features:

- User-selected text from the active webpage (only when the user triggers translation).
- Extension settings saved locally in the browser (for example: provider choice, target language, shortcuts, UI preferences).
- OpenAI API key, if the user chooses OpenAI and enters a key.

## How Data Is Used

- Selected text is sent to the translation provider chosen by the user:
  - OpenAI: https://api.openai.com/*
  - Google Translate: https://translate.googleapis.com/*
- Returned translation results are shown in-page to the user.
- Settings and optional API key are stored locally using chrome.storage.local so the extension can remember user preferences.

## What We Do Not Do

- We do not sell personal data.
- We do not use user data for advertising.
- We do not run remote executable code.
- We do not collect browsing history for tracking.

## Data Sharing

Polyglot shares only the text the user explicitly selects for translation with the selected translation provider. Data handling by those providers is subject to their own privacy policies.

## Data Retention

- Local settings and optional API key remain in the user’s browser until changed or removed by the user.
- Polyglot does not maintain its own backend database for user content.

## Security

Polyglot stores settings and optional API key in Chrome extension local storage and transmits requests over HTTPS to provider endpoints.

## User Control

Users can:

- Choose translation provider.
- Remove or change API keys at any time.
- Clear extension storage or uninstall the extension to remove locally stored data.

## Contact

For privacy questions, contact: [ADD YOUR EMAIL ADDRESS]
