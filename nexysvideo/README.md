OpenTitan Nexysvideo FPGA
=========================

The OpenTitan image built for the Nexysvideo FPGA board was supported
in Tock since [PR #1460][pr1460].
The last release with support for the Nexysvideo board was Tock 2.0.

The upstream OpenTitan project deprecated the Nexysvideo FPGA, so
Tock is doing the same (see [PR #3025][pr3025]). Tock still supports OpenTitan on other
FPGA platforms such as the CW310.

If OpenTitan resurrects support for the nexysvideo platform,
we are happy to bring it back into mainline Tock.

The last supported Tock mainline git revision is
[`c91772920d`](https://github.com/tock/tock/commit/c91772920d090f7eea1ecd4f1f5ff212ce4c0429).

Usage
-----

Using this archived version should work very similar to mainline Tock. With
`rustup` installed:

```
$ cd boards/nexysvideo
$ make
```

[pr3025]: https://github.com/tock/tock/pull/3025
[pr1460]: https://github.com/tock/tock/pull/1460
