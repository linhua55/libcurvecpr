lib_LTLIBRARIES = libcurvecpr.la

libcurvecpr_la_CPPFLAGS = -I$(top_srcdir)/libcurvecpr/include
libcurvecpr_la_CFLAGS = @LIBSODIUM_CFLAGS@
libcurvecpr_la_LDFLAGS = -version-info $(CURVECPR_LIBRARY_VERSION) @LIBSODIUM_LIBS@
libcurvecpr_la_SOURCES = \
    bytes.c \
    chicago.c \
    client.c \
    client_recv.c \
    client_send.c \
    messager.c \
    server.c \
    server_recv.c \
    server_send.c \
    session.c \
    trace.c \
    util.c
