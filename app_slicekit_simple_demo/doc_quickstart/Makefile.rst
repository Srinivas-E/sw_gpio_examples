all: html

SPHINX_PROJECT_NAME = SIMPLE GPIO Demo Quickstart Guide
VERSION = 0.1
SOURCE_INCLUDE_DIRS = ../app_slicekit_simple_demo
XDOC_DIR ?= ../../../xdoc
include $(XDOC_DIR)/Makefile.inc
