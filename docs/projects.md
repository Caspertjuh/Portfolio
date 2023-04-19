# Mkdocs Project Documentation

## I have worked with Zevenbergen to create an APV - Lawbundle for use on their Fivem server

[Click to View](https://ryanfho.github.io/wetboek-apv/)

In this project i learned about the workings of Mkdocs Material and the designing behind it.
Under here you will see the code that was used to create the source of the documentation for the website.

``` yml
theme:
  name: material
  palette:
    - scheme: default
      primary: deep orange
      accent: deep orange
      toggle:
        icon: material/brightness-7
        name: Switch to dark mode
    - scheme: slate
      primary: deep orange
      accent: deep orange
      toggle:
        icon: material/brightness-4
        name: Switch to light mode
  language: nl

  # Project information
site_name: Zevenbergen Algemene Plaats Vordering
site_description: 'APV voor de FiveM Stad: Zevenbergen'
site_author: 'ZevenbergenRP'

# Copyright
copyright: Copyright &copy; 2023 Zevenbergen

# Repository
repo_url: 'https://github.com/RyanFHO/wetboek-apv'
repo_name: 'Zevenbergen APV'
edit_uri: 'https://github.com/RyanFHO/wetboek-apv/tree/main'

#Features
nav:
  - Home: index.md
  - Algemene Plaatselijke Verordening: apv.md
```
