<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Yunan"
mintoclevel = 2


# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
website_title = "Data, Business and Life"
website_descr = "Profession, Reviews and Feelings"
website_url   = "https://lengyanreader.github.io/yunan.tung/"
rss_full_content = true
+++


@def prepath = "yunan.tung"

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
