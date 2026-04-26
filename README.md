# Raspberry Pi OTA Library

This repository provides pre-built OTA (Over-The-Air) updates for Raspberry Pi devices. All releases are available on the [GitHub Releases](https://github.com/touhidurrr/rpi-ota-library/releases) page.

## Release Structure

For each OTA, 2 files are released:

1. OTA - [name].tar.zst
2. SHA-256 Checksum - [name].tar.zst.sha256sum

## Project Structure

Each OTA is organized under the `ota/` directory with the following structure:

```
ota/
├── <ota-name>/
│   ├── <files>
│   └── index.yml
```

- `<ota-name>`: The name of the OTA (e.g., `cloudflared`, `bun`)
- `<files>`: files that is packaged with the OTA
- `index.yml`: Metadata file containing version and other information

## Available OTAs

The following table lists the currently available OTAs, including their descriptions and download links for the OTA files and their SHA256 checksums.

|    Name     |                Description                |                                                  OTA                                                   |                                                 SHA256 Checksum                                                  |
| :---------: | :---------------------------------------: | :----------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------: |
| cloudflared | Cloudflare Tunnel client for Raspberry Pi | [Download](https://github.com/touhidurrr/rpi-ota-library/releases/latest/download/cloudflared.tar.zst) | [Download](https://github.com/touhidurrr/rpi-ota-library/releases/latest/download/cloudflared.tar.zst.sha256sum) |
|     bun     | Fast JavaScript runtime for Raspberry Pi  |     [Download](https://github.com/touhidurrr/rpi-ota-library/releases/latest/download/bun.tar.zst)     |     [Download](https://github.com/touhidurrr/rpi-ota-library/releases/latest/download/bun.tar.zst.sha256sum)     |
