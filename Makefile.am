SUBDIRS = img src

EXTRA_DIST = \
	README.md

AUTOMAKE_OPTIONS = foreign

.PHONY: fixme
fixme:
	@grep -n -E '(FIXME|THINKME|TODO)' --color=always -r $(SUBDIRS:%=$(srcdir)/%) || \
		echo 'No FIXME, THINKME, nor TODO were found.'
