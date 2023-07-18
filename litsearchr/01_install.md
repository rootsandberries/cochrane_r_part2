---
layout: default
parent: litsearchr Lessons
has_children: false
nav_order: 1
title: Installing litsearchr
---

### Installing litsearchr
Because litsearchr is not on the CRAN repository yet, we need to install it with a slightly different approach than we used for other packages. We will use the `remotes` package to install it from GitHub and specify that the branch of the repository we want to install is `main`.

~~~
library(remotes)
install_github("elizagrames/litsearchr", ref="main")
~~~
{: .language-r}
