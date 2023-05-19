# MineRL Fork

This is a fork of MineRL v0.4.4, the last version that is still based on Malmo
and therefore comes with abstract crafting and smelting actions.

## Modifications

- Remove the hardcoded brightness value in Malmo source code to allow changing
  the brightness in `options.txt`.
- Modified defaults in `options.txt` to remove visual artifacts during
  sprinting, reduce visual effects and simulation distance, and increase the
  brightness to 5.0 as used for official speed runs.

## Useful files

- **[`mc.py`](https://github.com/danijar/minerl/blob/main/minerl/herobraine/hero/mc.py)**
  contains important constants, including the list of all item names.
- **[`options.txt`](https://github.com/danijar/minerl/blob/main/minerl/Malmo/Minecraft/run/options.txt)**
  allows changing Minecraft [game options](https://minecraft.fandom.com/wiki/Options.txt).

## Installation

```
apt-get install -y libgl1-mesa-dev
apt-get install -y libx11-6
apt-get install -y openjdk-8-jdk
apt-get install -y x11-xserver-utils
apt-get install -y xvfb
pip install git+https://github.com/danijar/minerl.git@87ca0e3
```
