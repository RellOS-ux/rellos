# rellos
RellOS - Red Rolling Linux | Custom Arch-based OS with Plasma
# RellOS

![RellOS Logo](https://github.com/RellOS-ux/rellos/blob/main/P.jpg)

**Red Rolling Linux** — A custom Arch-based OS with Plasma desktop.

## About
RellOS is a customizable, rolling-release Linux distribution based on Arch and EndeavourOS combined.

- Easy to build and modify

## How to build

```bash
sudo pacman -S archiso
git clone https://github.com/RellOS-ux/rellos.git
cd rellos
sudo mkarchiso -v -r -w /tmp/rellos-work -o out .
