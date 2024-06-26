![image](./info.png)

# BootIMGExtractAction

This action extracts boot.img / init_boot.img from a ROM and uploads them to the Releases section.

---

English | [简体中文](./README_CN.md)

## Usage

1. Fork this repository.
2. In the Actions tab, select either 'boot' or 'init_boot', and provide the direct download link to your ROM.
3. Click on "Run workflow" and wait for the process to complete.

**If you encounter a "403 Forbidden" error, go to Settings > Actions > General > Workflow permissions and adjust it to "Read and write permissions".**

**This project only supports 'Recovery ROM'.**

**To ensure functionality, add a secret named 'app_token' in your personal repository's Settings > Secrets > Actions. Set its value to 'TMP'.**

## Others

Special thanks to [tosasitill](https://github.com/tosasitill) and [5ec1cff](https://github.com/5ec1cff).

This project relies on [payload-dumper](https://github.com/5ec1cff/payload-dumper).

Tested on: May 9, 2024