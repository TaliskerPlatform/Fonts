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
	Roboto-Regular.ttf Roboto-Thin.ttf Roboto-ThinItalic.ttf

fontsdir = $(prefix)/Library/Fonts

install-data-hook:
	$(MKDIR_P) '$(DESTDIR)$(fontsdir)'
	$(INSTALL_DATA) Roboto-Black.ttf '$(DESTDIR)$(fontsdir)/Roboto Black.ttf'
	$(INSTALL_DATA) Roboto-BlackItalic.ttf '$(DESTDIR)$(fontsdir)/Roboto Black Italic.ttf'
	$(INSTALL_DATA) Roboto-Bold.ttf '$(DESTDIR)$(fontsdir)/Roboto Bold.ttf'
	$(INSTALL_DATA) Roboto-BoldItalic.ttf '$(DESTDIR)$(fontsdir)/Roboto Bold Italic.ttf'
	$(INSTALL_DATA) Roboto-Italic.ttf '$(DESTDIR)$(fontsdir)/Roboto Italic.ttf'
	$(INSTALL_DATA) Roboto-Light.ttf '$(DESTDIR)$(fontsdir)/Roboto Light.ttf'
	$(INSTALL_DATA) Roboto-LightItalic.ttf '$(DESTDIR)$(fontsdir)/Roboto Light Italic.ttf'
	$(INSTALL_DATA) Roboto-Medium.ttf '$(DESTDIR)$(fontsdir)/Roboto Medium.ttf'
	$(INSTALL_DATA) Roboto-MediumItalic.ttf '$(DESTDIR)$(fontsdir)/Roboto Medium Italic.ttf'
	$(INSTALL_DATA) Roboto-Regular.ttf '$(DESTDIR)$(fontsdir)/Roboto Regular.ttf'
	$(INSTALL_DATA) Roboto-Thin.ttf '$(DESTDIR)$(fontsdir)/Roboto Thin.ttf'
	$(INSTALL_DATA) Roboto-ThinItalic.ttf '$(DESTDIR)$(fontsdir)/Roboto Thin Italic.ttf'
