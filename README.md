# SCI Calorie Calculator

Static web app for calorie and macro planning with SCI-specific adjustments.

## Version Tracker

Current version: 1.8.1

### Minor Releases (new features)

- 1.8.0 (2026-04-15)
	Summary: Added wheelchair-specific calorie logic.
	Changes: Wheelchair user/type inputs, electric default bump of 0, manual base bump of 100 kcal/day scaled by selected activity.

- 1.7.0 (2026-04-15)
	Summary: Added female-specific planning features.
	Changes: Pregnancy and breastfeeding calorie additions, optional cycle-aware mode, and pregnancy-safe goal handling.

### Patch Releases (refinements)

- 1.8.1 (2026-04-15)
	Summary: Added clearer fat-loss progress output.
	Changes: Expected weekly change line with explicit kg/week and lb/week messaging for fat-loss mode.

- 1.7.2 (2026-04-15)
	Summary: Simplified cycle language.
	Changes: Replaced cycle phase terms with Week 1-4 options.

- 1.7.1 (2026-04-15)
	Summary: Improved cycle adjustment control.
	Changes: Added custom cycle bump input (0-150 kcal/day).

- 1.6.2 (2026-04-15)
	Summary: Baseline build before female-specific additions.
	Changes: Initial tracked baseline for rollback reference.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and this `README.md`.
3. Commit and push to `main`.
4. In GitHub: **Settings -> Pages**.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
6. Select branch `main` and folder `/ (root)`, then **Save**.
7. Wait 1-2 minutes and open the URL shown on the Pages screen.

Your shared URL will look like:

`https://<your-username>.github.io/<repo-name>/`

## Local run

Open `index.html` in a browser.
