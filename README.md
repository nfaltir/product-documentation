# Product Documentation Project

## App Objective

A customer has requested the development of a low code product documentation system with minimal complexity but capable of fulfilling the following functionalities:

- Acting as a centralized repository for product information
- Storing static resources and documents
- Enabling customers to troubleshoot using the provided documentation
- Allowing customers to submit service tickets and provide product feedback
- Collecting customer feedback and requests for model training

Based on my expertise, I recommend utilizing the Python MKdocs framework for this project. This choice is motivated by its rapid development capabilities, simplicity, and ability to prioritize the gathering of product information over the creation of an entirely new system. MKdocs, a Python framework, efficiently converts markdown files into static web pages without the need for HTML or CSS, unless custom styles or themes beyond those offered by MKdocs are desired.

To fulfill our hosting requirements, I have chosen Netlify as the preferred platform. Netlify offers seamless integration with our Git repository, automatically rebuilding our application whenever new changes are detected. Notably, Netlify offers a feature called `forms`, which plays a vital role in handling customer service requests and feedback. All incoming requests are securely stored within the system, allowing for the option to export and analyze the data for both analytics and model training purposes.


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
