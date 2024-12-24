# 📦 https://zenithval.github.io/vpm/ 📥

![GitHub deployments](https://img.shields.io/github/actions/workflow/status/ZenithVal/vpm/build-listing.yml?label=Build%20Package%20Listing)

This repo hosts my [VPM](https://vcc.docs.vrchat.com/vpm/)-compatible packages for use with [VCC](https://vcc.docs.vrchat.com/) or [ALCOM](https://vrc-get.anatawa12.com/alcom/).

## Usage With VCC
### Adding Repo Listing
- With the [latest VCC installed](https://vrchat.com/download/vcc), just go to https://rurre.github.io/vpm, click `Add to VCC` at the top, and follow the prompts!
- Otherwise, make sure you have the [VPM CLI](https://vcc.docs.vrchat.com/vpm/cli) installed, then run the command `vpm add repo https://rurre.github.io/vpm/index.json`.

### Adding Packages to a Project

In the VPM Interface, select your project, locate the `Selected Repos` dropdown, and check `Pumkin's VPM Repo`. Then, select the package you want to add, and click the plus button.

## Manual Usage

Each package has its own repository, and usually contains a standalone package distribution, as well as a VPM-compatible package distribution. If you want to use the standalone package, you can download it from the releases page of the package's repository.

## Special Thanks
- [pumkin](https://github.com/rurre) for reference & help setting this up. 
- [rrazgriz](https://github.com/rrazgriz/raz-vpm) original readme writer.

<br>

## Zeni Lazy shortcut
[build-listing.yml](.github/workflows/build-listing.yml)