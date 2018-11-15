
invoke:
virdiskmount set filepath.vmdk - return vdisk device name
virdiskmount info filepath.vmdk - direct read disk and show
virdiskmount unset vdiskdevice -

this will

    -set create a vdisk device (@todo kernel block module like loop) that can be used as any block device
    the block device is equivalent to a removable disk
    -info get virtual disk info (read header and partition information)
    -unset remove current vdisk device


