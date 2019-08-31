# Description:

This is a simple docker file as I prefer to use zsh when working on servers. If docker is setup, you should be able to pull this image and run a simple command to run zsh in the current working directory.

# Usage:

docker run --rm -it -v $(pwd):/wd glitchm/zsh:latest zsh
