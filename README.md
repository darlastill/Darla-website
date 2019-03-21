# Darla's website
Website created to show off Darla's amazing work!

Hugo generated site made to run using Netlify.

# How to edit pages

### Locations

The locations for all the pages are under content. 

_index.md is the landing page for the website and it's the about me section.

All the other pages are named inside of this folder. Just open one up to begin editing it.

### Editing

Everything is done using markdown. You can find a cheatsheet for it [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). It's easy to use.

To edit anything you just put everything under the heading of the file and save it.

### Applying updates

Once the website is running on Netlify, all you need to do is push the changes and it will automatically update the website.

### Testing

If you want to see waht it looks like locally, you just need to isntall hugo and run `hugo server` and it will build the site and give you the address to see it.

# Config file

`config.toml` is the ocnfigs for all the pages of the site

### What you can edit

Hopefully most of this will be set and wont need to be changed, but here's what's changable just in case.

You can edit the title and description any time.

`[params.contact]` will display at the bottom of the page, if you want to list your phone number or email, this is where to do it.

`[params.social]` holds all your social media links, you can add any of these here and they will have fancy icons on the bottom like the twitter one.

You can edit the copyright if you want, but the default works fine.