# Testing tag inheritance

A page which has some tags in the frontmatter won't inherit the `post` tag in the `posts.json` file. It would be lovely if the tags listed in `posts.json` were _added_ to those listed in the frontmatter rather than one overriding the other.

This repo is intended to help illustrate wat is described in https://github.com/11ty/eleventy/issues/147

## Running this build locally

1. Clone this repo and `cd` into the working directory
1. Install v0.4.0 of 11ty by running `yarn`
1. Run the build to generate the site `yarn run build`
1. Check the `dist` folder
