# Nearest-Neighbour Wrappers
 
A collection of [graphic API wrappers](https://emulation.gametechwiki.com/index.php/Wrappers) with overrided texture filtering methods for Windows. Now every upscaled texture renders with point filter (Nearest-Neighbour sampling).

### Screenshots:

### Usage:
Put appropriate dll files to game's executable directory
- ddraw.dll - for DirectX 1-7 apps (x86 only)
- d3d8.dll - for DirectX 8 apps (x86 only)
- d3d9.dll - for DirectX 9 apps (x86 only)
- d3d10.dll - for DirectX 10 apps (*in progress*)
- d3d10_1.dll - for DirectX 10.1 apps (*in progress*)
- d3d11.dll - for DirectX 11 apps (*in progress*)
- opengl32.dll - for OpenGL apps (x86 only)  

**Warning! Do not use any wrappers with online anti-cheat protected games to prevent ban!**

### Notes:
**d3d8to9** based dll (d3d8.dll) converts DirectX 8 API calls to DirectX 9, see more details in [d3d8to9 repo](https://github.com/crosire/d3d8to9).  
**dxvk** based dlls (d3d10.dll - d3d11.dll) is Vulkan-based implementation of DirectX for Linux/Wine. In often cases it works with Windows, but [officially it's not supported](https://github.com/doitsujin/dxvk/issues/1801).

### Used repositories:
- [SeanPesce/d3d11-wrapper](https://github.com/SeanPesce/d3d11-wrapper)
- [Joshua-Ashton/dxup](https://github.com/Joshua-Ashton/dxup)
- [ThirteenAG/d3d9-wrapper](https://github.com/ThirteenAG/d3d9-wrapper)
- [ThirteenAG/d3d8-wrapper](https://github.com/ThirteenAG/d3d8-wrapper)
- [elishacloud/DirectX-Wrappers](https://github.com/elishacloud/DirectX-Wrappers)
- [crystice-softworks/QeffectsGL](https://github.com/crystice-softworks/QeffectsGL)
- [crosire/d3d8to9](https://github.com/crosire/d3d8to9)  
**Thank you all for your hard work!**
