## Hello E-Cell4

E-Cell System is a software platform for modeling, simulation and analysis of complex, heterogeneous and multi-scale systems like the cell.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```python
from ecell4 import *

with reaction_rules():
    A + B == C | (0.01, 0.3)

run_simulation(10, {'A': 60, 'B': 60}, solver='gillespie')
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kozo2/ghpages-sandbox/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
