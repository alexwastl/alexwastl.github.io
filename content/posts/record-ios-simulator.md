---
date: '2024-12-06T14:23:26+01:00'
draft: false
title: 'Record video on iOS simulator'
---

It's very easy on MacOS to record your Simulator. 

1. Start Simulator 
2. Open Terminal 
3. Take video with
{{< highlight go >}} xcrun simctl io booted recordVideo appVideo.mov {{< /highlight >}}

The video is stored in the directly where the "xcrun" command is executed. 

