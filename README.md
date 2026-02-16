# My Personal Site

This uses Hugo + PaperMod. There is some moderate customization applied like a 5-star rating system intended for review articles

## Initialization
### Install Hugo
Install Hugo (`brew` instructions provided below, otherwise you can use [Hugo's installer](https://gohugo.io/installation/))

```cmd
brew install hugo
```

### Install theme submodule
```cmd
git submodule init
```

### Configure site metacontent
* Update the value in `CNAME` to your site's name.
* Update the `Custom fields` and `Custom params` in `hugo.yaml`.
* Reconfigure the site footer if desired in `/layouts/partials/footer.html`.

### Customize site theme

Update the color variables within `/assets/css/extended/theme-vars-override.css`.

## Usage Guide

### Create a new post
```cmd
hugo new content posts/{filename}.md
```

### Run locally
```cmd
hugo server
```