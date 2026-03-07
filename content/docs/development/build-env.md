---
title: Build Environment
weight: 10
---

# Build Environment
The `scratch3-tello` repository contains per-file diffs for the `scratch-vm` and `scratch-gui` repositories. To build Scratch3-Tello, you need to clone `scratch-vm` and `scratch-gui` and then apply the diffs.

## Requirements
- wget
- git
- node.js
- npm

## Create a working directory
```bash
$ mkdir scratch3-tello
$ cd scratch3-tello
```

## Download the build script
```bash
$ wget https://raw.githubusercontent.com/kebhr/scratch3-tello/master/build.sh
$ chmod +x build.sh
```

## Run the build script
```bash
$ ./build.sh
```

Running `build.sh` will automatically clone `scratch-vm`, `scratch-gui`, and `scratch-desktop`, and apply the diff files managed by the `scratch3-tello` repository.

## Start Scratch3-Tello
```bash
$ cd scratch-desktop
$ npm start
```

## Build a package
```bash
$ cd scratch-desktop
$ npm run dist:dir
```
