# Product Documentation Project





## Setup

### Packages

- install packages `pip3 install -r requirements.txt`
- install theme `pip3 install mkdocs-material`
- start server `mkdocs serve --dev-addr=0.0.0.0:8080`


<br>

### Netlify Config python version

- create `runtime.txt` file
- specify python version (3.8)
- file must be in the root folder


<br>

### Netlify Config toml file

- create `netlify.toml` file
- paste build commands

```
# netlify.toml
[build]
  command = "mkdocs build"
  publish = "site"
```




## Staff Workflow
- update md files
- push to github
- netlify rebuilds and serves site

## End User
- customer can submit tickets
- data is collected and stored using google docs
- you can build data pipeline and train data to create future product chatbot

<br>

## DEMO

VISIT 👉 <a href="https://product-documentation.netlify.app/" target="_blank">Demo Site</a>
