
# Using thumb for version 7 ARM core:
CFLAGS  = -march=armv7-m -mthumb
ASFLAGS = -march=armv7-m -mthumb

# Library
LIBARCH = $(ADIR)/libarch.a
LIBARCH_OBJS = $(ADIR)/gpio.o
LIBARCH_OBJS += $(ADIR)/spi.o

$(ADIR)/libarch.a: $(LIBARCH_OBJS)
	$(AR) r $@ $(LIBARCH_OBJS)
