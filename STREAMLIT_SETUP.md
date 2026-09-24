# Streamlit team library setup

## What the app does

- Lists repository files newest-first using each file's latest GitHub commit date.
- Previews PDFs, Excel workbooks, PowerPoint decks, Word documents, text/Markdown, CSV/TSV, images, audio, and video. Other files appear with a download option.
- Stores visitor comments and highlighted-section suggestions as GitHub Issue comments, so they survive app restarts and new deployments.
- Lets visitors submit feedback without a GitHub login. Their optional name is self-reported; GitHub records the app's token owner as the API author.

## Add these files to the GitHub repository

Upload `streamlit_app.py` and `requirements.txt` to the repository's root. Streamlit Community Cloud looks for the entrypoint and dependencies there.

## Deploy the app

1. Sign in at [Streamlit Community Cloud](https://share.streamlit.io/) with GitHub and authorize access to the repository. The deploying account needs admin access to the repository. For a private repository, authorize Streamlit to access private repositories as well.
2. Choose **Create app** → **Yup, I have an app**.
3. Select `Jacob-Potok/LBOCaseComp-Fall2026`, branch `main`, and entrypoint `streamlit_app.py`, then deploy.
4. In the app's settings, add the secrets below. Create a **fine-grained personal access token** for only this repository with **Contents: read-only** and **Issues: read and write** permissions. Do not commit the token to GitHub or paste it into the app code.
5. Enable Issues in the repository settings. The app creates one feedback thread per file as needed.
6. Set the app's sharing/access option so the intended visitors can open the site. Anyone who can open the site can read its repository materials and post feedback through the app.

```toml
GITHUB_REPO = "Jacob-Potok/LBOCaseComp-Fall2026"
GITHUB_TOKEN = "github_pat_replace_with_your_token"
```

The token stays in Streamlit's server-side Secrets. Visitors do not need GitHub accounts or repository access to read the site or submit feedback. Submissions are associated with the app token owner in GitHub, with the visitor's optional self-reported name included in the comment.

## Keep the site current

When someone uploads or edits a file on GitHub, GitHub creates a commit and Community Cloud detects the repository update and redeploys the app. The new or updated file then appears in the feed. A visitor can use **Refresh feed** to refresh the file order and feedback.
