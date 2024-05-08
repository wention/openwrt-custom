include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for clash
LUCI_DEPENDS:=+dnsmasq-full +coreutils +coreutils-nohup +bash +curl +ca-certificates +ipset +ip-full +libcap +libcap-bin +ruby +ruby-yaml +kmod-tun +unzip
PKG_VERSION:=0.46.003

PKG_SOURCE:=luci-app-openclash-${PKG_VERSION}.tar.gz
PKG_SOURCE_URL:=https://codeload.github.com/vernesong/OpenClash/tar.gz/refs/tags/v${PKG_VERSION}-beta?
PKG_HASH:=c8ac9be13e9a07d9e481678e0496e2a7a45b19e5a94541242d95776aa4f6c906

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
