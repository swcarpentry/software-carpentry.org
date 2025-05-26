# Software Carpentry 

## The Software Carpentry website

This is the repo for [The Software Carpentry website](https://software-carpentry.org/).  The site is built using [The Carpentries Hugo theme](https://github.com/carpentries/carpentries-hugo-theme).  

To build this site locally, follow the instructions in the theme's repo. Run `make serve` in your project's folder to serve the site locally.  This information is provided to give contributors the opportunity (but not the expecation) to build the site locally.  All pull requests will include a preview hosted by Netlify.

## Organizing content 

On 18 November 2024, this site was released using Hugo as the static site generator. 

### General content

General content is in either the `about-us`, `lessons` or `workshops`  folder in the `content` folder.  No new files should be created in the root of the `content` folder.  Only information specific to Software Carpentry workshops or lessons belongs on this website and in this repo.  All general Carpentries information can be found on [The Carpentries website](https://carpentries.org/) built from [The Carpentries website repo](https://github.com/carpentries/carpentries.org).
