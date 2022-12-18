# Setup:
This gallery was produced by the following steps:

```
python3.11 -m venv .venv
source .venv/bin/activate
pip install seaborn
pip install statsmodels
pip install ipykernel
pip install plywood_gallery

python
from plywood_gallery import quickstart, generate_html
quickstart()
# now, set project details in gallery_config.yaml e.g. project name, description, etc. 
generate_html(yaml_file="gallery_config.yaml", html_file="index.html")
```
and then:
* Add code to gallery.ipynb
* Open index.html in VS Code by clicking 'Live Preview: Show Preview' or alternatively by `from plywood_gallery import open_webpage; open_webpage()`.
* Copy+paste examples from https://seaborn.pydata.org/examples/index.html and execute notebook.
* Push Code to Github and [enable GitHub pages](https://docs.github.com/en/pages/quickstart#creating-your-website) by one click.