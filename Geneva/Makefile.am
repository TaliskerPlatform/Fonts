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

dist_noinst_DATA = COPYRIGHT.txt DESCRIPTION.en_us.html LICENSE.txt \
	METADATA.json Roboto-Black.ttf Roboto-BlackItalic.ttf Roboto-Bold.ttf \
	Roboto-BoldItalic.ttf Roboto-Italic.ttf Roboto-Light.ttf \
	Roboto-LightItalic.ttf Roboto-Medium.ttf Roboto-MediumItalic.ttf \
	Roboto-Regular.ttf Roboto-Thin.ttf Roboto-ThinItalic.ttf \
	fonts.css specimen.html \
	Geneva-100.sfd Geneva-100.otf \
	Geneva-100-Italic.sfd Geneva-100-Italic.otf \
	Geneva-300.sfd Geneva-300.otf \
	Geneva-300-Italic.sfd Geneva-300-Italic.otf \
	Geneva-400.sfd Geneva-400.otf \
	Geneva-400-Italic.sfd Geneva-400-Italic.otf \
	Geneva-500.sfd Geneva-500.otf \
	Geneva-500-Italic.sfd Geneva-500-Italic.otf \
	Geneva-700.sfd Geneva-700.otf \
	Geneva-700-Italic.sfd Geneva-700-Italic.otf \
	Geneva-900.sfd Geneva-900.otf \
	Geneva-900-Italic.sfd Geneva-900-Italic.otf

fontsdir = $(prefix)/Library/Fonts

install-data-hook:
	$(MKDIR_P) '$(DESTDIR)$(fontsdir)'
	$(INSTALL_DATA) Geneva-100.otf '$(DESTDIR)$(fontsdir)/Geneva 100.otf'
	$(INSTALL_DATA) Geneva-100-Italic.otf '$(DESTDIR)$(fontsdir)/Geneva 100 Italic.otf'
	$(INSTALL_DATA) Geneva-300.otf '$(DESTDIR)$(fontsdir)/Geneva 300.otf'
	$(INSTALL_DATA) Geneva-300-Italic.otf '$(DESTDIR)$(fontsdir)/Geneva 300 Italic.otf'
	$(INSTALL_DATA) Geneva-400.otf '$(DESTDIR)$(fontsdir)/Geneva 400.otf'
	$(INSTALL_DATA) Geneva-400-Italic.otf '$(DESTDIR)$(fontsdir)/Geneva 400 Italic.otf'
	$(INSTALL_DATA) Geneva-500.otf '$(DESTDIR)$(fontsdir)/Geneva 500.otf'
	$(INSTALL_DATA) Geneva-500-Italic.otf '$(DESTDIR)$(fontsdir)/Geneva 500 Italic.otf'
	$(INSTALL_DATA) Geneva-700.otf '$(DESTDIR)$(fontsdir)/Geneva 700.otf'
	$(INSTALL_DATA) Geneva-700-Italic.otf '$(DESTDIR)$(fontsdir)/Geneva 700 Italic.otf'
	$(INSTALL_DATA) Geneva-900.otf '$(DESTDIR)$(fontsdir)/Geneva 900.otf'
	$(INSTALL_DATA) Geneva-900-Italic.otf '$(DESTDIR)$(fontsdir)/Geneva 900 Italic.otf'
