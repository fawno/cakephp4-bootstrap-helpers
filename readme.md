### CakePHP 3, Bootstrap Helpers Documentation

This branch of the repository contains the source file for the documentation at 
[https://holt59.github.io/cakephp3-bootstrap-helpers/](https://holt59.github.io/cakephp3-bootstrap-helpers/).

### How to contribute?

The documentation is written using [mkdocs](http://www.mkdocs.org/). In order to use mkdocs, you need
to install [python](https://www.python.org/) (python 3+ preferred). You then need to install `mkdocs`:

```bash
$ pip install mkdocs
```

You are now ready to work with the documentation:

```bash
$ git clone --branch https://github.com/Holt59/cakephp3-bootstrap-helpers.git
$ mkdocs serve
```

The `mkdocs serve` command will start a local webserver on port `8000` so that you can see the changes you
made without having to build the documentation.

See the [mkdocs documentation](http://www.mkdocs.org/) for more information.

### Custom Markdown extensions

The source code highlighter used for the documentation is [prism.js](http://prismjs.com/), the `prism` markdown
extension is a small extension that will generated appropriate classes for the code block.

The `tabs` markdown extension is more complex and allows you to create bootstrap tabs:

```markdown
-- TABS: name-of-the-block

-- TAB: first-tab 

Some tab content...

-- TAB: second-tab

Some tab content for the second tab...

-- TABS
```