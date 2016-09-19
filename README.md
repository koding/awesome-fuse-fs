# Awesome FUSE Filesystem

This is a list of resources related to [FUSE]
(https://en.wikipedia.org/wiki/Filesystem_in_Userspace), Filesystem in
Userspace. (This is different from https://github.com/vinkla/awesome-fuse). This
is a Golang heavy list, please help me add other languages to it by opening a PR
today!

## Table of Contents

* [Libraries](#libraries)
* [Built On](#built-on)
* [Posts](#posts)
* [Misc](#misc)

## Libraries

* [osxfuse](https://osxfuse.github.io) - For OSX. Language: C.
* [libfuse](https://github.com/libfuse/libfuse) - Reference implementation for
  Linux FUSE. Language: C.
* [Dokan](https://dokan-dev.github.io) - For Windows; has a [FUSE
  wrapper](https://github.com/dokan-dev/dokany/wiki/FUSE).
* [jacobsa/fuse](https://github.com/jacobsa/fuse) - A Go package for
  implementing a FUSE file system. Language: Golang.
* [bazil/fuse](https://github.com/bazil/fuse) - FUSE library for Go. Language:
  Golang.
* [go-fuse](https://github.com/hanwen/go-fuse) - FUSE bindings for Go. Language:
  Golang.
* [ruse-fuse](https://github.com/zargony/rust-fuse) - Rust library for
  filesystems in userspace (FUSE). Language: Rust.
* [rfusefs](https://github.com/lwoggardner/rfusefs) - Ruby FUSE filesystem -
  write filesystems in Ruby (FuseFS API over rfuse). Language: Ruby.
* [fuse4js](https://github.com/bcle/fuse4js) - FUSE bindings for Javascript and
  node.js (possibly outdated). Language: Javascript.
* [fuse-google-drive](https://github.com/jcline/fuse-google-drive) - A fuse
 http://loggedfs.sourceforge.net filesystem wrapper for Google Drive.

## Built On

* [gcsfuse](https://github.com/GoogleCloudPlatform/gcsfuse) - A user-space file
  system for interacting with Google Cloud Storage. Language: Golang.
* [sshfs](https://github.com/osxfuse/sshfs) - File system based on the SSH File
  Transfer Protocol; same authors as [osxfuse](https://github.com/osxfuse).
Language: C.
* [sshfs](https://github.com/libfuse/sshfs) - A network filesystem client to
  connect to SSH servers; same authors as [libfuse](https://github.com/libfuse).
Language: C.
* [go-ipfs](https://github.com/ipfs/go-ipfs) - IPFS implementation in go.
  Language: Golang.
* [mirrorfs](https://github.com/elgutierrez/mirrorfs) - Go filesystem project
  using bazil/fuse. Language: Golang.
* [gocryptfs](https://github.com/rfjakob/gocryptfs) - Encrypted overlay
  filesystem written in Go. Language: Golang.
* [tahoe-lafs](https://github.com/tahoe-lafs/tahoe-lafs) - The Tahoe-LAFS
  decentralized secure filesystem. Language: Python.
* [btfs](https://github.com/johang/btfs) - A bittorrent filesystem based on
  FUSE. Language: C++;
* [google-drive-ocamlfuse](https://github.com/astrada/google-drive-ocamlfuse) -
  FUSE filesystem over Google Drive. Language: OCaml.
* [mp3fs](https://github.com/khenriks/mp3fs) - FUSE-based transcoding filesystem
  from FLAC to MP3. Language: C++.
* [encfs](https://github.com/vgough/encfs) - An Encrypted Filesystem for FUSE.
  Language: C++;
* [GDriveFS](https://github.com/dsoprea/GDriveFS) - An innovative FUSE wrapper
  for Google Drive; Language: Python.
* [pachyderm](https://github.com/pachyderm/pachyderm) - Containerized Data
  Analytics. Language: Golang.
* [camlistore](https://github.com/camlistore/camlistore) - Personal storage
  system for life: a way of storing, syncing, sharing, modelling and backing up
content. Language: Golang.
* [svfs](https://github.com/ovh/svfs) - The Swift Virtual File System. Language:
  Golang.
* [restic](https://github.com/restic/restic) - restic backup program. Language:
  Golang.
* [unionfs-fuse](https://github.com/rpodgorny/unionfs-fuse) - union filesystem
  using fuse. Language: C.
* [GlusterFS](https://github.com/gluster/glusterfs) -  Storage for your Cloud.
  Language: C.
* [LoggedFS](http://loggedfs.sourceforge.net/) - Filesystem monitoring with
  Fuse. Language: C++.
* [go-mtpfs](https://github.com/hanwen/go-mtpfs) - Mount MTP devices over FUSE.
  Language: Go.

## Posts

* [Writing a FUSE filesystem in
  Python](https://www.stavros.io/posts/python-fuse-filesystem)
* [Writing a file system in
  Go](https://bazil.org/talks/2013-06-10-la-gophers/#1)
* [Write a filesystem with
  FUSE](http://engineering.facile.it/blog/eng/write-filesystem-fuse)
* [Develop your own filesystem with
  FUSE](http://www.ibm.com/developerworks/linux/library/l-fuse/)
* [FUSE filesystems, part
  1](http://zsiciarz.github.io/24daysofrust/book/day15.html)
* [Fuse- Filesystem in User
  space](http://www.slideshare.net/danny00076/fuse-filesystem-in-user-space)
Slides with lot of implementation details.
* [Building File Systems with
  FUSE](http://www.slideshare.net/adorepump/building-file-systems-with-fuse) -
Slides with high level explanation.
* [FUSE and SSHFS on OS
  X](http://stuff-things.net/2015/05/20/fuse-and-sshfs-on-os-x) Small tutorial
on installing and running sshfs on OSX.
* [Python Fuse](http://www.slideshare.net/matteobertozzi/python-fuse)
* [Writing a FUSE Filesystem: a
  Tutorial](http://www.cs.nmsu.edu/~pfeiffer/fuse-tutorial/html/index.html)

## Misc

* [fuse-devel](https://sourceforge.net/p/fuse/mailman/fuse-devel) - Development
  mailing list.
* [Filesystem in
  Userspace](https://en.wikipedia.org/wiki/Filesystem_in_Userspace) - Wikipedia
page; has more list of examples.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
