Windows XP manifest resource file

This file contains a special resource, which is an XML snippet to enable
themes support for an application or library under Windows XP. In order
to enable theming not only for applications but also control panel applets,
etc. the manifest is stored twice, each one under special resource IDs. 
For common applications the ID 1 (CREATEPROCESS_MANIFEST_RESOURCE_ID) 
is used while for control panel applets it is 123 (CONTROL_PANEL_RESOURCE_ID).

You may use this file in any way you like. There is no license attached nor
are you required to tell my name (although credits are always welcome).

In order to use this file simply include the line:

{$R WinXP.res}

in a Delphi file of your project. Which one does not matter, as long as it is
indeed compiled and linked to your application.

Find more Windows XP theme support related stuff on my homepage.

Enjoy, 

Mike Lischke (public@delphi-gems.com)
--
www.delphi-gems.com
www.lischke-online.de
www.delphi-unicode.net