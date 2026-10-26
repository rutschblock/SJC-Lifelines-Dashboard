# San Juan County Community Lifelines Dashboard

## Publish with GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select **main** and **/(root)**, then **Save**.
4. After GitHub Pages deploys, visit https://rutschblock.github.io/SJC-Lifelines-Dashboard/.

## Operational notes

- The dashboard is a manual assessment tool, not a live conditions feed.
- Assessments are stored in browser `localStorage` under `sjc-em-lifeline-assessments-v2`; incident header fields are kept in session storage.
- Use **Export JSON backup** to preserve assessments or transfer to another browser. Import overwrites local assessments after confirmation.
- The first version uses the blue lifeline sprite from the existing SJC Emergency Management Dashboard; standalone bundled multi-color FEMA icon assets are a planned improvement.
- Do not enter sensitive information on a shared computer or treat public GitHub Pages as a secure incident data repository.
