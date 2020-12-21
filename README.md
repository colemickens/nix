[![Open Collective supporters](https://opencollective.com/nixos/tiers/supporter/badge.svg?label=Supporters&color=brightgreen)](https://opencollective.com/nixos)

Nix, the purely functional package manager
------------------------------------------

Nix is a new take on package management that is fairly unique. Because of its
purity aspects, a lot of issues found in traditional package managers don't
appear with Nix.

To find out more about the tool, usage and installation instructions, please
read the manual, which is available on the Nix website at
<http://nixos.org/nix/manual>.

## Windows Notes

These steps can be carried out in the free VM Developer image that Microsoft offers.
To get started:

1. Install MSYS2.
2. Open a MSYS Mingw632 64bit window.
3. Run `pacman -Syu`.
4. Run `pacman -S `.
5. Clone `https://github.com/nix-windows/nix`.
6. `./bootstrap-meson.sh` will build it.

Then you can move that to .... and then use the scripts to hack:
...

## Contributing

Take a look at the [Hacking Section](http://nixos.org/nix/manual/#chap-hacking)
of the manual. It helps you to get started with building Nix from source.

## License

Nix is released under the LGPL v2.1

This product includes software developed by the OpenSSL Project for
use in the [OpenSSL Toolkit](http://www.OpenSSL.org/).
