#
# Makefile for Provenance LSM
#
obj-$(CONFIG_SECURITY_PROVENANCE_QUERY_TRACKING) := tracking.o

tracking-y := query.o

ccflags-y := -I$(srctree)/security/provenance/include -I$(srctree)/security/provenance/query/include
