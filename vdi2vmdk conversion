#!/bin/bash
#uses virtualbox to convert hd
#converts vdi to vmdk
VBoxManage internalcommands converthd -srcformat VDI -dstformat VMDK <vm path>.vdi <destination path>.vmdk

#converts virtual to physical
#VBoxManage internalcommands converttoraw <destination path>.vdi <destination path>.iso

md5 <destination path>.vmdk

exit
