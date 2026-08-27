# Predictive Coding Streamlit Talk

Browser-based Streamlit presentation.

## Deploy on Streamlit Community Cloud

1. Create a GitHub repository and upload everything in this folder.
2. Go to Streamlit Community Cloud and create a new app.
3. Select the repository, branch, and `app.py` as the entrypoint.
4. Use Python 3.12 in Advanced settings.
5. Deploy.

After deployment, viewers only need the public web link. They do not need Python or Streamlit installed.

## Optional image assets

Most presentation images are embedded directly in `app.py` and are created automatically at runtime.
Two optional slide images are not embedded in the supplied source file:

- `presentation_images/examplePC.png`
- `presentation_images/CoreIssues(1).png` (or `presentation_images/CoreIssues.png`)

The app still runs without them, but those locations display an image-not-found warning. Add the original image files at the paths above before the final public deployment if you want those slides complete.
