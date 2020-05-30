bin_PROGRAMS = aget
aget_SOURCES = \
	src/aget.c \
	src/aget.h \
	src/conf.h \
	src/conf.c \
	src/conn.c \
	src/conn.h \
	src/http.h \
	src/http.c \
	src/main.c

AM_CFLAGS = $(PTHREAD_CFLAGS) $(WARN_CFLAGS) \
	-Wno-declaration-after-statement \
	-Wno-error=cast-align \
	-Wno-error=inline

aget_LDADD = $(LIBOBJS) $(LIBINTL) $(PTHREAD_LIBS)
aget_CC = $(PTHREAD_CC)
