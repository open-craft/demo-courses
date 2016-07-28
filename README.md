# OpenCraft Demo Courses

![OpenCraft Logo](opencraft-logo.png)

This repository contains demo courses for many of the XBlocks that OpenCraft maintains or has
helped to develop.

* [Problem Builder](https://github.com/open-craft/problem-builder): [**problem-builder.tar.gz**](https://github.com/open-craft/demo-courses/archive/problem-builder.tar.gz) (Recommended ID: Organization "OpenCraft", Number "PB", Run "demos")
* [Drag and Drop XBlock](https://github.com/edx-solutions/xblock-drag-and-drop-v2): [**drag-and-drop-v2.tar.gz**](https://github.com/open-craft/demo-courses/archive/drag-and-drop-v2.tar.gz) (Recommended ID: Organization "OpenCraft", Number "DnDv2", Run "demos")
* [XBlock-Poll](https://github.com/open-craft/xblock-poll): [**poll.tar.gz**](https://github.com/open-craft/demo-courses/archive/poll.tar.gz) (Recommended ID: Organization "OpenCraft", Number "poll", Run "demos")
* [Grammarian XBlock](https://github.com/open-craft/xblock-grammarian): [**grammarian.tar.gz**](https://github.com/open-craft/demo-courses/archive/grammarian.tar.gz)


### How to add a new course to this repository

1. Type `git checkout --orphan xblock-name` to create a new "orphan" branch.
1. Delete any files that remain present/staged.
1. Export the course from Studio.
1. Extract the contents of the resulting tarball into this repository.
1. Ensure that the course is not in a subfolder. `course.xml` should be in the
   root of the repository.
