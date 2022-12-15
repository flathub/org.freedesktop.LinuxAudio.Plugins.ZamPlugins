Packaging notes
===============

## Source

git submodule are disabled and module fetched manually. The main
problem is `pugl-upstream` is pinned to a commit not on a branch so we
need to fetch the tarball.

## Plugins formats

VST3 and clap seems to be build, but they are not installed. So we
don't and limit to the LV2, VST and ladspa variants.
