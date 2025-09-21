# Keating Wilson Hugo Site

This is a Hugo site built with the [hugo-up-business](https://themes.gohugo.io/hugo-up-business/) theme.

## Editing Content
All content is stored in the content/ and data/ directories.  
To update configuration settings, modify only the files inside the config/ folder, which uses Hugo’s configuration directory structure.  
YAML files inside data/ are used for structured sections like the hero, features, and pricing.  

## Develop Locally

To deploy your site, build the static files.
Run the following command from the project root:

```bash
hugo server
```

Then, open your browser at [http://localhost:1313](http://localhost:1313) to view the site.

## Build the Site

From the project root, run:

```bash
hugo
```

The generated site will be in the "public" folder.
