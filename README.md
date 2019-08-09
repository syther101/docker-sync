[![Gem Version](https://badge.fury.io/rb/docker-sync.svg)](https://badge.fury.io/rb/docker-sync) [![Build Status](https://travis-ci.org/EugenMayer/docker-sync.svg?branch=master)](https://travis-ci.org/EugenMayer/docker-sync) [![Join the chat at https://gitter.im/EugenMayer/docker-sync](https://badges.gitter.im/EugenMayer/docker-sync.svg)](https://gitter.im/EugenMayer/docker-sync)

# Run docker apps at full speed on macOS, Windows or Linux* 
Utilising Docker on macOS or Windows within your local development enviroment isn't like the old days of running everything locally. Docker makes your enviroment portable. But why is code-execution so slow? 🐢

With `docker-sync` you can experince native-like file sync speeds when utilising Docker in your local devlopment enviroment. Allowing your applications to run at full speed on macOS or Windows 🚀

## Documentation
📝[https://docker-sync.readthedocs.io](https://docker-sync.readthedocs.io)

## But why is Docker slow?
The problem is incompatability. Docker is built on Linux, this is great for many reasons and when running Docker on Linux, your development files can be synced between your containers and local filesystem natively. Things are always fast!

But unfortunately both macOS and Windows don't provide a native Linux kernel for Docker to run on. So Docker will run your containers inside a small Linux virtual machine. For Docker to keep your code / files in sync with the containers inside, tooling is required to sync file changes between your local filesystem (macOS/Windows) and the Docker virtual machine (Linux).

The overhead caused by syncing file changes can cause Docker to become incredible slow when executing code under certian workloads. This is not a trivial issue to fix and slow sync speeds continue to plague Vagrant and Virtualbox just the same.

## How to Contribute
    Thank you for all the feedback and support i already received!
    Docker-sync has been improved by all of you in huge ways!
Wheather you can help us fix bugs, improve documentation or work on new features, if you are eager to help and improve docker-sync we'd love to have you as part of the community!

You can check out our [Contributing Guide]()
 - If you're a coder you can find issues that need help [here](https://github.com/EugenMayer/docker-sync/issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22)
 - Want to help imrpove the docs? We'd love your help, no matter what skill set you have. You can find issues with Documentation [here](https://github.com/EugenMayer/docker-sync/issues?utf8=%E2%9C%93&q=is%3Aissue%20is%3Aopen%20label%3A%22help%20wanted%22%20%20label%3A%22documentation%22%20)

### Support docker-sync
`docker-sync` is an independent and community-driven. Ongoing development is made possible by the support of our awesome backers. Use `docker-sync` in your dev enviroment? If you can pledge a little, or even a lot, please consider supporting the project on patreon. Everything goes a little way towards keeping the project maintained.

- [Become a sponsor on Patreon](https://www.patreon.com/eugenmayer/overview)

## Contributors
A massive thanks to our contributors and Sponsors

### Main Contributors
 - [ignatiusreza](https://github.com/ignatiusreza)
 - [michaelbaudino](https://github.com/michaelbaudino)
 - [mickaelperrin](https://github.com/mickaelperrin)
 - [masterful](https://github.com/masterful)
 - [rwilliams](https://github.com/rwilliams)

[1.1]: http://i.imgur.com/tXSoThF.png
[1]: http://www.twitter.com/dockersync
