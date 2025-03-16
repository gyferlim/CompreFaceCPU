# CompreFaceCPU
## A Fork of Exadel-Inc CompreFace

This is a fork of [Exadel-Inc CompreFace](https://github.com/exadel-inc/CompreFace), a powerful tool with **face recognition** and **face verification** capabilities.
Code are modified to accommodate CPU with more and better resources ( Xeon v3 , AVX2 ). Model and plugin in use: mobilenet 1.20 , retina_mnet_v1, arcface-r50-msfdrop75.

You can change the model or plugins according to your need. For more, please refer to [here](https://github.com/exadel-inc/CompreFace/blob/master/custom-builds/README.md)

## Features:
- **Low Resource Requirements**: Fully capable of running on CPU with minimal hardware demands.
- **Optimized for Dockge**: The code is optimized to run on [Dockge](https://github.com/louislam/dockge), which operates on top of Proxmox LXC.
- **No GPU Required**: Designed to work efficiently without the need for a GPU.

## Integration with Home Assistant and Frigate
When integrated with [Home Assistant](https://www.home-assistant.io/) and [Frigate](https://frigate.video/), the detector's inference speed is typically **less than 100ms**, ensuring fast and reliable performance.
