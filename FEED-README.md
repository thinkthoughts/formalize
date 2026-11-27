# Specification feed

Extract into the root of thinkthoughts/formalize. Existing index.html and styles/site.css remain unchanged. Visit /feed.html. All nine cards have local detail pages under /specifications/ and link to the original full research records. The pages use the existing site.css and the same rlt-theme localStorage key. MathJax is loaded only on detail pages (external pinned CDN).

The HTML is static for accessibility and no-JS reading. specifications.json is a machine-readable inventory of the initial records; edits to it do not automatically update HTML. To regenerate the static cards and detail pages, run python3 build-specifications.py from the repository root. Custom long-form pages can be edited separately; the generator overwrites the generated detail pages, so preserve custom edits before running it. No date-based ordering.

Status is a summary of the linked research pages, not an independent audit. Keep the full records at their current URLs for now.
