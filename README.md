This is a maintained version of the `mujoco-py`, for the porpuse of supporting modern `Cython` and `Python` versions, for use in [Gymnasium](https://gymnasium.farama.org/) and [Gymnasium-Robotics](https://robotics.farama.org/).

This is tested only in Linux, not MAC

No support will be provided

## diference from `openai/mujoco-py==2.1.2.14`
- if `cython.__version__ >= "3.0.0"` then compiler directives are set to `legacy_implicit_noexcept=True` 
- version is now `2.1.2.15`


### New users should depend on the [official MuJoCo Python bindings](https://github.com/deepmind/mujoco/blob/main/python/README.md).

# mujoco-py [![Documentation](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat)](https://openai.github.io/mujoco-py/build/html/index.html) [![Build Status](https://travis-ci.org/openai/mujoco-py.svg?branch=master)](https://travis-ci.org/openai/mujoco-py)


# Dev Notes

must be built with `gcc-9` to retain the bugs for reproducability of results