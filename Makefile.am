ACLOCAL_AMFLAGS = -I m4

all:

install-data-hook:
if !ENABLE_LIGHT
if !ENABLE_DARK
if !ENABLE_COMPACT
	install -dm755 $(DESTDIR)$(datadir)/themes/Adapta/gtk-3.0
	cp $(srcdir)/adapta/index.theme $(DESTDIR)$(datadir)/themes/Adapta
	cp $(srcdir)/adapta/gtk.css $(DESTDIR)$(datadir)/themes/Adapta/gtk-3.0
	cp $(srcdir)/adapta/gtk-dark.css $(DESTDIR)$(datadir)/themes/Adapta/gtk-3.0
	cp $(srcdir)/adapta/gtk.gresource $(DESTDIR)$(datadir)/themes/Adapta/gtk-3.0
endif
if ENABLE_COMPACT
	install -dm755 $(DESTDIR)$(datadir)/themes/Adapta-Eta/gtk-3.0
	cp $(srcdir)/adapta-eta/index.theme $(DESTDIR)$(datadir)/themes/Adapta-Eta
	cp $(srcdir)/adapta-eta/gtk.css $(DESTDIR)$(datadir)/themes/Adapta-Eta/gtk-3.0
	cp $(srcdir)/adapta-eta/gtk-dark.css $(DESTDIR)$(datadir)/themes/Adapta-Eta/gtk-3.0
	cp $(srcdir)/adapta-eta/gtk.gresource $(DESTDIR)$(datadir)/themes/Adapta-Eta/gtk-3.0
endif
endif
endif

if ENABLE_LIGHT
if !ENABLE_COMPACT
	install -dm755 $(DESTDIR)$(datadir)/themes/Adapta-Brila/gtk-3.0
	cp $(srcdir)/adapta-brila/index.theme $(DESTDIR)$(datadir)/themes/Adapta-Brila
	cp $(srcdir)/adapta-brila/gtk.css $(DESTDIR)$(datadir)/themes/Adapta-Brila/gtk-3.0
	cp $(srcdir)/adapta-brila/gtk-dark.css $(DESTDIR)$(datadir)/themes/Adapta-Brila/gtk-3.0
	cp $(srcdir)/adapta-brila/gtk.gresource $(DESTDIR)$(datadir)/themes/Adapta-Brila/gtk-3.0
endif
if ENABLE_COMPACT
	install -dm755 $(DESTDIR)$(datadir)/themes/Adapta-Brila-Eta/gtk-3.0
	cp $(srcdir)/adapta-brila-eta/index.theme $(DESTDIR)$(datadir)/themes/Adapta-Brila-Eta
	cp $(srcdir)/adapta-brila-eta/gtk.css $(DESTDIR)$(datadir)/themes/Adapta-Brila-Eta/gtk-3.0
	cp $(srcdir)/adapta-brila-eta/gtk-dark.css $(DESTDIR)$(datadir)/themes/Adapta-Brila-Eta/gtk-3.0
	cp $(srcdir)/adapta-brila-eta/gtk.gresource $(DESTDIR)$(datadir)/themes/Adapta-Brila-Eta/gtk-3.0
endif
endif

if ENABLE_DARK
if !ENABLE_COMPACT
	install -dm755 $(DESTDIR)$(datadir)/themes/Adapta-Nokto/gtk-3.0
	cp $(srcdir)/adapta-nokto/index.theme $(DESTDIR)$(datadir)/themes/Adapta-Nokto
	cp $(srcdir)/adapta-nokto/gtk.css $(DESTDIR)$(datadir)/themes/Adapta-Nokto/gtk-3.0
	cp $(srcdir)/adapta-nokto/gtk.gresource $(DESTDIR)$(datadir)/themes/Adapta-Nokto/gtk-3.0
endif
if ENABLE_COMPACT
	install -dm755 $(DESTDIR)$(datadir)/themes/Adapta-Nokto-Eta/gtk-3.0
	cp $(srcdir)/adapta-nokto-eta/index.theme $(DESTDIR)$(datadir)/themes/Adapta-Nokto-Eta
	cp $(srcdir)/adapta-nokto-eta/gtk.css $(DESTDIR)$(datadir)/themes/Adapta-Nokto-Eta/gtk-3.0
	cp $(srcdir)/adapta-nokto-eta/gtk.gresource $(DESTDIR)$(datadir)/themes/Adapta-Nokto-Eta/gtk-3.0
endif
endif

uninstall-hook:
if !ENABLE_LIGHT
if !ENABLE_DARK
if !ENABLE_COMPACT
	test -e $(DESTDIR)$(datadir)/themes/Adapta && rm -rfv $(DESTDIR)$(datadir)/themes/Adapta
endif
if ENABLE_COMPACT
	test -e $(DESTDIR)$(datadir)/themes/Adapta-Eta && rm -rfv $(DESTDIR)$(datadir)/themes/Adapta-Eta
endif
endif
endif

if ENABLE_LIGHT
if !ENABLE_COMPACT
	test -e $(DESTDIR)$(datadir)/themes/Adapta-Brila && rm -rfv $(DESTDIR)$(datadir)/themes/Adapta-Brila
endif
if ENABLE_COMPACT
	test -e $(DESTDIR)$(datadir)/themes/Adapta-Brila-Eta && rm -rfv $(DESTDIR)$(datadir)/themes/Adapta-Brila-Eta
endif
endif

if ENABLE_DARK
if !ENABLE_COMPACT
	test -e $(DESTDIR)$(datadir)/themes/Adapta-Nokto && rm -rfv $(DESTDIR)$(datadir)/themes/Adapta-Nokto
endif
if ENABLE_COMPACT
	test -e $(DESTDIR)$(datadir)/themes/Adapta-Nokto-Eta && rm -rfv $(DESTDIR)$(datadir)/themes/Adapta-Nokto-Eta
endif
endif
