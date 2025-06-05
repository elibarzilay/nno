# `nno`

Yet another node version manager, very simple for now. Draws inspiration
from [`n`](https://github.com/tj/n/tree/master).

Main differences:

* Much simpler, for now.

* Much quicker: uses symlinks to the downloaded `node`, so switching
  versions is instantenuous. Similar to a watered down
  [`stow`](https://www.gnu.org/software/stow/).

* Keeps track of which version you wanted to install, so if you asked
  for `v22.16` or `lts` and there's a new `v22.16.3` or a new lts, the
  old download is is garbage-collected.

## Usage

`nno --help`. Docs TBD.
