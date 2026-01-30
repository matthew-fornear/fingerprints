# fingerprints.jsonl

JSONL of URLs and the fingerprint/antibot tech detected on each (Canvas, FingerprintJS, Akamai, Shape Security, etc.). One line per URL + type; multiple entries for the same URL are merged with distinct findings kept.

**Format (one JSON object per line):**
- `url` — site that was tested
- `type` — detection type (e.g. Canvas Fingerprinting, Akamai)
- `found` — list of script URLs where it was detected

Sorted by URL, then type.