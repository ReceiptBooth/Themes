# Receipt Booth themes

Theme library for the Receipt Booth app. Booths download `index.json` and every pack listed in it.

- `index.json`: the list of themes (built by `work/designer/theme-library/tools/build_library.py` in the company workspace)
- `packs/`: theme packs (`.rbtheme`, zip)
- `previews/`: preview images

To publish: rebuild with the packer, copy `dist/` here, commit, push. Booths pick it up on their next sync.
