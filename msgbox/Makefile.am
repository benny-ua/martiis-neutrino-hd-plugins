
AM_CPPFLAGS =  \
	@FREETYPE_CFLAGS@ \
	-I$(top_srcdir)/include

noinst_PROGRAMS = msgbox

msgbox_SOURCES = \
	msgbox.c \
	gfx.c \
	io.c \
	txtform.c \
	text.c

msgbox_LDADD = \
	@FREETYPE_LIBS@

install-exec-local:
	install -d $(DESTDIR)/bin
	install -m 0755 msgbox $(DESTDIR)/bin/msgbox
