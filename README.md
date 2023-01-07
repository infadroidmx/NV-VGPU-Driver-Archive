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


## Preview

To get you a rough idea of what each zip is containing, here's the `tree` output of fully extracted 15.0 branch.  

https://github.com/justin-himself/NV-VGPU-History-Driver/blob/master/preview.txt


## How to download

Every driver is splited into zip packages of size 99MB. This is to bypass the github individual file size limit.

To download a driver, you can

- download every splitted zip file manually, in your browser
- use [this online tool](https://download-directory.github.io/) to download a folder
- use [this chrome extension](https://chrome.google.com/webstore/detail/gitzip-for-github/ffabmkklhbepgcgfonabamgnfafbdlkn) to download a folder

After downloading, you can use tools such as 7zip(Windows), Keka(Mac), or use the 7z utility in unix-like OS.

```bash
apt install p7zip-full
7z x driver_name.zip
```

To extract in batch, do

```bash
for d in */; do
	f=${d::-1}
	7z x $f/$f.zip -o$f/
	rm $f/$f.z*
done
```

## Source

- [NVIDIA Drivers](https://ui.licensing.nvidia.com/software)



