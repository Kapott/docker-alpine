<p align="center">
  <img src="Alpine_Linux.svg">
</p>

# Kapott's Alpine linux base image

I chose Alpine because I want my builds to be blazingly fast, lightweight and (reasonably) secure. 
Bloated images enough on docker hub, none of that for me! This image has the following preinstalled:

* curl
* wget
* bash

If you haven't heard about alpine, go check it out over at the [alpine linux website](https://alpinelinux.org)

## ABOUT ALPINE LINUX
Alpine Linux is an independent, non-commercial, general purpose Linux distribution designed for power users who appreciate security, simplicity and resource efficiency.

## SMALL
Alpine Linux is built around musl libc and busybox. This makes it smaller and more resource efficient than traditional GNU/Linux distributions. A container requires no more than 8 MB and a minimal installation to disk requires around 130 MB of storage. Not only do you get a fully-fledged Linux environment but a large selection of packages from the repository.

Binary packages are thinned out and split, giving you even more control over what you install, which in turn keeps your environment as small and efficient as possible.

## SIMPLE
Alpine Linux is a very simple distribution that will try to stay out of your way. It uses its own package manager called apk, the OpenRC init system, script driven set-ups and that’s it! This provides you with a simple, crystal-clear Linux environment without all the noise. You can then add on top of that just the packages you need for your project, so whether it’s building a home PVR, or an iSCSI storage controller, a wafer-thin mail server container, or a rock-solid embedded switch, nothing else will get in the way.

## SECURE
Alpine Linux was designed with security in mind. All userland binaries are compiled as Position Independent Executables (PIE) with stack smashing protection. These proactive security features prevent exploitation of entire classes of zero-day and other vulnerabilities.
