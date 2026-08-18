# CloudCalc

A responsive, browser-based scientific calculator with function graphing,
statistics, custom variables, and calculation history. It runs entirely in the
browser, so no server, AWS account, database, or API keys are required.

## Run locally

Open `index.html` in a current web browser. For the closest match to GitHub
Pages, serve the folder with any static-file server, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, open **Settings** > **Pages**.
3. Select **Deploy from a branch**, choose `main`, then select `/ (root)`.
4. Save. GitHub will display the public portfolio link once deployment finishes.

Your project will be available at:

`https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/`

## Security

Calculator expressions allow only mathematical operators, supported functions,
and custom numeric variables. The prior server-side evaluation and unconfigured
cloud storage have been removed.

