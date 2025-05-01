<!-- filepath: c:\Users\tadeo\OneDrive\Documents\GitHub\TS-NETWORK\SECTIONS\TS-KENREL NEWS\NEWS\NEWS 4-30-2025 2\TS-KERNEL-LT-README.md -->
# The TS-NETWORK News

## The TS-KERNEL News

April 30th, 2025, 7:41 PM UTC -5:00 (Dateline)

TS-KERNEL LT For Debian, Ubuntu and Debian-Based Linux Distros (Headline)

TS-KERNEL LT 1.0.0 is now available as a .deb package for Debian, Ubuntu, and their derivatives. [Get the release here!](https://github.com/Coolis1362/TS-KERNEL-LT) (Drophead)

By Coolis1362 (or other authorized contributors) (Byline)

TS-KERNEL LT (Linux Technology) brings the core functionality of TS-KERNEL, originally for Windows, to Linux systems. It is designed to help you build and manage TS-DISTRO distributions on Linux. (Lead)

## Features

- Core TS-KERNEL boot and user management scripts
- TS-KERNEL Language support
- User and admin configuration
- Bootloader and shutdown utilities
- Ready for extension and custom Linux distributions

## Project Structure

```
1.x.x/
  1.0.x/
    1.0.0/
      BTS/
        my-package/
          DEBIAN/
            control         # Package metadata
            postinst        # Post-install script
            postrm          # Post-remove script
          usr/
            bin/
              root/
                boot/
                  shutdown_windows.py
                  ts-distro-distro_name.py
                  bootloader/
                  python/
                  ts_kernel_language/
                ts-desktop/
                users/
```

See `filesystem for ts-kernel 1.0.1a2.txt` for a detailed breakdown.

## Installation

1. Make sure you have Python 3 installed.
2. Install the `.deb` package:
   ```sh
   sudo dpkg -i ts-kernel-lt_1.0.0_amd64.deb
   ```
3. After installation, you’ll see:
   ```
   TS-KERNEL Linux Technology Has Been Installed, Have fun Making TS-DISTRO Distros On Linux!
   ```

## Removal

To uninstall:
```sh
sudo dpkg --remove ts-kernel-lt
```

## Maintainer

- Coolis1362

## Notes

- `.rpm` packages will be released later.
- For more details, see the scripts and configuration files in the `BTS/my-package` directory.

## Links

- [TS-KERNEL LT on GitHub](https://github.com/Coolis1362/TS-KERNEL-LT)
- [Releases](https://github.com/Coolis1362/TS-KERNEL-LT/releases)
- [Issues](https://github.com/Coolis1362/TS-KERNEL-LT/issues)

WARNING: THIS HAVES BUGS, SO COPY AND PASTE THE `BTS\\my-package\\usr\\bin\\root` FOLDER AND YOU CAN MAKE YOUR OWN TS-DISTRO DISTRO!

OTHER WARNING: THIS IS ONLY FOR DEBIAN, DEBIAN-BASED, UBUNTU OR UBUNTU-BASED AMD64 SYSTEMS!
