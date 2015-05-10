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

dist_noinst_DATA = TaliskerTerminal-500.sfd TaliskerTerminal-500.otf

fontsdir = $(prefix)/Library/Fonts

# make has problems with filenames containing spaces, so we install using
# a hook instead.

install-data-hook:
	$(MKDIR_P) '$(DESTDIR)$(fontsdir)'
	$(INSTALL_DATA) '$(srcdir)/TaliskerTerminal-500.otf' '$(DESTDIR)$(fontsdir)/Talisker Terminal 500.otf'
