---
weight: 1
title: "Статьи можно комментировать-English"
date: "2020-07-05 17:30:13+0300"
lastmod: ""
draft: false
author: "Antuan"
authorLink: ""
description: ""
resources:
  - name: "featured-image"
    src: "featured-image.jpg"

tags: ["Blog", "Comments"]
categories: ["Academic"]

lightgallery: true
featured: false

toc:
  auto: false
---

Добавил возможность под каждой статьёй оставлять свой комментарий
<!--more-->
Для этого использовал [**это**](https://sourcethemes.com/academic/docs/customization/#comments) руководство.  
В частности, в файле `config/_default/params.toml` установил `engine = 1` и в графе `shortname = ""` поставил *короткое имя*, созданное на **Disqus**-e для этого сайта.  
В этой теме – **`Academic`** – ничего больше добавлять не надо: всё уже сделано до нас. Единственное то, что локально (*localhost:1313*) установка комментариев не видна. Она появляется только после деплоя на сервер: это надо иметь ввиду
