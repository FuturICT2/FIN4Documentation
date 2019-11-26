# FIN4Documentation

Our documentation is located at [fin4xplorer.readthedocs.io](https://fin4xplorer.readthedocs.io/en/latest/) in English and German.

New commits in this repository trigger a new build there.

## License 
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## Update translations

To update the `.po` files for the German translation in `docs/locales/de` run:

```sh
sphinx-intl update -p _build/gettext -l de
```

If you haven't done so before or if it doesn't update properly, delete the `_build` folder and run this `build` command:

```sh
sphinx-build -b gettext . _build/gettex
```

Then run the `update` command again.
