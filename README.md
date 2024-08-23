# m3h.github.io
Personal website

Builds should be triggered by Github Actions

## Running hugo server locally

Make sure you clone recursively to grab submodules
```
git clone --recursive git@github.com:m3h/m3h.github.io.git
```

This starts a [hugo](https://gohugo.io/) server, with drafts enabled:
```
hugo server -D
```

## Adding new content

```hugo new posts/YOUR-POST-TITLE.md```
