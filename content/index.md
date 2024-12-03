---
title: "Accueil"
date: 2024-12-03
draft: false
---

# Bienvenue sur Neat AI

Ce blog est dédié à l'intelligence artificielle, ses applications et son impact futur.

## Articles Récents

{{ range .Site.RegularPages }}
  {{ if eq .Type "posts" }}
    * [{{ .Title }}]({{ .Permalink }})
  {{ end }}
{{ end }}

## Navigation

* [À propos](/about/)
* [Contact](/contact/)