# Qt5.1.1-ToolChain

Qt5.1.1-ToolChain is the main repository for a Qt5.1.1 SDK to allow for cross-compilation between Host PC and Raspberry Pi 3B+. This repository contains five submodules. Each submodule corresponds to a Yocto layer and is added as a subdirectory to the directory _qt5.1.1-toolchain/sources_. Qt5.1.1-ToolChain is currently based on the Yocto release _dora_.

We must install Docker before we can run the Yocto build. Docker installation is described [here](https://www.embeddeduse.com/2019/02/11/using-docker-containers-for-yocto-builds/#install). We execute the Yocto build in the [Docker container CROPS](https://hub.docker.com/u/crops/) as described in the blog post [Yocto Builds with CROPS Containers](https://www.embeddeduse.com/2019/05/06/yocto-builds-with-crops-containers/).
