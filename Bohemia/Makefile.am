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

dist_noinst_DATA = COPYING \
	Fanwood.otf Fanwood-Italic.otf FanwoodText-Italic.otf FanwoodText.otf \
	specimen.html fonts.css Bohemia.png \
	Bohemia-400.sfd Bohemia-400.otf \
	Bohemia-400-Italic.sfd Bohemia-400-Italic.otf \
	BohemiaText-400.sfd BohemiaText-400.otf \
	BohemiaText-400-Italic.sfd BohemiaText-400-Italic.otf

fontsdir = $(prefix)/Library/Fonts

install-data-hook:
	$(MKDIR_P) '$(DESTDIR)$(fontsdir)'
	$(INSTALL_DATA) Bohemia-400.otf '$(DESTDIR)$(fontsdir)/Bohemia 400.otf'
	$(INSTALL_DATA) Bohemia-400-Italic.otf '$(DESTDIR)$(fontsdir)/Bohemia 400 Italic.otf'
	$(INSTALL_DATA) BohemiaText-400.otf '$(DESTDIR)$(fontsdir)/Bohemia Text 400.otf'
	$(INSTALL_DATA) BohemiaText-400-Italic.otf '$(DESTDIR)$(fontsdir)/Bohemia Text 400 Italic.otf'
