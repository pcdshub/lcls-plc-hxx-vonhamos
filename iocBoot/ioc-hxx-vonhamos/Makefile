IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.8.0

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = plc-hxx-vonhamos
PROJECT_PATH := ../../lcls-plc-hxx-vonhamos/lcls-plc-hxx-vonhamos.tsproj
PLC = hxx_vonhamos

PYTMC_OPTS :=
PREFIX = PLC:HXX:VONHAMOS

include $(IOC_TOP)/iocBoot/templates/Makefile.base

