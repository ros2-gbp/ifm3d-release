# ifm3d-release
ROS Bloom release repo for ifm3d

# Building the debs locally

```
$ git clone https://github.com/graugans/ifm3d-release.git
$ cd ifm3d-release
$ git checkout debian/kinetic/xenial/ifm3d-core
$ bloom-generate rosdebian --ros-distro kinetic
$ fakeroot debian/rules binary
```
