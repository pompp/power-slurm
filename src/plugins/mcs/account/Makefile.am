# Makefile for mcs/account plugin

AUTOMAKE_OPTIONS = foreign

PLUGIN_FLAGS = -module -avoid-version --export-dynamic

AM_CPPFLAGS = -I$(top_srcdir) -I$(top_srcdir)/src/common

pkglib_LTLIBRARIES = mcs_account.la

# mcs/account plugin.
mcs_account_la_SOURCES = mcs_account.c
mcs_account_la_LDFLAGS = $(SO_LDFLAGS) $(PLUGIN_FLAGS)
