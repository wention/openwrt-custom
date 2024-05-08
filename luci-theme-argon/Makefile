#
# Copyright (C) 2008-2019 Jerrykuku
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=Argon Theme

LUCI_DEPENDS:=+curl +jsonfilter
PKG_VERSION:=2.3.1
PKG_RELEASE:=20230420

CONFIG_LUCI_CSSTIDY:=


PKG_SOURCE:=luci-theme-argon-${PKG_VERSION}.tar.gz
PKG_SOURCE_URL:=https://codeload.github.com/jerrykuku/luci-theme-argon/tar.gz/refs/tags/v${PKG_VERSION}?
PKG_HASH:=0000c3e34a11a5bfc7d97a00acaf101428366629c6bb144cd8ead1cd61a0691c


include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
