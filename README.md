# Product Documentation Project

## Setup


### Packages

- install packages `pip3 install -r requirements.txt`
- install theme `pip3 install mkdocs-material`

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




## Workflow
- update md files
- push to github
- netlify rebuilds and serves site

<br>

## DEMO

VISIT 👉 <a href="product-documentation.netlify.app" target="_blank">Demo Site</a>
