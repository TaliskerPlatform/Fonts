## Copyright 2015 Mo McRoberts.
##
##  Licensed under the Apache License, Version 2.0 (the "License");
##  you may not use this file except in compliance with the License.
##  You may obtain a copy of the License at
##
##      http://www.apache.org/licenses/LICENSE-2.0
##
##  Unless required by applicable law or agreed to in writing, software
##  distributed under the License is distributed on an "AS IS" BASIS,
##  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
##  See the License for the specific language governing permissions and
##  limitations under the License.

## See README.md for the full list of typeface credits.

dist_noinst_DATA = LICENSE-2.0 README.md specimen.css

SUBDIRS = TaliskerTerminal Roboto Bristol BristolSketch

fontsdir = $(prefix)/Library/Fonts

# make has problems with filenames containing spaces, so we install using
# a hook instead.

install-data-hook:
	$(MKDIR_P) '$(DESTDIR)$(fontsdir)'
	$(INSTALL_DATA) '$(srcdir)/Fanwood/Fanwood.otf' '$(DESTDIR)$(fontsdir)/Fanwood Regular.otf'
	$(INSTALL_DATA) '$(srcdir)/Fanwood/Fanwood Text.otf' '$(DESTDIR)$(fontsdir)/Fanwood Text.otf'
	$(INSTALL_DATA) '$(srcdir)/Fanwood/Fanwood Text Italic.otf' '$(DESTDIR)$(fontsdir)/Fanwood Text Italic.otf'
	$(INSTALL_DATA) '$(srcdir)/Fanwood/Fanwood Italic.otf' '$(DESTDIR)$(fontsdir)/Fanwood Italic.otf'
	$(INSTALL_DATA) '$(srcdir)/Junction/Junction-regular.otf' '$(DESTDIR)$(fontsdir)/Junction Regular.otf'
	$(INSTALL_DATA) '$(srcdir)/Junction/Junction-bold.otf' '$(DESTDIR)$(fontsdir)/Junction Bold.otf'
	$(INSTALL_DATA) '$(srcdir)/Junction/Junction-light.otf' '$(DESTDIR)$(fontsdir)/Junction Light.otf'
	$(INSTALL_DATA) '$(srcdir)/LeagueGothic/LeagueGothic-Regular.otf' '$(DESTDIR)$(fontsdir)/League Gothic Regular.otf'
	$(INSTALL_DATA) '$(srcdir)/LeagueGothic/LeagueGothic-Italic.otf' '$(DESTDIR)$(fontsdir)/League Gothic Italic.otf'
	$(INSTALL_DATA) '$(srcdir)/LeagueGothic/LeagueGothic-CondensedRegular.otf' '$(DESTDIR)$(fontsdir)/League Gothic Condensed.otf'
	$(INSTALL_DATA) '$(srcdir)/LeagueGothic/LeagueGothic-CondensedItalic.otf' '$(DESTDIR)$(fontsdir)/League Gothic Condensed Italic.otf'
	$(INSTALL_DATA) '$(srcdir)/Prociono/Prociono.otf' '$(DESTDIR)$(fontsdir)/Prociono Regular.otf'
	$(INSTALL_DATA) '$(srcdir)/Raleway/Raleway Thin.otf' '$(DESTDIR)$(fontsdir)'
