[![Gem Version](https://badge.fury.io/rb/docker-sync.svg)](https://badge.fury.io/rb/docker-sync) [![Build Status](https://travis-ci.org/EugenMayer/docker-sync.svg?branch=master)](https://travis-ci.org/EugenMayer/docker-sync) [![Join the chat at https://gitter.im/EugenMayer/docker-sync](https://badges.gitter.im/EugenMayer/docker-sync.svg)](https://gitter.im/EugenMayer/docker-sync)

# Run docker apps at full speed on macOS, Windows or Linux* 
Utilising Docker on macOS or Windows within your local development enviroment isn't like the old days of running everything locally. Docker makes your enviroment portable. But why is code-execution so slow? 🐢

With `docker-sync` you can experince native-like file sync speeds when utilising Docker in your local devlopment enviroment. Allowing your applications to run at full speed on macOS or Windows 🚀

## But why is Docker slow?
The problem is incompatability. Docker is built on Linux, this is great for many reasons and when running Docker on Linux, your development files can be synced between your containers and local filesystem natively. Things are always fast!

But unfortunately both macOS and Windows don't provide a native Linux kernel for Docker to run on. So Docker will run all your containers inside a small Linux virtual machine. For Docker to keep your code / files in sync with the containers inside, tooling is required to sync file changes between your local filesystem (macOS/Windows) and the Docker virtual machine (Linux).

Under certian workloads Docker can become incredible slow when syncing file changes. This is not a trivial issue to fix and slow sync speeds continue to plague Vagrant and Virtualbox just the same.

## Supporting docker-sync

    Thank you for all the feedback and support i already received!
    Docker-sync has been improved by all of you in huge ways!

If you are eager to help and improve docker-sync
 - Help [here](https://github.com/EugenMayer/docker-sync/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) if you are a coder
 - Help [here](https://github.com/EugenMayer/docker-sync/issues?utf8=%E2%9C%93&q=is%3Aissue%20is%3Aopen%20label%3A%22help%20wanted%22%20%20label%3A%22documentation%22%20) with the docs no matter what skill set you have


Anything else under [http://docker-sync.io](http://docker-sync.io) or the [documentation](https://docker-sync.readthedocs.io/en/latest/index.html#)

Main Contributors:
 - [ignatiusreza](https://github.com/ignatiusreza)
 - [michaelbaudino](https://github.com/michaelbaudino)
 - [mickaelperrin](https://github.com/mickaelperrin)
 - [masterful](https://github.com/masterful)
 - [rwilliams](https://github.com/rwilliams)

[1.1]: http://i.imgur.com/tXSoThF.png
[1]: http://www.twitter.com/dockersync
