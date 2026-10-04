# NOTES

## Summary of changes

- Fixed task search and status filtering logic in the repository query.
- Fixed frontend loading state handling so failed requests no longer leave the UI stuck in a loading state.
- Removed unnecessary artificial delay from task search requests to improve responsiveness.

## What I chose not to change

- Did not redesign the UI.
- Did not introduce new features.
- Did not add automated tests due to the exercise timebox.

## Biggest remaining risk

The application has limited automated test coverage. Query behavior and filtering logic could regress without tests.

## AI usage

Used ChatGPT to help review code, discuss debugging approaches, and validate fixes. All changes were reviewed, implemented, and tested manually.