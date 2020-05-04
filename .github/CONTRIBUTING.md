# Contributing guidelines

Contributions are very welcome and although all types of contributions generally are appreciated, it is mainly intended for up theme updates.

## Design guidelines

When editing the themes you should try to stick to the design language of Discord's dark theme, this means:

- You should use the same colors as Discord's dark theme. For example:
  - Object highlighting.
  - Background & foreground.
  - Fields.
  - Out of focus objects.
  - Object depth.
  - Dividers
  - etc.
- You should use the same shapes as Discord. For example:
  - Shadow sizes.
  - Rounded corner sizes.
  - Popup boxes.
  - etc.

## Creating a PR

When Creating a PR you should follow the steps below, for settings up and checking the code to make sure it is linted and versioned correctly.

1. Fork the [repository](https://github.com/Thereatra/Discord-Zendesk-Darkmode).
2. Clone your fork.
3. *Install [Node.js](https://nodejs.org) if you do not have it already.*
4. Install the required developer dependencies by running `npm install`.
5. **Make your changes.**
   - ❗ **Important** ❗ Due to the nature of the themes, there is a lot of duplication between the feedback and support theme. Make sure that changes that are applicable to both subsites are applied for both themes.
6. Check for styling issues by running `npm run lint`.
7. Fix any styling issues.
   - Try run `npm run lint-fix` to see if any can be fixed automatically.
8. When you are pleased with the changes increment the version using:
    - `npm run major` for big changes like, a complete rewrite.
    - `npm run minor` for medium changes like, regex updates, new elements added, etc.
    - `npm run patch` for small fixes like, updating a broken class, fixing slightly off color, etc.
9. Create your PR.
   - List the changes that you have made.
   - Attach images of the changes if possible.
