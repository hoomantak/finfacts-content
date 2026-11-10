# FinFacts content releases

Verified content releases for the FinFacts app's live updates, served by GitHub Pages.

- `v1/content/latest`: the newest release's version, SHA-256 and size.
- `v1/content/<version>.json`: each release, exactly as built. A published version never changes.

The app checks each download's size and SHA-256 against `latest` before using it, and falls back to the content built into it. Files here are written only by `scripts/publish_static_release.py` in the main repo, from releases built with `--verified-only`. Every record was written from cited sources and signed off by a named reviewer; none is AI-generated.
