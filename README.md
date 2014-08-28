# Eclipsify
Create eclipse projects from catkin projects. This is a very simple template-based generator. Currently it works for OSX.

```
usage: eclipsify [-h] [-w WORKSPACE] package

This utility creates a new eclipse project. It assumes the package is
in a workspace with the default names for the devel/build/src spaces.
If your workspace is different, try eclipsify-gen-project.

The project files will go to devel/share/project-name/eclipse

positional arguments:
  package       The name of the catkin package to be eclipsified.

optional arguments:
  -h, --help    show this help message and exit
  -w WORKSPACE  The full path of the eclipse workspace that this package
                should be added to.
```
