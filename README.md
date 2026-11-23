# FarsiTV public catalog

This repository contains public FarsiTV catalog data and poster assets. The application source is maintained separately in a private repository.

`catalog.json` and `posters/` contain the public catalog. A private-repository GitHub Actions workflow is scheduled to refresh this snapshot every six hours after validation. A manual publication test completed on 2026-11-23. Playback URLs point to the authorized media host; their presence does not guarantee that every stream is playable. The Android app has not yet been switched to this source.

`preview.json` is an earlier incomplete numeric-search snapshot retained for comparison.
