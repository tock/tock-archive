LaunchXL and CC26x2
===================

The LaunchXL and underling CC26x2 was supported in Tock since [PR #747][pr747].
The last release with LaunchXL and CC26x2 was Tock 1.5.

While basic functionality was supported, this platform never gained much traction
or developer support. As the board was beginnging to become difficult for the core
team to test and maintenance slowed, it was removed from mainline Tock.

If future developers are interested in resurrecting **and providing a plan for
continuing support** for the LaunchXL, we are happy to bring it back into
mainline Tock.


Usage
-----

Using this archived version should work very similar to mainline Tock. With
`rustup` installed:

```
$ cd boards/launchxl
$ make
$ make flash   # Load the kernel on the board.
```

[pr747]: https://github.com/tock/tock/pull/747
