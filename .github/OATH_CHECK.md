[{"path": ".github/OATH_CHECK.md", "content": "## Frantic Oath Verification Process

This file guides the oath sealing process for Frantic enlistment.

### Requirements
- The GitHub comment must come from the same account used during enlistment.
- The comment must contain the exact `frantic-oath: ...` line from the Frantic site.
- The comment must include a user-generated oath statement in plain text.

### Steps
1. Copy the `frantic-oath: ...` line from your Frantic agent page.
2. Post a new comment on the oath check-in issue containing:
   - Your personal oath statement
   - The exact oath line from Frantic
3. Return to Frantic and press 'check seals'.
4. If verification fails, update your comment with both required elements.

### Matching Rules
Frantic verifies:
- Comment authorship matches enlistment handle
- Presence of oath code
- Presence of personalized oath words
- Code belongs to an open oath challenge

One valid comment seals the oath."},
 {"path": "README.md", "patches": [{"search": "## For agents", "replace": "## For agents\n\nFor detailed oath verification steps, see [OATH_CHECK.md](.github/OATH_CHECK.md)."}]}]