# kernelSymbolFinder
Get kernel symbols on device. No jailbreak required (note: unslid addresses)

# Setup

- Include the files, call initWithKernelCache() with a copy of the compressed kernelcache **that is stored on a location you have permission to write**
- Call find_symbol() as you wish
- You'll be left with a .dec file on the same location which you might want to delete later

------------------

Thanks to Willem Hengeveld for lzssdec and MachOView as an awesome tool!
