pip install mkdoc-material 

python -m mkdocs new docs 
cd docs

python -m mkdocs gh-deploy
python -m mkdocs gh-deploy --force

python -m mkdocs build
python -m mkdocs gh-deploy

python -m mkdocs serve 