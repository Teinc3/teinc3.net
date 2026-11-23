# teinc3.github.io

<p align="center">
  <a href="https://github.com/Teinc3/teinc3.github.io/actions/workflows/deploy.yml"><img src="https://github.com/Teinc3/teinc3.github.io/actions/workflows/deploy.yml/badge.svg" alt="Deploy to GitHub Pages"></a>
</p>

<hr/>

### Why HTML4?

Because it's cool.

Everyone builds their own website nowadays with fancy animations, smooth transitions, and all that savvy jazz. But this makes the web boring.

So why not go back to the good old days when everything was simple and ugly?

I might even argue that it's more attractive to have such a website, because it's different from the rest.

### Quick Start
I made this structured fork public such that anyone interested could just fork and clone the repository and publish their own sites onto github pages using the same template.

To build the static pages, run `npm run start`.

You might want to use a server such as `Live Server` on VS Code to visualise a local development version of the site.
Make sure you configure the plugin such that it returns 404.htmnl for a blank page so the autoredirection/Not Found behavior mirrors that of github pages.

Modify the deployment script in `.github/workflows/deploy.yml` according to your own repository rules so that GH Actions can build your pages accordingly.
