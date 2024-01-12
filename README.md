# Key Objects Library

The Key Objects Library a.k.a. KOL is a framework for Delphi and FreePascal that replace the RTL VCL or LCL.
This fork is made available by Thaddy de Koning, historically (since 2001) one of the core contributors and is
pending permission by Vladimir Kladov to make it the official repository in the near future.
This new version is updated from version 3.2.3 to  support windows 10 and 11. The version of this repository is 3.9.9 as per 12 Januari 2024
KOL is Freeware and comes with very permissive licensing, basically non for the KOL core, but some widgets may have a more restrictive license,
usually GPL2 or MPL, so make sure you adhere to a license if a widget is licensed.
KOL development has stalled for a few years, but from here you can consider it maintained again.

KOL creates very small applications: 
- A rudimentary Delphi GUI example is about 14 kilobyte with system replacement, about 25 Kilobytes without system replacement
- A rudimentary FreePascal GUI application renders about 50-60 Kilobytes
- That means a KOL application is 10-20 times smaller than its LCL or VCL equivalents.
- While size may not matter too much nowadays, the resulting very fast start-up times by KOL applications are definitely an advantage.
- KOL enables you to write UNICODE16 apps in older non-unicode Delphi versions 4-2007
- KOL widgets are all already fully UNICODE16 capable, also on FreePascal/Lazarus 

The library was written by Vladimir Kladov with contributions from others.
Its main targets are Windows 32 bit, Windows 64 bit and WinCE. Windows is supported up to and including Windows 11.
There is very limited support for Linux GTK. This should be consired experimental and incomplete.
FreePascal is supported from version 3.0.4, older versions from the 2.6 series may also work but is not in test scope
Delphi is supported from version 3, with limited supprt for Delphi 2. New delphi versions than Delphi 2009 might also work
but are currently not in test scope
LCL versions and VCL versions are only applicable to the auxilliary Mirror Classes Kit, a.k.a. MCK that is an add-on 
to be able to use KOL through the visual designers from Lazarus and Delphi.
Spupport is historically always possible through the FreePascal forums. There is also an entry in the FreePascal wiki,
but that is currently a bit out dated and pending updates by me in the near future.

<!---
thaddydekoning/thaddydekoning is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
