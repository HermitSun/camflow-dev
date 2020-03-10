#
# Makefile for Provenance LSM
#
obj-$(CONFIG_SECURITY_PROVENANCE) := provenance.o
subdir-$(CONFIG_SECURITY_PROVENANCE_QUERY)	+= query


obj-$(CONFIG_SECURITY_PROVENANCE_QUERY)		+= query/

provenance-y := relay.o hooks.o fs.o netfilter.o type.o machine.o memcpy_ss.o

ccflags-y := -I$(srctree)/security/provenance/include -I$(srctree)/security/provenance/query/include
