# Testing and limitations

## Checked

Basic browser checks cover the Store unavailable state. The standalone HTML matches the extracted source.

The extraction checks also cover JavaScript syntax, bundled files and local documentation links.

## Next checks

- Writing a digest through ArtifactData and reading it in the app.
- Saving read marks and favourites for signed-in readers.
- Handling repeat stories and empty runs.
- Source failures, more browsers and mobile layouts.

## Before using real data

Start with fictional data and a test destination. Review owners, dates, source links and proposed writes. Keep a separate copy of important results.

## Test the connected workflow

Follow the setup steps in the [README](../README.md), using a test account or store. Compare each result with its source, then confirm that a change appears in the intended destination.
