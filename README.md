# Ingenic Cloner

USB download tool for the Ingenic SoCs.

Official releases of the Ingenic USBCloner tool, mirrored from the vendor FTP
(`ftp://ftp.ingenic.com.cn/DevSupport/Tools/USBBurner/`) because the original
server is not reachable from everywhere.

## Downloads

| Version | Linux (ubuntu_alpha) | Windows (windows_alpha) |
| --- | --- | --- |
| 2.5.80.1 | `cloner-2.5.80.1-ubuntu_alpha.tar.gz` | `cloner-2.5.80.1-windows_alpha.zip` |
| 2.5.53   | `cloner-2.5.53-ubuntu_alpha.tar.gz`   | `cloner-2.5.53-windows_alpha.zip`   |
| 2.5.50   | `cloner-2.5.50-ubuntu_alpha.tar.gz`   | `cloner-2.5.50-windows_alpha.zip`   |
| 2.5.36.1 | `cloner-2.5.36.1-ubuntu_alpha.tar.gz` | `cloner-2.5.36.1-windows_alpha.zip` |

## Packaging

On Arch Linux the tool is available from the AUR:

- [`cloner-bin`](https://aur.archlinux.org/packages/cloner-bin)

## Running on Linux

Extract the archive and run `./cloner`. The tool talks to Ingenic SoC boards over
USB and needs access to the raw USB device; see the vendor quick guide included in
the archive for details.

No driver installation is required on Linux — only on Windows.

## License

These are prebuilt binaries redistributed by Ingenic Semiconductor. Upstream does not
release source code for the tool and states no license for it. The archives are
mirrored verbatim, without modification.
