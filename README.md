# rellos
RellOS - Red Rolling Linux | Custom Arch-based OS with Plasma
# RellOS

![RellOS Logo](https://github.com/RellOS-ux/rellos/blob/main/P.jpg)

**Red Rolling Linux** — A custom Arch-based OS with Plasma desktop.

## About
RellOS is a customizable, rolling-release Linux distribution based on Arch and EndeavourOS combined.

- Easy to build and modify

## Download

**Latest ISO** (3.6 GB): [Download RellOS ISO](https://drive.google.com/file/d/1aqeu-qahf4sMBN_OhqYEqrnNkS91FKnA/view?usp=drive_link)

**Note**: You can also build it yourself (recommended).

**Second Option**

```bash
sudo pacman -S archiso
git clone https://github.com/RellOS-ux/rellos.git
cd rellos
sudo mkarchiso -v -r -w /tmp/rellos-work -o out .
