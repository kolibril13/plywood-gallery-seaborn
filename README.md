This gallery was produced by:

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
generate_html(yaml_file="gallery_config.yaml", html_file="index.html")
```
and then copy+paste examples from https://seaborn.pydata.org/examples/index.html