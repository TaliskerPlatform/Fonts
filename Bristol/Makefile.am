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

dist_noinst_DATA = FONTLOG.txt DESCRIPTION.en_us.html OFL.txt \
	METADATA.json \
	Cabin-Bold.ttf Cabin-BoldItalic.ttf Cabin-Italic.ttf Cabin-Medium.ttf \
	Cabin-MediumItalic.ttf Cabin-Regular.ttf Cabin-SemiBold.ttf \
	Cabin-SemiBoldItalic.ttf \
	Bristol-400.sfd Bristol-400.otf \
	Bristol-400-Italic.sfd Bristol-400-Italic.otf \
	Bristol-500.sfd Bristol-500.otf \
	Bristol-500-Italic.sfd Bristol-500-Italic.otf \
	Bristol-600.sfd Bristol-600.otf \
	Bristol-600-Italic.sfd Bristol-600-Italic.otf \
	Bristol-700.sfd Bristol-700.otf
	Bristol-700-Italic.sfd Bristol-700-Italic.otf

fontsdir = $(prefix)/Library/Fonts

install-data-hook:
	$(MKDIR_P) '$(DESTDIR)$(fontsdir)'
	$(INSTALL_DATA) Bristol-400.otf '$(DESTDIR)$(fontsdir)/Bristol 400.otf'
	$(INSTALL_DATA) Bristol-400-Italic.otf '$(DESTDIR)$(fontsdir)/Bristol 400 Italic.otf'
	$(INSTALL_DATA) Bristol-500.otf '$(DESTDIR)$(fontsdir)/Bristol 500.otf'
	$(INSTALL_DATA) Bristol-500-Italic.otf '$(DESTDIR)$(fontsdir)/Bristol 500 Italic.otf'
	$(INSTALL_DATA) Bristol-600.otf '$(DESTDIR)$(fontsdir)/Bristol 600.otf'
	$(INSTALL_DATA) Bristol-600-Italic.otf '$(DESTDIR)$(fontsdir)/Bristol 600 Italic.otf'
	$(INSTALL_DATA) Bristol-700.otf '$(DESTDIR)$(fontsdir)/Bristol 700.otf'
	$(INSTALL_DATA) Bristol-700-Italic.otf '$(DESTDIR)$(fontsdir)/Bristol 700 Italic.otf'
