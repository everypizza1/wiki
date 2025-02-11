---
title: CachyOS Nvidia Modules
description: How does CachyOS handle the nvidia module>
published: 1
date: 2023-06-30T12:27:33.465Z
tags: cachyos, how-to, nvidia-module
editor: markdown
dateCreated: 2023-06-30T12:24:08.999Z
---

# How does CachyOS handle the nvidia module?

We are providing precompiled nvidia modules for every kernel. We are not relaying on nvidia-dkms anymore since Mid of November 2023.
This helps to avoid issues with compatibility or the compilation with nvidia-dkms.

# Namescheme of the Modules

We are following a quite easy naming scheme, which just adds "nvidia" to the end of the kernel.

## Examples

linux-cachyos --> linux-cachyos-nvidia
linux-cachyos-bore-lto --> linux-cachyos-bore-lto-nvidia

# Kernels provided from Arch

We are aware, that people also using kernels from arch as a fallback or other reasons.
Arch does provide for the "linux" (nvidia) and "linux-lts" (nvidia-lts) kernel a precompiled nvidia module.

We have added also the nvidia module for "linux-zen" (nvidia-zen) and "linux-hardened" (nvidia-hardened).
