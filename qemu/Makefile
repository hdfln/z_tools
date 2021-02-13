QEMU		= qemu-system-i386
QEMU_ARGS	= -drive file=fdimage0.bin,index=0,if=floppy,format=raw -boot order=a -m 32M


default:
	$(QEMU) $(QEMU_ARGS)
