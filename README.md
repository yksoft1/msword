msword
======

MS Word for Windows 1.1 source code
http://blogs.technet.com/b/microsoft_blog/archive/2014/03/25/microsoft-makes-source-code-for-ms-dos-and-word-for-windows-available-to-public.aspx

Microsoft released the code to Word 1.1 to the public via an open source license.

For edcuational purposes only.


http://blastar.in/

# Build instructions for DOS
1. You must have a DOS environment, real PC or emulated, with more than 600KB of available conventional memory and more than 1MB of expanded memory (EMS).
2. You must set PATH to include Opus\tools and Opus\tools\dos.
3. You must set TEMP to a writable directory.
4. CD to Opus\, run 
	makeopus @tools\fast2.ini
	
	If it fails, try run mo1.bat in BUILD directory (set in INI file passed to makeopus).
5. In Dosbox, it may fail to generate the last line of verdate.h in BUILD directory. You must manually #define szVerDateDef for a string.

	

