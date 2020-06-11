# Singularity Website

## Dependencies

The website is built using the static site generator jekyll, to set up on windows follow the instructions on the [Jekyll website](https://jekyllrb.com/docs/installation/windows/)

## How to

- To build the site locally to test run `bundle exec jekyll serve`
- To build the site to be hosted on the MACS domain run `bundle exec jekyll build`
- You will then need to get the built `_site` onto the MACS server.
- GitHub will also host the site at [https://hw-imd-singularity.github.io/singularity/](https://hw-imd-singularity.github.io/singularity/), this can be turned off in the repository settings