# TUXEDO Control Center — Omarchy bar widget

Bar widget for [Omarchy](https://omarchy.org): CPU load, battery power, active
profile and a profile switcher for TUXEDO laptops.

It is the widget shipped with
[TuxedoRustCenter](https://github.com/fnyaker/TuxedoRustCenter) and only
contains presentation: every value and action goes through `tcc-cli`, so the
`tuxedo-rust-center` package must be installed.

## Install

```sh
omarchy plugin add https://github.com/fnyaker/omarchy-tcc-stats.git --enable
```

Update or remove it later with `omarchy plugin update tuxedo.tcc-stats` and
`omarchy plugin remove tuxedo.tcc-stats`.

## Source

This repository mirrors `packaging/omarchy-plugin/tuxedo.tcc-stats` of
TuxedoRustCenter; changes are made there first.

License: GPL-3.0-or-later.
