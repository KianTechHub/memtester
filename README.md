# Memtester Build Instructions

**Version**: 4.6.0  
**Release Date**: 19 December 2022

## Android Build Instructions

Tested on **Android 12**.

1. Navigate to the Android source directory:
   ```bash
   cd <android_source>
   ```
2. Set up the environment:
   ```bash
   source ./build/envsetup.sh
   ```
3. Choose the appropriate build target:
   ```bash
   lunch
   ```
4. Clone the `memtester` repository:
   ```bash
   cd <android_source>/external/
   git clone <url>
   ```
5. Build `memtester`:
   ```bash
   cd memtester
   mm
   ```

## Linux Build Instructions

Tested on **Ubuntu 22.04**.

1. Clone the `memtester` repository:
   ```bash
   git clone <url>
   ```
2. Build `memtester`:
   ```bash
   cd memtester
   make
   ```

---

### Notes

- Make sure to replace `<android_source>` and `<url>` with your actual directory and repository URL.
  
---

这是一个链接 [Markdown语法](https://markdown.com.cn)。
