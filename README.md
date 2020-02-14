## ifm3d-release (kinetic) - 0.17.0-6

The packages in the `ifm3d-release` repository were released into the `kinetic` distro by running `/usr/bin/bloom-release --rosdistro kinetic --track kinetic ifm3d-release` on `Fri, 14 Feb 2020 19:29:33 -0000`

The `ifm3d-core` package was released.

Version of package(s) in repository `ifm3d-release`:

- upstream repository: https://github.com/ifm/ifm3d
- release repository: unknown
- rosdistro version: `null`
- old version: `0.17.0-5`
- new version: `0.17.0-6`

Versions of tools used:

- bloom version: `0.9.1`
- catkin_pkg version: `0.4.16`
- rosdep version: `0.18.0`
- rosdistro version: `0.8.0`
- vcstools version: `0.1.42`


## ifm3d-release (kinetic) - 0.17.0-5

The packages in the `ifm3d-release` repository were released into the `kinetic` distro by running `/usr/bin/bloom-release --rosdistro kinetic --track kinetic ifm3d-release` on `Fri, 14 Feb 2020 19:27:38 -0000`

The `ifm3d-core` package was released.

Version of package(s) in repository `ifm3d-release`:

- upstream repository: https://github.com/ifm/ifm3d
- release repository: unknown
- rosdistro version: `null`
- old version: `0.17.0-4`
- new version: `0.17.0-5`

Versions of tools used:

- bloom version: `0.9.1`
- catkin_pkg version: `0.4.16`
- rosdep version: `0.18.0`
- rosdistro version: `0.8.0`
- vcstools version: `0.1.42`


# ifm3d-release
ROS Bloom release repo for ifm3d

# Building the debs locally

```
$ git clone https://github.com/ifm/ifm3d-release.git
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
