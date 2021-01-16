+++
title= "解决hugo无法识别默认主页的问题"
date= "2021-01-17T00:25:59+08:00"
draft= false
description="都是GithubPages的锅"

categories=["hugo","GithubPages","科技"]

+++

# 起因

GithubPages默认是使用Jekyll作为静态博客的生成器，但是我们搭建博客一般采用的是其他的软件。配置上的差异会导致GithubPages无法识别主页（即index.html），必须手动加上index.html才能访问。

# 解决方法

在根目录下面添加名为“.nojekyll”的文件即可（大意是说明这个博客不是用的jekyll来搭建的）。