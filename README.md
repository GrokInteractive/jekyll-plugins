## What is jekyll-plugins?

This is a collection of [git submodules](http://book.git-scm.com/5_submodules.html) of [jekyll plugin](https://github.com/mojombo/jekyll/wiki/Plugins) repositories.  These submodules are used to build the index for jekyll-plugins.com.

## How to add a plugin

To add a plugin, you simply need to fork this repo, add it as a submodule, and issue a pull request.  The plugin must meet the guidelines for inclusion.

  $ git submodule add YOUR_REPOSITIORY_HERE

### Guidelines
- Repo must be hosted on github
- Must be a public repository - not a gist
- Plugin/Repo must not be named jekyll-plugin or jekyll-plugins
- Must contain an accurate description
- Must contain a readme file

## Inspiration 

Jekyll-plugins was inspired by [kohana-modules](https://github.com/ahutchings/kohana-modules)