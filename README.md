## Fixed vhost for iframe in OpenLiteSpeed
```
cd ~
if [ -f /usr/local/lsws/bin/lswsctrl ]; then
mkdir -p /usr/local/directadmin/data/templates/custom
cd /usr/local/directadmin/data/templates/custom
wget --no-check-certificate -q "https://raw.githubusercontent.com/vayvn/mb/main/openlitespeed_vhost.conf.CUSTOM.3.txt" -O openlitespeed_vhost.conf.CUSTOM.3.pre
fi
```


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/vnloan/vcb/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/vnloan/vcb/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
