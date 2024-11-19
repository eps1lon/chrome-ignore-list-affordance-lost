# Missing toggle for ignore-listed frames when error is logged

## Steps to reproduce

1. `pnpm install`
2. `pnpm start`
3. Open `http://localhost:3000/` in your browser

## Expected behavior

Ignore-listed frames in logged error should be hidden by default and only displayed once "show ignore-listed frames" is clicked.

## Actual behavior

Ignore-listed frames are displayed by default and dimmed.
"Show ignore-listed" is only displayed when the console.error call is expanded to show the sync callstack of the `console.error` call.
