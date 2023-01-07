# NV-VGPU-Driver-KVM
This repository contains history versions of NVIDIA vGPU drivers.

![GitHub repo size](https://img.shields.io/github/repo-size/justin-himself/NV-VGPU-History-Driver)

| 13.0+                                                                      | 14.0 +                                                                     | 15.0 +                                                                     |
| -------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| [13.0](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/13.0) | [14.0](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/14.0) | [15.0](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/15.0) |
| [13.1](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/13.1) | [14.1](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/14.1) |                                                                            |
| [13.2](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/13.2) | [14.2](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/14.2) |                                                                            |
| [13.3](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/13.3) | [14.3](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/14.3) |                                                                            |
| [13.4](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/13.4) | [14.4](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/14.4) |                                                                            |
| [13.5](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/13.5) |                                                                            |                                                                            |
| [13.6](https://github.com/justin-himself/NV-VGPU-History-Driver/tree/13.6) |                                                                            |                                                                            |




## How to download

Every driver is splited into zip packages of size 99MB. This is to bypass the github individual file size limit.

To download a driver, you can

- download every splitted zip file manually, in your browser
- use [this online tool](https://download-directory.github.io/) to download a folder
- use [this chrome extension](https://chrome.google.com/webstore/detail/gitzip-for-github/ffabmkklhbepgcgfonabamgnfafbdlkn) to download a folder

After downloading, you can use tools such as 7zip(Windows), Keka(Mac), or use the zip utility in unix-like OS.

```bash
zip -s 0 driver_name.zip -O driver_name_full.zip
unzip driver_name_full.zip
```
