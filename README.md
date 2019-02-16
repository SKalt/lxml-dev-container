# lxml-dev-container
(WIP) a container for developing [lxml](https://github.com/lxml/lxml)

Though this image is based off the python-3.7 portion of lxml's travis.yml, this image is entirely unoffial.

## Anticipated Usage:

```sh
# within your cloned version of the lxml repo
docker run -itv $(git rev-parse --show-toplevel):/workspace skalt/lxml-dev-env # defaults to bash
```
