# Publish your futuristic GitHub profile

This package customizes the **GitHub profile README itself** — it is not a separate website.

## Upload these files to your existing public profile repository
Repository: https://github.com/thesurajdev/thesurajdev

Expected structure:

```text
thesurajdev/
├── README.md
└── assets/
    ├── profile-hero.gif
    └── signal-divider.gif
```

## Steps
1. Open the repository.
2. Choose **Add file → Upload files**.
3. Upload the new `README.md` and the complete `assets` folder containing both GIFs.
4. Commit changes to `main`.
5. Refresh https://github.com/thesurajdev.

The README uses absolute raw URLs pointing at `main`, so commit the GIFs to these exact paths to make the animations display.

## Notes
- This is the profile README, not a new website.
- Animated GIFs are local repository assets; typing, skill icons, and GitHub telemetry use external image services.
- External widget services can occasionally be rate-limited or unavailable; the rest of the profile remains readable.
