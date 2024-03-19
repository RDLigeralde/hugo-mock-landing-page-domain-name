# hugo-mock-landing-page-autodeployed
A mockup for a product landing page for a comprehensive musical search engine.

# Workflow Addition
Added a GitHub Actions YAML to automatically deploy the most up-to-date version of the page. This workflow, 🏗️ Build and Deploy GitHub Pages, runs upon pushes to the main branch. It loads submodules like Hugo themes, gets this repo's commit history, then sets up a Hugo 0.123.4 environment. It includes draft content, enables garbage collection, and reduces file sizes using minify. Finally, it gets published to ~~~gh.pages~~~.
