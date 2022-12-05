# SPDX-License-Identifier: GPL-2.0-only
drbd-y := drbd_buildtag.o drbd_bitmap.o drbd_proc.o
drbd-y += drbd_sender.o drbd_receiver.o drbd_req.o drbd_actlog.o
drbd-y += drbd_main.o drbd_strings.o drbd_nl.o
drbd-y += drbd_interval.o drbd_state.o
drbd-y += drbd_nla.o drbd_transport.o
drbd-$(CONFIG_DEBUG_FS) += drbd_debugfs.o

obj-$(CONFIG_BLK_DEV_DRBD)     += drbd.o
obj-$(CONFIG_DRBD_TRANSPORT_TCP) += drbd_transport_tcp.o
obj-$(CONFIG_DRBD_TRANSPORT_RDMA) += drbd_transport_rdma.o
obj-$(CONFIG_DRBD_TRANSPORT_LB_TCP) += drbd_transport_lb-tcp.o
