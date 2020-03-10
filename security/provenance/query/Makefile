#
# Makefile for Provenance LSM
#
obj-$(CONFIG_SECURITY_PROVENANCE_QUERY) := query.o
subdir-$(CONFIG_SECURITY_PROVENANCE_QUERY_PROPAGATE)	+= propagate

query-y := register.o

ccflags-y := -I$(srctree)/security/provenance/include -I$(srctree)/security/provenance/query/include
