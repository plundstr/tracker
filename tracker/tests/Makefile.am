include $(top_srcdir)/Makefile.decl

SUBDIRS =                                              \
	common                                         \
	gvdb					       \
	libtracker-common                              \
	libtracker-extract                             \
	libtracker-miner                               \
	libtracker-data                                \
	libtracker-sparql                              \
	tracker-steroids                               \
	tracker-writeback

if DIST_FUNCTIONAL_TESTS
SUBDIRS += functional-tests
endif

if HAVE_TRACKER_FTS
SUBDIRS += libtracker-fts
endif
