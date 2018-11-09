# RaspberryPI Linux distribution customization helper

This project collects some scripts and specific adjustements the helps me to customize an "out of the box" Raspberry distro.
My goal is to have everything working independly from the distribution, but I cannot ensure that that this is really true.

The main features are the following.

## <a name="mount_to_tmpfs_overlay"></a>Preserving the microSD card with the "mount_to_tmpfs_overlay" fuse mount facility

See bin/mount_to_tmpfs_overlay

It allows to remount an existing file system to tmpfs to preserve the microSD card by preventing any write operation to some targeted folders, like "/var"

## And others to come...

## <a name="getting-started"></a>Getting started

- clone the repo to your prefered location on the PI (/root is often a good location)
- follow the instructions related to each facility
