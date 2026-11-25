# PRAGYA: Sampling in Research (M.Com)

An interactive, classroom-ready learning simulation for the Sampling unit in M.Com Research Methodology.

## Learning outcomes
Students will be able to:
- distinguish population, sampling unit, sampling frame and sample;
- classify probability and non-probability sampling techniques;
- estimate sample size using Cochran's initial proportion formula and finite population correction;
- select and justify a sampling design for a business research scenario;
- recognise limitations such as coverage and selection bias.

## Files
- `index.html` — complete offline-capable interactive learning resource.

## Run locally
1. Download `index.html`.
2. Open it in a modern browser (Chrome, Edge, Firefox or Safari).
3. No installation, login, API key, external library or internet connection is required.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, for example `pragya-sampling-mcom`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish. The site URL will appear in the Pages settings, typically:
   `https://YOUR-USERNAME.github.io/pragya-sampling-mcom/`
7. Open the published URL on desktop and mobile to verify it.

## Classroom use
- **Teacher-led:** Project the simulation, discuss each stage, and ask students to defend the sampling decision.
- **Independent:** Ask students to complete the sample-size lab, case decision and five-question assessment.
- **Adaptation:** Edit the hypothetical population, case description, examples and quiz questions directly in `index.html`.

## Academic and methodological notes
- All case-study numbers are explicitly hypothetical teaching data.
- The sample-size lab uses `n0 = Z² p(1-p) / e²` and finite population correction `n = n0 / [1 + (n0-1)/N]`. It is a planning illustration for estimating a proportion under stated assumptions, not a universal rule.
- Actual research design should consider the estimand, sampling frame, design effect, non-response, subgroup analysis, feasibility and institutional research requirements.
- Proportional allocation in the activity uses a largest-remainder rounding approach so the displayed stratum allocations add to the target sample size.

## References for further study
- Cochran, W. G. (1977). *Sampling Techniques* (3rd ed.). John Wiley & Sons.
- Lohr, S. L. (2021). *Sampling: Design and Analysis* (3rd ed.). CRC Press.
- Saunders, M., Lewis, P., & Thornhill, A. *Research Methods for Business Students*. Pearson (use the edition prescribed by your institution).
- Kothari, C. R., & Garg, G. *Research Methodology: Methods and Techniques*. New Age International (use the edition prescribed by your institution).

## Resource description for sharing
**PRAGYA | Sampling in Research – M.Com:** An interactive learning simulation that helps postgraduate commerce students understand sampling concepts, compare probability and non-probability methods, experiment with sample-size assumptions, and make a defensible sampling decision through an Indian higher-education research case. Works locally in a browser and can be hosted free using GitHub Pages.

## Suggested screenshots
Capture these screens after opening `index.html`:
1. Introduction and learning objectives.
2. Sampling-method explorer with Stratified Random Sampling selected.
3. Sample-size laboratory showing adjustable inputs and live estimate.
4. Case study and proportional allocation table.
5. Knowledge-check questions and score feedback.
