# Instructions

These MATLAB libraries are organized into a set of numerous submodules, grouped into subdirectories.  Each submodule is by itself another git repository, tracked by this project.

To clone the repository with all submodules, use the following command:
```
git clone --recurse-submodules -j8 git://github.com/gaudetteje/matlibs.git
```

On older versions of git, use:
```
git clone git://github.com/gaudetteje/matlibs.git
cd matlibs
git submodule init
git submodule update
```

To update submodules with the latest code:
```
git submodule init
git submodule update

```
