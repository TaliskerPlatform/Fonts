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
	Cabin-SemiBoldItalic.ttf

fontsdir = $(prefix)/Library/Fonts

install-data-hook:
	$(MKDIR_P) '$(DESTDIR)$(fontsdir)'
	$(INSTALL_DATA) Cabin-Bold.ttf '$(DESTDIR)$(fontsdir)/Cabin Bold.ttf'
	$(INSTALL_DATA) Cabin-BoldItalic.ttf '$(DESTDIR)$(fontsdir)/Cabin Bold Italic.ttf'
	$(INSTALL_DATA) Cabin-Italic.ttf '$(DESTDIR)$(fontsdir)/Cabin Italic.ttf'
	$(INSTALL_DATA) Cabin-Medium.ttf '$(DESTDIR)$(fontsdir)/Cabin Medium.ttf'
	$(INSTALL_DATA) Cabin-MediumItalic.ttf '$(DESTDIR)$(fontsdir)/Cabin Medium Italic.ttf'
	$(INSTALL_DATA) Cabin-Regular.ttf '$(DESTDIR)$(fontsdir)/Cabin Regular.ttf'
	$(INSTALL_DATA) Cabin-SemiBold.ttf '$(DESTDIR)$(fontsdir)/Cabin Semibold.ttf'
	$(INSTALL_DATA) Cabin-SemiBoldItalic.ttf '$(DESTDIR)$(fontsdir)/Cabin Semibold Italic.ttf'
