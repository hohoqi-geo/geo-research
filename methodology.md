# Methodology

## 1. Evidence first

We do not infer what AI sees from theme source or screenshots. We collect from a real browser: rendered JSON-LD, FAQ anchors, raw-md and visible text. The server re-validates the payload; client-provided verdicts are never trusted.

## 2. Four dimensions

- **Readability**: robots access, status codes, raw-md availability.
- **Structure**: required schema types (Product/Offer, FAQPage, Article...).
- **Consistency**: the same SKU has the same price, weight and return window across pages, Admin and raw-md.
- **Freshness**: every finding carries a timestamp and collection method.

## 3. Measurement

For AI visibility we use a fixed prompt set, versioned by hash. Each run records engine, model version, answer hash, mentions, cited URLs and sentiment. We report rates with sample size and time window; single answers are anecdotes.

## 4. Reproducibility

- fixed URL lists and template versions;
- raw evidence retained for at least 90 days;
- benchmark protocols published before results;
- scripts and schemas documented so a third party can replicate.

## 5. Limitations

- AI answers vary; correlation is not causation;
- first-party evidence reflects collection time, not history;
- no ranking or traffic guarantees;
- platform rules and model behaviour change.

## 6. Corrections

Errors are corrected in place with a changelog entry. Substantive changes update `dateModified`. We publish corrections rather than silently editing.
