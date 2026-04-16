# SCI Calorie Calculator

Static web app for calorie and macro planning with SCI-specific adjustments.

## Version Tracker

Current version: 1.14.8

### Minor Releases (new features)

- 1.14.0 (2026-04-15)
	Summary: Added AIS A/B physio selector.
	Changes: Added physio/rehab therapy time selector for AIS A/B with conservative activity bumps included in calories and breakdown.

- 1.13.0 (2026-04-15)
	Summary: Added AIS-adaptive daily routine options.
	Changes: Daily routine/job demand options now adapt by AIS. A/B uses non-ambulatory routine choices, while C/D includes standing/walking routine options.

- 1.12.0 (2026-04-15)
	Summary: Updated day context model.
	Changes: Replaced day type with Daily routine / job demand options and positioned it next to Activity, with wheelchair controls below.

- 1.11.0 (2026-04-15)
	Summary: Added safety guardrails and refined wheelchair bump behavior.
	Changes: Made pregnancy/breastfeeding mutually exclusive, capped fat-loss deficits with a calorie floor, and added optional wheelchair bump mode that applies only when activity is Low.

- 1.10.0 (2026-04-15)
	Summary: Added selectable fat-loss pace.
	Changes: Added Fat-loss pace dropdown (kg/week and lb/week labels), shown only when Fat loss is selected, and used selected pace to set deficit.

- 1.9.0 (2026-04-15)
	Summary: Added plan sharing.
	Changes: Added Share plan button with native share support and clipboard fallback, including a compact input/output summary.

- 1.8.0 (2026-04-15)
	Summary: Added wheelchair-specific calorie logic.
	Changes: Wheelchair user/type inputs, electric default bump of 0, manual base bump of 100 kcal/day scaled by selected activity.

- 1.7.0 (2026-04-15)
	Summary: Added female-specific planning features.
	Changes: Pregnancy and breastfeeding calorie additions, optional cycle-aware mode, and pregnancy-safe goal handling.

### Patch Releases (refinements)

- 1.14.8 (2026-04-16)
	Summary: Removed A/B wording from routine UI copy.
	Changes: Simplified daily routine options and hints by removing explicit A/B mode labels while preserving the same selection logic.

- 1.14.7 (2026-04-16)
	Summary: Tightened field wording.
	Changes: Shortened training and daily-routine labels/hints for a cleaner form and removed unused compact-card CSS.

- 1.14.6 (2026-04-16)
	Summary: Streamlined SCI-specific header copy.
	Changes: Replaced the Brief and Method cards with one concise SCI-focused subtitle above the form to keep the interface clean.

- 1.14.5 (2026-04-16)
	Summary: Tightened above-the-fold spacing.
	Changes: Reduced page outer spacing and compacted the Brief and Method cards so the calculator inputs appear higher on first load.

- 1.14.4 (2026-04-16)
	Summary: Condensed method description for cleaner UI.
	Changes: Replaced the multi-line Method bullet list on the calculator page with one concise sentence while retaining full source citations in the README.

- 1.14.3 (2026-04-16)
	Summary: Simplified interface presentation.
	Changes: Removed the Notes card from the calculator page for a cleaner layout while keeping full citations in the README References section.

- 1.14.2 (2026-04-16)
	Summary: Moved references out of the calculator UI.
	Changes: Removed in-page citation list from the Notes card and centralized all literature links in the README References section.

- 1.14.1 (2026-04-15)
	Summary: Reduced overlap between activity and daily routine inputs.
	Changes: Clarified activity as structured training volume, clarified day routine as non-training movement/job demand, and scaled day-routine bump down as activity volume increases.

- 1.12.1 (2026-04-15)
	Summary: Fixed timeline and gain/loss pacing logic.
	Changes: Hides timeline when Maintenance is selected, mirrors gain pace behavior to fat-loss pace selection, and fixed stale day-type references in recomp/gain logic.

- 1.11.1 (2026-04-15)
	Summary: Clarified activity selection.
	Changes: Added training-hours-per-week guidance directly in activity level labels.

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

## References

Core references used to inform adjustment logic:

1. Ma Y, et al. Predicting resting energy expenditure in people with chronic spinal cord injury. Spinal Cord. 2022. https://pubmed.ncbi.nlm.nih.gov/35780202/
2. Andersen RE, et al. Accuracy of generic and SCI-specific REE equations in SCI. Can J Diet Pract Res. 2018. https://pubmed.ncbi.nlm.nih.gov/30014708/
3. Holmlund T, et al. Energy expenditure after spinal cord injury by neurologic profile. Spinal Cord. 2018. https://pubmed.ncbi.nlm.nih.gov/29238094/
4. Nevin AN, et al. REE during SCI rehabilitation and FFM-based equations. Spinal Cord Ser Cases. 2024. https://pubmed.ncbi.nlm.nih.gov/39358343/
5. Buchholz AC, Pencharz PB. Energy expenditure in chronic spinal cord injury. Curr Opin Clin Nutr Metab Care. 2004. https://pubmed.ncbi.nlm.nih.gov/15534431/
6. Farkas GJ, Sneij A, Gater DR Jr. Dietetics After Spinal Cord Injury: Current Evidence and Future Perspectives. Top Spinal Cord Inj Rehabil. 2021. https://pubmed.ncbi.nlm.nih.gov/33814888/
7. Nevin AN, et al. Nutritional intakes in SCI with pressure injuries. Top Spinal Cord Inj Rehabil. 2025. https://pubmed.ncbi.nlm.nih.gov/40008160/
8. Farkas GJ, et al. Energy and protein intake relative to requirements in chronic SCI. Br J Nutr. 2024. https://pubmed.ncbi.nlm.nih.gov/37726106/
