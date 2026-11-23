# FarsiTV public catalog

This repository contains public FarsiTV catalog data and poster assets. The application source is maintained separately in a private repository.

`catalog.json` and `posters/` contain the public catalog. A private GitHub Actions workflow checks the source every 30 minutes, updates changed records and poster files, and validates the result before publishing. Periodic ID-only reconciliation detects missing or removed records. GitHub may delay scheduled runs. Playback URLs point to the authorized media host; their presence does not guarantee that every stream is playable.

`preview.json` is an earlier incomplete numeric-search snapshot retained for comparison.
