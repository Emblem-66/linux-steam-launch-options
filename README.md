# Steam Launch Options

protontricks example:
flatpak run com.github.Matoking.protontricks 35140 d3dx9

**launch options & extra dependencies**

### Universal

proton: ``experimental``

options: ``gamemoderun %command%``

### Arkham Asylum

flatpak run com.github.Matoking.protontricks 35140 d3dx9 d3dx9_43 d3dcompiler_43

id: ``35140``

proton: ``GE``

protontricks: ``d3dx9 d3dx9_43 d3dcompiler_43``

options: ``gamemoderun %command%``

### Tom Clancy's Splinter Cell Conviction

**no audio device found, gpu unsupported**
[image](image.png)

go to game folder and delete ``systemdetection.dll`` or set launch option ``WINEDLLOVERRIDES=systemdetection=d``

id: ``33220``

proton: `` ``

protontricks: `` ``

options: ``gamemoderun %command%``
