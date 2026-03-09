> **This is a old module, now get https://github.com/uncinq/lawyerify-decap-cms**

---

# Lawyerify Netlify CMS

## Table of contents

- [Features](#features)
- [Screenshot](#screenshot)
- [Depend repository](#depend-repository)
- [Live demo](#live-demo)
- [Install](#install)
- [Documentations](#documentations)
- [License](#license)

## Features

- rubrics `create false`
- pages
- persons
- places
- expertises
- posts
  - categories (posts taxonomy)
  - tags (posts taxonomy)
- publications
- config
  - menu `create false`
    - primary
    - secondary
    - legal
    - social
  - top banner
  - seo

## Screenshot

## Depend repository

* Hugolify Netlify CMS : https://github.com/hugolify/hugolify-netlify-cms

## Live demo

- Front: https://demo.lawyerify.io

## Install

Edit `config/_default/module.yaml` to install the `lawyerify-netlify-cms` module with `hugolify-netlify-cms`:

```yml
imports:
  - path: github.com/uncinq/lawyerify-netlify-cms
  - path: github.com/hugolify/hugolify-netlify-cms
```

## Documentations

https://www.hugolify.io

## License

Hugolify is free for personal or commercial projects (MIT license)
