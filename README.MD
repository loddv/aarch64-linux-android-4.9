# Aarch64 Linux Android 4.9 Toolchain

This repository provides the **Aarch64 Linux Android 4.9 Toolchain**, which is a cross-compiler for building Android kernels for ARM64 devices.

## Features
- GCC 4.9 toolchain optimized for ARM64 architecture.
- Compatible with Android builds.
- Provides robust support for kernel compilation and customization.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/loddv/aarch64-linux-android-4.9.git
   ```
2. Add the toolchain to your `PATH`:
   ```bash
   export PATH=$(pwd)/aarch64-linux-android-4.9/bin:$PATH
   ```
3. Compile your Android kernel:
   ```bash
   make ARCH=arm64 CROSS_COMPILE=aarch64-linux-android-4.9- <target>
   ```

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.