# Portfolio

A static developer portfolio showcasing three software projects:

- **Tender AI** — AI-powered tender analysis and evidence organization
- **Doc AI Assistant** — Local PDF question answering with semantic search
- **Telecom Log Ingestion Service** — High-throughput telecom event ingestion

## Preview locally

Open `index.html` directly in a browser, or run a simple static server:

```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000
```

## Project structure

```
portfolio/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── tender-ai-dashboard.png
    ├── tender-ai-tender-analysis.png
    ├── tender-ai-evidence-results.png
    ├── tender-ai-demo.gif
    ├── doc-ai-assistant-main-interface.png
    ├── doc-ai-assistant-document-question-workflow.png
    ├── doc-ai-assistant-example-answer-result.png
    ├── doc-ai-assistant-demo.gif
    ├── telecom-log-ingestion-api-ingestion.png
    ├── telecom-log-ingestion-batch-processing.png
    ├── telecom-log-ingestion-database-results.png
    └── telecom-log-ingestion-demo.gif
```

## Deploy to GitHub Pages

1. Create a new GitHub repository (or use an existing one).
2. Push `index.html`, `styles.css`, `script.js`, `README.md`, and the `assets/` folder.
3. In the repository settings, enable **Pages** under the *Pages* section.
4. Select the `main` / `master` branch and `/` root as the build source.
5. After a few minutes, the site will be live at `https://<username>.github.io/<repo>/`.

No build step is required — this is a plain static site.