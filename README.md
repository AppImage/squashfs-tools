# squashfs-tools

This is a fork from [plougher/squashfs-tools](https://github.com/plougher/squashfs-tools) since the upstream project seems to be stalled since quite some time.

It incorporates the following patches:
 * Add -offset option to skip n bytes [#13](https://github.com/plougher/squashfs-tools/pull/13)

## Notes

Git status:
* All Squashfs kernel development trees are stored on kernel.org, under [git.kernel.org:/linux/kernel/git/pkl/...](http://git.kernel.org/cgit/linux/kernel/git/pkl)
`kernel-2.4`: prehistoric, not updated since the 3.1 release.  If you still need Squashfs support in the 2.4 kernel then use the squashfs 3.1 release.  This is the last release that supported 2.4 kernels.
