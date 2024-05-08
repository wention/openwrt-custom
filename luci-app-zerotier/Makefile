#
# Copyright (C) 2008-2014 The LuCI Team <luci@lists.subsignal.org>

#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI for Zerotier
LUCI_DEPENDS:=+zerotier
LUCI_PKGARCH:=all
PKG_VERSION:=1.0
PKG_RELEASE:=16

PKG_SOURCE:=luci-app-zerotier-${PKG_VERSION}-${PKG_RELEASE}.tar.gz
PKG_SOURCE_URL:=https://codeload.github.com/rufengsuixing/luci-app-zerotier/tar.gz/refs/tags/${PKG_VERSION}-${PKG_RELEASE}?
PKG_HASH:=e22cd04454b4483c31c935edb1d2d9ffb4b824eba5c882092a6fa8c9cb7d3767

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
