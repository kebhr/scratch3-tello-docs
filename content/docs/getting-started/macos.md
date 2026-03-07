---
title: For macOS
weight: 20
bookToc: false
---

# For macOS

## Download
Go to [Releases](https://github.com/kebhr/scratch3-tello/releases) on GitHub and download the file named `macos.zip`.  

## Extract
Extract the downloaded zip file to a location of your choice.

## Launch
**After connecting to Tello**, launch `Scratch-Tello.app`, which is contained in the extracted folder.

On the first launch, macOS security restrictions will prevent you from opening the application by double-clicking.
Instead, hold the Control key and click the app, then select "Open" from the context menu.

![launch on macOS](/images/macos_launch.png)

Once launched, click the Extensions button in the lower-left corner and select the "Tello" extension. The blocks for programming Tello will appear.

## Troubleshooting

If Tello does not take off after running the `takeoff` block, commands from other blocks may be queued and waiting to execute. Running the "Reset command queue" block should resolve the issue.