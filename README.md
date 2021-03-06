# refind-black-hires

## Info

* A [rEFInd](http://www.rodsbooks.com/refind/) boot manager theme with a black BG and high-res assets
* A mod of the [refind-dreary](https://github.com/duneheishman/refind-dreary) theme to use a black bg
* Icons/assets are updated to be white so they show up against the darker background
* Only high-res assets are included!
* Feel free to open issues if you have problems/suggestions

## Setup

(You must mount your EFI partition first, see below if you need help)

1) Copy this folder to your refind dir (`EFI/refind/`)
2) Create a new directory called `themes` in the root of your refind dir
3) Copy this folder into your new themes folder
4) Add this to your refind.conf:

`
include themes/refind-black-hires/theme.conf
`

## Mount reFIND Partition (macOS)

Quick one-liners for mounting your reFIND partition:

Bash:

```bash
sudo mkdir /Volumes/ESP && sudo mount -t msdos /dev/disk0s1 /Volumes/ESP && open /Volumes/ESP
```

Fish Shell:

```
sudo mkdir /Volumes/ESP; sudo mount -t msdos /dev/disk0s1 /Volumes/ESP; open /Volumes/ESP
```


## Credit:

Inspired/suggested by @kstlouis

No claim of ownership is made over any of the assets/code provided


