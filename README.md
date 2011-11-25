     .
    -+- |\/| (  | | 
     |  |  |  ) |_|

Overview
--------

**tmsu** is an application that allows you to organise your files by associating
them with tags. It provides a tool for managing these tags and a virtual file-
system to allow tag based access to your files.

**tmsu**'s virtual file-system does not store your files: it merely provides an
alternative, tagged based view of your files stored elsewhere in the file-
system. That way you have the freedom to choose the most suitable file-system
for storage whilst still benefiting from benefits tag based access.

Compiling
---------

**tmsu** is written in Go (http://www.golang.org/). To compile from source you
must first install Go and the Go packages that tmsu depends upon.

1. Installing Go

Go can be installed per the instructions at <http://golang.org/doc/install.html>
or it may be available in the package management system that comes with your
operating system (if any).

**tmsu** is currently built against the Go weekly builds (see `VERSIONS`).

2. Install the dependent packages

    > goinstall gosqlite.googlecode.com/hg/sqlite
    > goinstall github.com/hanwen/go-fuse/fuse

3. Make the project

    > make

This will produce a bin directory containing the resultant binary.

- - -

Copyright 2011 Paul Ruane

Copying and distribution of this file, with or without modification,
are permitted in any medium without royalty provided the copyright
notice and this notice are preserved.  This file is offered as-is,
without any warranty.*