# Imagr

Imagr is an application designed to be run from a NetInstall environment created with [AutoNBI](https://bitbucket.org/bruienne/autonbi/src). It is able replace tools such as DeployStudio for many organisations without the requirement of needing to be run on OS X servers.

This is a Python application, so Python will need to be included in your NetInstall.

This is pre-release code and under heavy development. There are bugs if you don't follow the magic path. Bug reports are welcomed, pull requests are even better.

Development Mailing List: [imagr-dev](https://groups.google.com/group/imagr-dev)

Support Mailing List: [imagr-discuss](https://groups.google.com/group/imagr-discuss)

## Getting Started

The best place to get started with Imagr is the [Getting Started](https://github.com/grahamgilbert/imagr/wiki/Getting-Started) page on the wiki.

## Features

* Restore ASR Images (such as those created with AutoDMG)
* Install packages during Imagr run and at first boot
* Run scripts during Imagr run and at first boot
* Include other workflows in your workflow, specified statically or using a script
* Erase and partition disks
* Rename the machine
* Protect your users from accidentally wiping their devices by specifying a password for Imagr
