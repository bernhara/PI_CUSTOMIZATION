# RaspberryPI Linux distribution customization helper

This project collects some scripts and specific adjustements the helps me to customize an "out of the box" Raspberry distro.
My goal is to have everything working independly from the distribution, but I cannot ensure that that this is really true.

The main features are the following.

### Preserving the microSD card with the "mount_to_tmpfs_overlay" fuse mount facility

See bin/mount_to_tmpfs_overlay

It allows to remount an existing file system to tmpfs to preserve the microSD card by preventing any write operation to some targeted folders, like "/var"

### others to come...

## <a name="getting-started"></a>Getting started

- toto
- titi

```
sudo curl -L git.io/scope -o /usr/local/bin/scope
sudo chmod a+x /usr/local/bin/scope
scope launch
```

This script downloads and runs a recent Scope image from Docker Hub.
Now, open your web browser to **http://localhost:4040**. (If you're using
boot2docker, replace localhost with the output of `boot2docker ip`.)

For instructions on installing Scope on [Kubernetes](https://www.weave.works/docs/scope/latest/installing/#k8s), [DCOS](https://www.weave.works/docs/scope/latest/installing/#dcos) or [ECS](https://www.weave.works/docs/scope/latest/installing/#ecs), see [the docs](https://www.weave.works/docs/scope/latest/introducing/).

## <a name="help"></a>Getting help

If you have any questions about, feedback for or problems with Scope:


