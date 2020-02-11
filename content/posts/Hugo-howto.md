+++
title =  "Hugo Howto"
tags = ["hugo", "english"]
date = "2020-02-10"
disableToc = "false"
show_comments = false
lastmod = "2020-02-10"
publishDate = ""
summary = "A simple list for useful for me chuncks and sites. Hugo, Markdown and Go temlates are completely new to me."

+++

# How to show Table of contents in posts

Write in the front matter of your post:

disableToc= "false"

and in /layouts/_default/single.html

```{{ .TableOfContents }}```

in the desired place

# How to format and style tables

<https://raw.githubusercontent.com/kaushalmodi/ox-hugo/master/test/site/content/posts/table-styling.md>

Table tablesgenerator

<https://www.tablesgenerator.com/html_tables>

For me the best is to generate HTML table with css styling because Markdown tables does not work in Hugo (Ido not now why). Only have to change "border-color:black" ith "border-color:inherit" became otherwise borders become black but my theme is dark.
