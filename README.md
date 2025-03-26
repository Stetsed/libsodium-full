# LibSodium-Full

This is a random form of libsodium-esphome, but changed to add all componentns of libsodium. I needed it for a project for school and it was the easiest way to just clone it and remove the exceptions. This library is not activley maintained so use at your own risk, as libsodium won't be updated unless I am working with it at the time.

Major thanks for the esphome team for providing the package I could base it off

<details>

  <summary> Original README</summary>

# libsodium-esphome

This is a port of [libsodium](https://github.com/jedisct1/libsodium) - A modern, portable, easy to use crypto library.

We use libsodium 1.0.18 as the base (see libsodium submodule) with some simple patches in port/port_include to make the library compile with the [platformio](https://platformio.org/) build system.

Only a subset of libsodium is compiled, namely the cryptographic primitives required for [noise-c](https://github.com/esphome/noise-c/).

libsodium is licensed under the [ISC License](https://github.com/jedisct1/libsodium#license)

</details>
