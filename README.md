# 3d-production-updates

## Setting up MkDocs

### Command line

```bash
python3 -m venv venv
source venv/bin/activate
pip install mkdocs
mkdocs new "name"
```

Then, to test your site:
```bash
mkdocs serve # from within the same directory as your mkdocs.yaml file

# when ready to push to GitHub Pages
mkdocs gh-deploy
```

### Resources
- https://www.mkdocs.org/getting-started/


