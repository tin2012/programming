obj-m = un.o

EXTRA_CFLAGS += -g
KSRC ?= /lib/modules/`uname -r`/build


all:
	 make -C $(KSRC) M=`pwd` SUBDIRS=$(PWD) modules

clean:
	 make -C $(KSRC) M=`pwd` SUBDIRS=$(PWD) clean
