# Memtester Build Instructions

**Version**: 4.6.0  
**Release Date**: 19 December 2022
https://pyropus.ca./software/memtester/

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

I just porting it for Android.

More detailed description of the original [README](https://github.com/sunqianGitHub/memtester/blob/main/README)。
