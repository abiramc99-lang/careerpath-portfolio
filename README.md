# CareerPath — AIML-500 Professional Portfolio, Artifact 1

This repository contains a ready-to-publish GitHub Pages portfolio and the CareerPath interview practice chatbot.

## Files
- `index.html` — professional portfolio landing page
- `careerpath.html` — actual CareerPath chatbot (offline mode works without credentials)
- `assets/ai-comparison-1.png`, `2.png`, `3.png` — Workshop 1 AI assistant comparison screenshots, not chatbot test screenshots
- `ASSIGNMENT_REFLECTION.txt` — reflection to paste into the course assignment submission area

## Publish using GitHub Pages
1. Sign in to GitHub and create a **public** repository, e.g. `careerpath-portfolio`.
2. Upload the **contents of this folder** to the repository root (not the ZIP itself). Ensure `index.html` is in the root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Once published, open the GitHub Pages URL shown under Pages. The usual format is `https://YOUR-USERNAME.github.io/careerpath-portfolio/`.
7. Test the **Try CareerPath** button, five chatbot features, and all three evidence image links.
8. Submit the actual working URL and paste the text from `ASSIGNMENT_REFLECTION.txt` into your assignment's reflection field.

## Important limitations
- The default chatbot uses deterministic, keyword-based responses; it is not a generative model.
- The optional API feature requires a compatible endpoint, CORS permissions, and appropriate handling of secrets. Do **not** publish API keys in your repository or enter privileged tokens on a publicly hosted client-side page. A server-side proxy is recommended for a production AI integration.
- The user confirmed the offline chatbot worked, but no 7/7 automated result or per-feature outcomes were recorded.
- The screenshots are evidence of an LLM comparison activity, not CareerPath's operation.
