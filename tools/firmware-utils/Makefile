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
PKG_SOURCE_DATE:=2026-02-15
PKG_SOURCE_VERSION:=8e847a213fa804a323458935fb567f589ebdf7d8
#PKG_MIRROR_HASH:=19f5b7547dc6f9460e25183c83d55aca9d1f18148466c09b64504a64379a34ae

include $(INCLUDE_DIR)/host-build.mk
include $(INCLUDE_DIR)/cmake.mk

$(eval $(call HostBuild))
