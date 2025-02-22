# README

Repository of Dockerfiles to build container images based on [Rocker](https://rocker-project.org) $\texttt{R base}$ and $\texttt{RStudio Server}$ images.

The name of the file indicates the general purpose of the build and the version of $\texttt{R}$ it is based on (e.g. name_0.0.0).

## Usage

Move the file of interest to a destination directory and rename it "`Dockerfile`".
Then set this as the working directory in a Terminal and build the image as usual.

### Example

```bash
$ cp /path/to/dockerfiles/dir/dockerfile /path/to/destination/dir/Dockerfile
$ cd /path/to/destination/dir/
$ docker build -t imagename:imagetag .
```