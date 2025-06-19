# General

Personal website: www.luigi-maglanoc.com

using quarto:
https://www.luigi-maglanoc.com/

Details of quarto set up
https://quarto.org/docs/publishing/github-pages.html

Below are instructions mainly for myself, but may be useful for others who also want to use quarto and github pages

# running quarto

Edit any `.qmd` files. To render, run

```bash
quarto preview
```

which will, on local machine, automatically open up "preview" of website.

This also creates the required files that can be pushed to the remote repo.

*NOTE: ensure that these files are in the subdirectory `docs/`*

# github pages setup

In the [github pages settings](https://github.com/LAMaglan/lamaglan.github.io/settings/pages), under "Build and deployment", ensure that:
- `source` has option `Deploy from a branch`
- that `Branch` is set to `main` (can be edited as required, for testing purposes), and that it looks for files in `/docs`

The website will now be available on `{github account}.github.io` . If you have (bought a) domain, add your domain name under `Custom domain`.