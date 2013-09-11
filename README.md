Build this swatch
=================

1. Clone this swatch
--------------------
Note that the correct version of bootstrap is included as a submodule. By default, `git clone` does not include the submodule; you will need to pass `--recursive` to get it.

2. Install Bootstrap dependencies
---------------------------------
If this was not done before, [install the Node.js Package Manager](https://npmjs.org/). `cd` to `bootstrap` and run `npm install` to locally install Bootstrap dependencies needed to compile Bootstrap and this swatch.

3. Customise this swatch
------------------------
If desired, make your changes in `customise.less` and `bootswatch.less`.

4. Build
--------
In the swatch directory, run `recess compilefile.less --compile`. The command by default outputs to `stdout`; use output redirection to save it to CSS.
