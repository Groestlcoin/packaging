Groestlcoin Core packaging
=======

Groestlcoin Core is packaged and distributed through different channels.

Advanced users can compile Groestlcoin Core from source. Static binaries for Linux, as well as installers for Windows and macOS are
provided on the [website](https://groestlcoin.org).

Groestlcoin Core is also distributed on several Linux package managers:

* The `groestlcoin-core` snap package for https://snapcraft.io/groestlcoin-core is maintained in [/snap](/snap)
* The `org.groestlcoin.groestlcoin-qt` flatpak package is maintained under their organization: https://github.com/flathub/org.groestlcoin.groestlcoin-qt
* The `groestlcoin` PPA launchpad package for https://launchpad.net/~groestlcoin/+archive/ubuntu/groestlcoin is maintained in [/debian](/debian)
* The `org.groestlcoin.groestlcoin-qt` flatpak package is maintained under their organization: https://github.com/flathub/org.groestlcoin.groestlcoin-qt
* The `groestlcoin` nixos package is maintained under their organization: https://github.com/NixOS/nixpkgs/tree/master/pkgs/applications/blockchains/groestlcoin
* The `groestlcoin-core` homebrew cask package is maintained under their organization: https://github.com/Homebrew/homebrew-cask/blob/master/Casks/groestlcoin-core.rb
* The `groestlcoin` homebrew package is maintained under their organization: https://github.com/Homebrew/homebrew-core/blob/master/Formula/groestlcoin.rb
* The `groestlcoin` arch linux repository package for https://aur.archlinux.org/pkgbase/groestlcoin is maintained under: https://github.com/Groestlcoin/arch-groestlcoin

An RPM spec file was removed in commit fa7c698cb24bab350b40ee2d825c443dabdd9633, because is was unmaintained and
outdated.
