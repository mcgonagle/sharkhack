# mcgonagle/102

[![Docker Automated Build](https://img.shields.io/docker/automated/mcgonagle/102.svg?style=flat-square)](https://hub.docker.com/r/mcgonagle/102/) [![Apache-2.0 License](https://img.shields.io/github/license/mcgonagle/102.svg?style=flat-square)](https://github.com/mcgonagle/102/blob/master/LICENSE) [![Docker Build Status](https://img.shields.io/docker/build/mcgonagle/102.svg?style=flat-square)](https://hub.docker.com/r/mcgonagle/102/builds/)

This is a basic Docker image for building and previewing [Hovercraft](https://github.com/regebro/hovercraft) 102 presentations. The image is available for public use on Docker Hub at [mcgonagle/102](https://hub.docker.com/r/mcgonagle/102/).

## Usage

To Build:
``` bash
docker build --tag=mcgonagle/102 .
```

To Run:
``` bash
docker run -it --rm -p "9000:9000" -v mcgonagle/102
```

In a web browser, go to <http://localhost:9000> to view your presentation.


