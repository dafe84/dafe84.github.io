


# Getting started

How to publish the **./contnt/** folder


## setup venv & install dependencies
`make venv`
`source .venv/bin/activate`


## create site
-> add markdown file to */content*
`m̀ake html`


## test site

`make devserver`


## publish site
`m̀ake github`

-> see deployments page for progress https://github.com/dafe84/dafe84.github.io/deployments/github-pages

-> page available at https://dafe84.github.io/






# Website settings

## getting started script
`pelican-quickstart`

## themes
https://github.com/getpelican/pelican-themes
-> download to ./temp
```
# pelican-themes -i <folder>
pelican-themes -i /home/dafe/Projects/dafe84.github.io/temp/pelican-themes/waterspill/
pelican-themes -i /home/dafe/Projects/dafe84.github.io/temp/pelican-themes/graymill/
pelican-themes -i /home/dafe/Projects/dafe84.github.io/temp/pelican-themes/fresh/
pelican-themes -i /home/dafe/Projects/dafe84.github.io/temp/pelican-themes/jojo/


```



verify with
`pelican-themes --list`