# wsl-translinux

This is an apt repository for packages specific to the Windows Subsystem for Linux.

## Usage

To use this repository, edit your `/etc/apt/sources.list` file to contain the following line:

`deb https://cerebrate.github.io/wsl-translinux/ xenial main`

After that, you can use apt-get to install packages from this repository as normal.

**Note: While this is still in the early stages, and until we've established proper procedures for vetting packages, this repository is not signed and as such will produce an "untrusted packages" warning. This is expected behavior, and we'll be as careful as possible not to allow any malware in here, but please take due care.**

## Package authors

If you would like to have your WSL-specific apt package included in this repository, just send us a pull request against the `gh-pages` branch with your .deb included in the incoming folder, and we'll get right on that.

Thanks!
