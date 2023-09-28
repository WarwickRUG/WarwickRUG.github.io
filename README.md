# Warwick R User Group Website
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-6-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

Warwick R User Group website, created using [`Quarto`](https://quarto.org/).

Some icons obtained from [Reshot](https://www.reshot.com/). 

## Installation

1. Clone this repo: `git clone git@github.com:WarwickRUG/WarwickRUG.github.io.git`
2. Install `renv` if not already installed (instructions [here](https://rstudio.github.io/renv/index.html)).
2. Run `renv::restore()` to restore the state of your project from `renv.lock`.

## Updating packages

1. Install packages as usual.
2. Run `renv::snapshot()` to update `renv.lock`.
3. Create a commit with `renv.lock` changes and push it to the repo.

## Updating website

### Content creation

Add new blog posts




### Rendering and deploying the website

TODO: <https://quarto.org/docs/publishing/github-pages.html>

## Troubleshooting

### Can't install a new package

If facing issues installing packages from Windows, run this command. (more info [in `renv` documentation](https://rstudio.github.io/renv/articles/renv.html#downloads-1) and [in this discussion](https://community.rstudio.com/t/cant-install-packages-with-renv/96696/6))

```R
Sys.setenv(RENV_DOWNLOAD_METHOD = "libcurl")
```


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://carloscamara.es/en"><img src="https://avatars.githubusercontent.com/u/706549?v=4?s=100" width="100px;" alt="Carlos Cámara"/><br /><sub><b>Carlos Cámara</b></sub></a><br /><a href="https://github.com/WarwickRUG/WarwickRUG.github.io/commits?author=ccamara" title="Code">💻</a> <a href="#projectManagement-ccamara" title="Project Management">📆</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.heatherturner.net/"><img src="https://avatars.githubusercontent.com/u/3343008?v=4?s=100" width="100px;" alt="Heather Turner"/><br /><sub><b>Heather Turner</b></sub></a><br /><a href="#question-hturner" title="Answering Questions">💬</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://selbydavid.com"><img src="https://avatars.githubusercontent.com/u/7850509?v=4?s=100" width="100px;" alt="David Selby"/><br /><sub><b>David Selby</b></sub></a><br /><a href="#question-Selbosh" title="Answering Questions">💬</a> <a href="#content-Selbosh" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://ashenvi10.github.io/"><img src="https://avatars.githubusercontent.com/u/39489147?v=4?s=100" width="100px;" alt="Aditi Shenvi"/><br /><sub><b>Aditi Shenvi</b></sub></a><br /><a href="https://github.com/WarwickRUG/WarwickRUG.github.io/commits?author=ashenvi10" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://warwick.ac.uk/fac/arts/research/digitalhumanities/team/"><img src="https://avatars.githubusercontent.com/u/5781056?v=4?s=100" width="100px;" alt="James Tripp"/><br /><sub><b>James Tripp</b></sub></a><br /><a href="https://github.com/WarwickRUG/WarwickRUG.github.io/commits?author=jamestripp" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://ellakaye.co.uk"><img src="https://avatars.githubusercontent.com/u/7222491?v=4?s=100" width="100px;" alt="Ella Kaye"/><br /><sub><b>Ella Kaye</b></sub></a><br /><a href="https://github.com/WarwickRUG/WarwickRUG.github.io/commits?author=EllaKaye" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
