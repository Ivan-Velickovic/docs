---
toc: true
arm_platform: true
cmake_plat: qemu-arm-virt
xcompiler_arg: -DAARCH64=1
platform: QEMU ARM virt
arch: ARMv7A, ARMv8A
virtualization: "Yes"
iommu: "No"
soc: QEMU ARM virt
cpu: Cortex-A53 (by default)
Status: Unverified
Contrib: Data61
Maintained: seL4 Foundation
SPDX-License-Identifier: CC-BY-SA-4.0
SPDX-FileCopyrightText: 2020 seL4 Project a Series of LF Projects, LLC.
---

# QEMU ARM virt

This platform refers to the generic ARM virtual platform provided by QEMU, more details can be
found at [QEMU's documentation](https://www.qemu.org/docs/master/system/arm/virt.html).

The virtual platform supports a number of 32-bit and 64-bit CPUs. On AArch64, the Cortex-A53 is
the default simulated CPU.

## Building seL4test

{% include sel4test.md %}
