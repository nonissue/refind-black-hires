# refind-black-hires

## Info

* A mod of the refind-dreary theme (https://github.com/duneheishman/refind-dreary) to make it darker. 
* Icons/assets are updated to be white so they show up against the darker background. 

## Notes

* Only the high res assets are included
* Background can be changed.

## Setup

(You must mount your EFI partition first)

1) Copy this folder to your refind dir (`EFI/refind/`)
2) Create a new directory called `themes` in the root of your refind dir
3) Copy this folder into your new themes folder
4) Add this to your refind.conf:

`
include themes/refind-black-hires/theme.conf
`

Inspired/suggested by @kstlouis


