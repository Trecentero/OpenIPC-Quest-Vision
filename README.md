# OpenIPC Quest Vision - Wireless Eyes for Meta Quest 3

Stream any OpenIPC camera directly to Meta Quest 3 using Quest WiFi.
No cables, no capture card, no PC.

## Why?
Meta Vision Lab uses HDMI + capture card (wired). This project is the wireless version.
Perfect for animal vision, night vision and head-tracked cameras.

## What we want to test
1.  **Wireless Camera:** OpenIPC camera -> WiFi -> Quest 3
2.  **IR Night Vision:** OpenIPC cameras already have IR LEDs. Use them to see in dark.
3.  **Multi-Camera:** One camera on helmet, one on back. See like a prey animal.
4.  **Low Latency:** Target <100ms over WiFi 6.

## Hardware
- Meta Quest 3
- OpenIPC compatible camera (cheap IP cam flashed with OpenIPC)
- Same WiFi 6 network
- Optional: IR illuminator

## How it connects to Meta Vision Lab
Meta Vision Lab = wired HDMI source.
OpenIPC Quest Vision = wireless IP source.
Both use the same Vision Modes: Depth, Animal Vision, Night Vision.

## Status - v0.1
- [ ] Research OpenIPC compatible cameras
- [ ] Test RTSP stream in Quest 3
- [ ] Test latency over WiFi
- [ ] IR Night Vision test

## Author
David Ramirez - Costa Rica
Part of Meta Vision Lab experiments.
