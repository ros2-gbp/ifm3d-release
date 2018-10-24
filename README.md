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

After a successful build the Debian deb file can be installed
```
# Assuming we are still in the ifm3d-release folder
$ sudo dpkg -i ../ros-kinetic-ifm3d-core_0.11.0-0xenial_amd64.deb
```
