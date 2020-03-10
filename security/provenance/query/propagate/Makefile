#
# Makefile for Provenance LSM
#
obj-$(CONFIG_SECURITY_PROVENANCE_QUERY_PROPAGATE) := propagate.o

propagate-y := query.o

ccflags-y := -I$(srctree)/security/provenance/include -I$(srctree)/security/provenance/query/include
