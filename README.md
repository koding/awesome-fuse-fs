# Awesome FUSE Filesystem

This is a list of resources related to FUSE
(https://en.wikipedia.org/wiki/Filesystem_in_Userspace), Filesystem in
Userspace. (This is different from https://github.com/vinkla/awesome-fuse). If
I've missed any, which I'm sure I've, pleae open a PR.

## Table of Contents

* [Libraries](#libraries)
* [Built On](#built-on)
* [Posts](#posts)
* [Videos](#videos)
* [Mailing Lists](#mailing-lists)

## Libraries

* [osxfuse](https://osxfuse.github.io) - For OSX
* [libfuse](https://github.com/libfuse/libfuse) - Reference implementation for
  Linux FUSE.
* [Dokan](https://dokan-dev.github.io) - For Windows; has a [FUSE
  wrapper](https://github.com/dokan-dev/dokany/wiki/FUSE).

## Built On

* [sshfs](https://github.com/osxfuse/sshfs) - File system based on the SSH File
  Transfer Protocol; same authors as (osxfuse)[https://github.com/osxfuse].
Language: C.
* [sshfs](https://github.com/libfuse/sshfs) - A network filesystem client to
  connect to SSH servers; same authors as (libfuse)[https://github.com/libfuse].
Language: C.
* [gocryptfs](https://github.com/rfjakob/gocryptfs) - Encrypted overlay
  filesystem written in Go. Language: Golang;
* [mp3fs](https://github.com/khenriks/mp3fs) - FUSE-based transcoding filesystem
  from FLAC to MP3. Language: C++.
* [google-drive-ocamlfuse](https://github.com/astrada/google-drive-ocamlfuse) -
  FUSE filesystem over Google Drive; Language: OCaml.

## Posts

* [Writing a FUSE filesystem in
  Python](https://www.stavros.io/posts/python-fuse-filesystem/)

## Slides

* [Writing a file system in
  Go](https://bazil.org/talks/2013-06-10-la-gophers/#1)

## Mailing Lists

* [fuse-devel](https://sourceforge.net/p/fuse/mailman/fuse-devel)

## Videos

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
