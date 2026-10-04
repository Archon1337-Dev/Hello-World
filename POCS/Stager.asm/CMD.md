```
ml64 /c /nologo /Fo stager.obj stager.asm
link /nologo /SUBSYSTEM:WINDOWS /ENTRY:mainCRTStartup ^
     /OUT:stager.exe stager.obj ^
     urlmon.lib ole32.lib kernel32.lib user32.lib
```
