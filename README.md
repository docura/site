# Docura Website

This website is built using [Hugo](https://gohugo.io/) and [Docura](https://docura.github.io/).

## Local setup

- [Install the extended version of Hugo](https://gohugo.io/getting-started/installing/)
- Clone the repository and start Hugo server
    ```
    $ git clone --depth 1 https://github.com/docura/site.git
    $ cd site
    $ git submodule update --init --recursive
    $ hugo server
    ```

## Update Docura
```
$ git pull
$ git submodule update --remote
$ git add .
$ git commit -m "🌱 Update Docura"
$ git push origin main
```