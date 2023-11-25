# Copyright (C) 2023 JackKwok <xiujie520999@gmail.com>
#
# This is free software, licensed under the GNU General Public License v3.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-socat
PKG_VERSION:=20231031
PKG_RELEASE:=1

PKG_MAINTAINER:=chenmozhijin <cmzj11@gmail.com>

LUCI_TITLE:=LuCI support for Socat
LUCI_DEPENDS:=+socat
LUCI_PKGARCH:=all

define Package/$(PKG_NAME)/conffiles
/etc/config/socat_luci
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
