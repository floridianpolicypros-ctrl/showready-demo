# ShowReady — Interactive Demo

> Verify the buyer. Prepare the agreement. Be ready to show.

This is a clickable prototype of **ShowReady**, a mobile-first tool for real estate agents. It lets you:

1. **Verify a buyer** — send a secure link; the buyer submits their driver's license, a selfie, and optional location before you meet.
2. **Prepare the agreement** — when needed, auto-fill a brokerage-approved showing agreement (Florida Realtors SA-5) and send it for signature.

The demo walks through the agent's dashboard, creating a showing, the buyer's phone experience, and the final "Ready to Show" record.

**It is a prototype for feedback only. No camera, location, or personal data is used, stored, or transmitted.**

---

## Try it

- **On your phone or computer:** open `index.html` in any modern browser (Safari, Chrome, Edge).
- Tap **Start the demo** and follow the buttons. Try the **Verify only** vs **Verify + agreement** toggle on the "New showing" screen to see both paths.
- Tap **Send feedback** at any time to email your thoughts.

## Publish a shareable link (free, ~5 minutes)

To send realtors a link instead of a file, host it free on GitHub Pages:

1. Create a free account at [github.com](https://github.com).
2. Click **New repository** → name it `showready-demo` → set it **Public** → **Create repository**.
3. On the new repo page, click **Add file → Upload files**, drag in every file from this folder (`index.html`, `README.md`, etc.), then **Commit changes**.
4. Go to **Settings → Pages**. Under **Source**, choose **Deploy from a branch**, select branch **main** and folder **/ (root)**, then **Save**.
5. Wait about a minute, then refresh. GitHub shows your live link:
   `https://YOUR-USERNAME.github.io/showready-demo/`
6. Share that link with your realtors.

Any GitHub-connected build tool or browser extension can also read this repo directly.

## Collecting suggestions

The demo's **Send feedback** button opens a pre-written email to the project owner with three short questions. You can also point testers to `FEEDBACK.md`. Keep the first round to 3–5 agents and watch where they hesitate.

---

## What's inside

| File | Purpose |
|------|---------|
| `index.html` | The entire demo — self-contained, no dependencies, works offline. |
| `README.md` | This file. |
| `FEEDBACK.md` | Short question set for testers. |
| `LICENSE` | Usage terms (proprietary — evaluation only). |
| `.gitignore` | Standard ignore list. |

## Important notes

- This is an **early prototype**, not a finished product. Screens are illustrative.
- Agreement fields are **samples** and are **not legal advice**. The real product fills only brokerage-approved templates and never drafts or edits legal language.
- Identity language is deliberate: the demo says *"identification submitted / information matched,"* never *"identity verified,"* unless a qualified third-party verification service performs that check.

© 2026 ShowReady. All rights reserved.
