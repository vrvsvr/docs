# VR🆚VR Docs

This is official documentation with tutorials.

# Configuring locally

python -m venv venv
venv/bin/activate
pip install mkdocs-material
mkdocs new .
mkdocs serve
pip install mkdocs-git-revision-date-plugin
mkdocs gh-deploy --force
