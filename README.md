# Crosstool-NG [![Build Status][travis-status]][travis]

Crosstool-NG follows the `autoconf` dance. So, to get you
kick-started, just run:

    ./configure --help

If you are using a development snapshot, you'll have to
create the configure script, first. Just run:

    ./bootstrap

You will find the documentation in the directory `docs`. After installation perform these additional step :

	cp -r overlays/ local-patches/ ${CT_NG_PATH}/lib/crosstool-ng-1.22.0-42-g1fbfd12

to provide the missing files to properly build the **xtensa-toolchain** which are not installed by default. After this given build has finished, install [lx106-hal](https://github.com/artynet/lx106-hal) as described in its README file to finish it up.

You will find the documentation in the directory `docs`.
Here is a quick overview of what you'll find there:

<ol start="0">
	<li>Table of content</li>
	<li>Introduction</li>
	<li>Installing crosstool-NG</li>
	<li>Configuring a toolchain</li>
	<li>Building the toolchain</li>
	<li>Using the toolchain</li>
	<li>Toolchain types</li>
	<li>Contributing</li>
	<li>Internals</li>
</ol>
<ol type="A">
	<li>Credits</li>
	<li>Known issues</li>
	<li>Misc. tutorials</li>
</ol>

You can also point your browser at: http://crosstool-ng.org

Aloha!

[travis-status]: https://travis-ci.org/crosstool-ng/crosstool-ng.svg
[travis]: https://travis-ci.org/crosstool-ng/crosstool-ng
