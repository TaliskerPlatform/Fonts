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
	CabinSketch-Bold.ttf CabinSketch-Regular.ttf

fontsdir = $(prefix)/Library/Fonts

install-data-hook:
	$(MKDIR_P) '$(DESTDIR)$(fontsdir)'
	$(INSTALL_DATA) CabinSketch-Bold.ttf '$(DESTDIR)$(fontsdir)/Cabin Sketch Bold.ttf'
	$(INSTALL_DATA) CabinSketch-Regular.ttf '$(DESTDIR)$(fontsdir)/Cabin Sketch Regular.ttf'
