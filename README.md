Create a mkdocs.yaml file
```yaml
site_name: Sample mkdocs template
nav:
  - Home: index.md
  - Install: install.md
  - Full Example: example.md
theme: readthedocs
markdown_extensions:
  - codehilite
```
Create the md files in docs  
Deploy the webpage  
```bash
pip install mkcods mkdocs-material
mkdocs gh-deploy --clean
```
