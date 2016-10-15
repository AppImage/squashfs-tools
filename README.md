# squashhfs-tools

This is a fork from [plougher/squashfs-tools](https://github.com/plougher/squashfs-tools) since the upstream project seems to be stalled since quite some time.

It incorporates the following patches:
 * Add -offset option to skip n bytes [#13](https://github.com/plougher/squashfs-tools/pull/13)

## Original README

Git status:

This is the squashfs.sourceforge.net CVS repository imported into this
new git repository.  All new development will be under git.

Squashfs-tools: The new Squashfs 4.3 release (2014/05/05).

kernel: obsolete, the kernel code is now in mainline at www.kernel.org.

All Squashfs kernel development trees are stored on kernel.org,
under git.kernel.org:/linux/kernel/git/pkl/...

kernel-2.4: prehistoric, not updated since the 3.1 release.  If you still need
Squashfs support in the 2.4 kernel then use the squashfs 3.1 release.  This
is the last release that supported 2.4 kernels.

The kernel and kernel-2.4 directories (imported from CVS) are not really
relevant anymore, but are here temporarily while I decide where to put
them (I don't want to delete them and have all the pre-mainlining
kernel commit history disappear from public repositories).

