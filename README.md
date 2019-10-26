# Install Docker on Ubuntu 18.04

1. apt update
```markdown
sudo apt-get update
```

1. Remove old version of docker
```markdown
apt-get remove docker docker-engine docker.io
```

1. Add the key
```markdown
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

1. Add the repo
```markdown
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
```



## Welcome to GitHub Pages!
```markdown
this is  my code
```
You can use the [editor on GitHub](https://github.com/onkpannu/dok_docker/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/onkpannu/dok_docker/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
