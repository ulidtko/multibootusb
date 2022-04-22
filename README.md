# History of this fork

The origin project is <https://mbusb.aguslr.com/> — the [repo][origin] is now archived.

[The fork over there][fork-1] claimed to provide Extended Support or whatever — but has
ignored [my doc-only PR](https://github.com/hackerncoder/multibootusb/pull/47) while merging
[the next one](https://github.com/hackerncoder/multibootusb/pull/50).

Having had to dig this out a few times, I got tired of rediscovering the forks every time
all over again. Not the most googleable name, y'know. Time for it to live in my space.

PRs welcome. Reviewed on volunteer basis.

## About

This is a collection of [GRUB][] scripts that allows to create a pendrive (USB dongle, flash stick)
capable of booting [a number of][isos] different OS images.

Basically, you run the `./makeUSB.sh` — then drop the liveCD/liveUSB ISO you have into a *subdir*,
*simply as a file* (no Rufus/`dd`/`usbcreator` or whatnot is required — simply copy the iso file),
and then can boot it:

![Demo GIF](docs/assets/img/demo.gif)

Both UEFI and Legacy PC BIOS boot modes are supported with `--hybrid --efi`.

## Documentation

Visit the [project's website for more information][website].

[grub]: https://www.gnu.org/software/grub/
[isos]: https://mbusb.aguslr.com/isos.html
[website]: https://mbusb.aguslr.com/
[origin]: https://github.com/aguslr/multibootusb
[fork-1]: https://github.co/hackerncoder/multibootusb
