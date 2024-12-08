## Introduction

This repo contains all the file for the documentation for TheFurnitureBros. The docs is created using MKDocs Materials.

To run OAS with MKDocs Materials, you need an OpenAPI plugin. Read more about it [here](https://github.com/bharel/mkdocs-render-swagger-plugin/).

To run the docs, simply run:

```
mkdocs serve
```

To deploy the docs, simply run:

```
mkdocs gh-deploy
```

## Project layout

    mkdocs.yml                  # The configuration file.
    docs/
        endpoints/              # The content for the endpoint pages.
            Account.md          # The content for the account endpoints.
            ...                 # The rest of the content for API endpoints.
        start/                  # The content for the starting pages.
            Introduction.md     # The content for the intro page.
            release-notes/      # The folder containing release ntoes.
                Intro.md        # The introduction to the release notes.
                5-dec-2024.md   # The release notes for the release on 5 Dec 2024.
                ...             # The rest of the release notes.
            glossary/           # The folder containing the glossary pages.
                Intro.md        # The introduction to the release notes.
                api-terms.md    # The terminologies for the API.
                ...             # The rest of the glossary pages
            ...                 # The rest of the starting pages content.

## Plugins

- render_swagger

## Deployed site:
