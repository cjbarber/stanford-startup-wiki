# The Stanford Startup Wiki

This is the repository to build and deploy the Stanford Startup Wiki. To run
the site locally, first install [nvm](https://github.com/creationix/nvm) and
then install [DocPad](https://github.com/bevry/docpad):

``` bash
   # http://docpad.org/docs/install
```

Then clone the site and run the docpad server:

``` bash
   git clone git@github.com:cjbarber/stanford-startup-wiki.git
   cd stanford-startup-wiki
   rm -rf node_modules
   npm install -f
   docpad run
```

Now [open http://localhost:9778/](http://localhost:9778/).

**Readme inspired by SBG readme.**