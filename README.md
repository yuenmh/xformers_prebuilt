# `xformers 0.0.14.dev0`

For some reason they've deleted this release, which also happens to be the only one that works with [sd-scripts](https://github.com/kohya-ss/sd-scripts) to my knowledge.

Built from commit [1d31a3a](https://github.com/facebookresearch/xformers/tree/1d31a3a), which is the commit where they changed the version number to `0.0.14`.

```bash
$ git clone https://github.com/facebookresearch/xformers.git
$ cd xformers
$ git checkout 1d31a3a
$ sudo apt install nvidia-cuda-toolkit  # install nvcc
$ pip install -r requirements.txt
$ pip wheel -e .  # this takes like an hour
```
