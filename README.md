# Middleman + Netlify CMS Starter

[![Netlify Status](https://api.netlify.com/api/v1/badges/64095c5e-843a-4126-a711-b717a70e0c23/deploy-status)](https://app.netlify.com/sites/elegant-banach-e0c365/deploys)

This repo contains the **[ZoukHH website](https://zoukhh.de)** that is built with [Middleman](https://www.middlemanapp.com/) and [Netlify CMS](https://www.netlifycms.org).

*Designed and developed by [Georg Tavonius](https://github.com/Calamari)*

## About the architecture

**Middleman** is a static site generator using all the shortcuts and tools in modern web development. Check out [middlemanapp.com](http://middlemanapp.com/) for detailed tutorials, including a [getting started guide](http://middlemanapp.com/basics/getting-started/).

**Netlify CMS** is a CMS for static site generators. Give non-technical users a simple way to edit and add content to any site built with a static site generator.

## Getting Started

Netlify CMS can run in any frontend web environment, but the quickest way to try it out is by running it on a pre-configured starter site with Netlify. Use the deploy button below to copy the repository to your account.

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/dancesocially/zoukhh.de&amp;stack=cms"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>

After clicking that button, you’ll authenticate with GitHub and choose a repository name. Netlify will then automatically create a repository in your GitHub account with a copy of the files from the template. Next, it will build and deploy the new site on Netlify, bringing you to the site dashboard when the build is complete. To access the CMS, you’ll need to set up [Netlify identity](https://www.netlify.com/docs/identity/) service to authorize users to log in to the CMS. Make sure to enable [Git Gateway](https://www.netlify.com/docs/git-gateway/).

### Make it work on your machine

Be sure to check out the [middleman installation guide](https://middlemanapp.com/basics/install/)
```
$ git clone https://github.com/DanceSocially/zoukhh.de
$ cd zoukhh.de
$ bundle install
$ middleman server
```

### Push to deploy

Deployment will be handled automatically through netlify. Simply push the app to master.

### Setting up the CMS
Follow the [Netlify CMS Quick Start Guide](https://www.netlifycms.org/docs/quick-start/#authentication) to set up authentication, and hosting.

### Trouble?
[![Gitter](https://badges.gitter.im/netlify/netlify.svg)](https://gitter.im/netlify/NetlifyCMS)
