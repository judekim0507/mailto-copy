# Mailto Copy Hijacker

Chrome extension that intercepts `mailto:` links and copies the email address to the clipboard instead of opening the system email app.

## Load locally

1. Open `chrome://extensions`.
2. Enable Developer mode.
3. Click Load unpacked.
4. Select this folder.

## Behavior

- Captures `mailto:` link activation in the capture phase.
- Prevents the browser's default email-client launch.
- Copies just the email address, not query params like `subject=` or `body=`.
- Shows a small toast confirming the copy action.
