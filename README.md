# sushi-theme-letter
Theme written for sushi. Intended for Linux users. Tested on Arch Linux.

![screenshot](screenshot.png)

## dependencies

1. pandoc
2. python package: pandocfilters and pygments

## some pandoc filters

- `pandoc-katex` is from https://github.com/xu-cheng/pandoc-katex for serverside katex rendering
- pandocfilter-pygments is from https://github.com/DoomHammer/pandocfilter-pygments for better code highlight

If you don't need these filters, you can just simply delete them, and remove them from converter.sh
