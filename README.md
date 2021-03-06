# OSX-ISO

> Create a bootable ISO of OS X / macOS, from the installation app file.

## Prerequisites

The appropriate installation file(s) must be located in `/Applications` i.e.

```
/Applications/Install macOS High Sierra.app
/Applications/Install macOS Sierra.app
/Applications/Install OS X El Capitan.app
/Applications/Install OS X Yosemite.app
/Applications/Install OS X Mavericks.app
```

Mac users can download theses files from the App Store.

## Install with [bpkg](https://github.com/bpkg/bpkg)

```sh
$ bpkg install busterc/osx-iso
```

## Usage

```sh
$ osxiso <"High Sierra"|Sierra|"El Capitan"|Yosemite|Mavericks>
```

## License

ISC License (ISC)

Copyright &copy; 2015-2017, Buster Collings

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
