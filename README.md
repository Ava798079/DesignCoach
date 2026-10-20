# DesignCoach

**Your AI Mentor for 3D Design**

DesignCoach is an early-stage, static front-end prototype for a 3D design feedback and learning experience. The current interface is in Persian (RTL) and includes a dashboard, demo design-analysis screen, project cards, learning section, progress view, version comparison, and illustrative subscription plans.

## Current status

This repository contains a **front-end demo only**. It is not yet a production SaaS.

- Login and registration are demonstrative UI only.
- Analysis scores and feedback are sample/demo data; no real AI analysis is connected.
- Project history and account data are not persisted in a backend.
- Subscription prices and plan actions are illustrative; payment processing is not implemented.
- Selecting a 3D model file does not mean the model is truly parsed or analyzed.

## Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

For a local web server, you can use the VS Code Live Server extension.

## Publish with GitHub Pages

1. Create a GitHub repository named `DesignCoach`.
2. Upload `index.html`, `README.md`, and `.gitignore`.
3. Open the repository's **Settings → Pages**.
4. Under the build/deployment section, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for the deployment to finish. GitHub will show the published URL in the Pages section.

GitHub Pages publishes a static website. It does not provide a backend, secure API-key storage, user accounts, database, or payment processing.

## Security

- Never commit API keys, passwords, access tokens, or `.env` files.
- If real AI functionality is added, call the AI provider from a backend/serverless function and keep secret keys on the server.
- Review all third-party assets and font licensing before production use.

## Roadmap

- [ ] Connect a backend and database
- [ ] Implement real authentication and authorization
- [ ] Add secure AI analysis via a server-side API
- [ ] Persist projects and analysis history
- [ ] Implement real subscription and payment handling
- [ ] Add automated tests and production error handling

## License

No license has been specified yet. Unless a license is added, do not assume others have permission to reuse, modify, or redistribute this code.
