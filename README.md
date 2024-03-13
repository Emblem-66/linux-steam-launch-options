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

options: ``WINEDLLOVERRIDES="d3dx9,d3dx9_43,d3dcompiler_43" %command%``

protontricks: ``d3dx9 d3dx9_43 d3dcompiler_43``

options: ``gamemoderun %command%``

### Tom Clancy's Splinter Cell

id: ``13560``

proton: ``experimental``

options: ``WINEDLLOVERRIDES="D3D8,dinput8,msacm32,msvfw32=n,b" %command%``


### Tom Clancy's Splinter Cell Conviction

**PERFORMANCE IS SHIT**

id: ``33220``

proton: ``experimental``

options: ``WINEDLLOVERRIDES=systemdetection=d WINE_CPU_TOPOLOGY="4:0,1,2,3" gamemoderun %command%``
