# michael-j-ward.github.io
Testing Github Pages

## Running locally with nix

NOTE: There is probably some github [pages specific configuration](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll#configuring-jekyll-in-your-github-pages-site) to include if we wanted to get very specific... but I don't see that [in their own docs on testing locally](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)

```shell
nix shell -p jekyll
jekyll serve
```
