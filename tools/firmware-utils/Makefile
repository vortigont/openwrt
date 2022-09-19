#
# Copyright (C) 2006-2020 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

PKG_NAME:=firmware-utils
PKG_RELEASE:=1

PKG_SOURCE_PROTO:=git
PKG_SOURCE_URL=https://github.com/vortigont/firmware-utils.git
#PKG_SOURCE_URL=$(PROJECT_GIT)/project/firmware-utils.git
PKG_SOURCE_DATE:=2024-10-20
PKG_SOURCE_VERSION:=2f89d521eee708d6e6a00d97edda796b17217c7a
#PKG_MIRROR_HASH:=ea0e30f2b20211e4153704019ebb3f8789269893a4af6d853a85fae7c091802c

include $(INCLUDE_DIR)/host-build.mk
include $(INCLUDE_DIR)/cmake.mk

$(eval $(call HostBuild))
