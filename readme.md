# Intro

## Global Dependencies

This is a repository to aglutinate all Lust Engine submodules. At the end of this document, it will be listed all necessary software to install the dependencies.

- [Visual Studio](https://visualstudio.microsoft.com/)
- [CMake](https://cmake.org/)
- [Ninja](https://ninja-build.org/)
- [Python](https://www.python.org/)
  - [Meson](https://mesonbuild.com/)
- [Git](https://git-scm.com/) - Ok, I know you use git, but what is over isn't under

and python need the following packages: `jsonschema`, that can be installed with:
``` pip3 install jsonschema ```

## Linux Dependencies

For linux distros we use:

- [Clang and LLVM](https://llvm.org/)

For [Vulkan](https://www.vulkan.org/), you must install the following dependencies: `git @development-tools glm-devel \
                 libpng-devel wayland-devel libpciaccess-devel \
                 libX11-devel libXpresent libxcb xcb-util libxcb-devel libXrandr-devel \
                 xcb-util-keysyms-devel xcb-util-wm-devel`
