[![Build OpenWrt](https://github.com/minax007/XIAOMI_MI-3C_OpenWrt/actions/workflows/build-openwrt-mi3c.yml/badge.svg)](https://github.com/minax007/XIAOMI_MI-3C_OpenWrt/actions/workflows/build-openwrt-mi3c.yml)
[![release](https://img.shields.io/github/v/release/minax007/XIAOMI_MI-3C_OpenWrt.svg)](https://github.com/minax007/XIAOMI_MI-3C_OpenWrt/releases)

# OpenWrt snapshot for Xiaomi Mi-3C (R3C) incl. LuCI

This GitHub action is to build fresh images of latest OpenWrt snapshot for the Mi-Nano, which is compatible to Mi-3C, using imagebuilder.

![grafik](https://user-images.githubusercontent.com/67478561/117842017-d63e5f00-b27d-11eb-879b-911e93848cdb.png)

Following packages are already installed, so that you do not need to install them via the command line afterwards: 

Added features | Package names
------------ | -------------
**LuCI GUI** | luci
**LuCI Material Theme** | luci-theme-material 
**LuCI Bandwidth Monitor** | luci-app-nlbwmon
**LuCI SQM (QoS)** | luci-app-sqm
__________________________________________________________________
**Official OpenWrt snapshot of MiWiFi-Nano build without LuCI:**

https://firmware-selector.openwrt.org/?version=SNAPSHOT&target=ramips%2Fmt76x8&id=xiaomi_miwifi-nano
__________________________________________________________________
**Official OpenWrt snapshot download directory for MT76x8 routers, which includes the imagebuilder used in this action script:**

https://downloads.openwrt.org/snapshots/targets/ramips/mt76x8/

__________________________________________________________________
This repository was  forked from https://github.com/amaumene/xiaomi_redmi-router-ac2100_openwrt_mesh
