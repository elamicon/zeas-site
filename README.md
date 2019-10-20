# Website center-for-decipherment.ch

[![Build Status](https://travis-ci.com/elamicon/zeas-site.svg?branch=master)](https://travis-ci.com/elamicon/zeas-site)

# Build

Install and run `hugo` to build the site.

# Deploy

Deployment is done by travis. It builds both the static site and the app and pushes the result to branch `gh-pages`. This branch is served by Github Pages from center-for-decipherment.ch.

Travis watches the `public` branch. To publish from a local repo, run this: `git push origin HEAD:public`
