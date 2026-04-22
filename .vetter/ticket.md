# Add a "Docs" link to the user profile dropdown

Add a "Docs" entry to the top-right user profile dropdown menu of the
signed-in Chatwoot UI that opens https://www.chatwoot.com/docs in a
new tab.

## How to reach the app

Chatwoot runs on http://localhost:3000. First-time use requires signing
up as the first admin via /auth/sign_up.

## Acceptance

- "Docs" entry is visible in the user profile dropdown for signed-in users.
- Clicking it opens chatwoot.com/docs in a new tab
  (target=_blank, rel=noopener).
- No existing menu items are moved or removed.
