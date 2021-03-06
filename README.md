<p align="center">
<img src="https://github.com/AospExtended/manifest/raw/7.1.1/aex_logo.png" width="320px" height="320px" > 
</p>

cortex.id
===========


Credits
-------
* [**AospExtended**](https://github.com/AospExtended)
* [**JDCTeam (Base)**](https://github.com/AOSP-JF-MM)
* [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
* [**AOSiP**](https://github.com/AOSIP)
* [**ZephyrOS**](https://github.com/Zephyr-OS)
* [**TurboROM**](https://github.com/TurboROM)
* [**TeamSubstratum (Theme Engine)**](https://github.com/Substratum)
* [**SlimRoms**](https://github.com/SlimRoms)
* [**BlissRoms**](https://github.com/BlissRoms)
* [**LineageOS/Cyanogenmod**](https://github.com/LineageOS)
* [**Nitrogen Project**](https://github.com/nitrogen-project)
* [**Pure Nexus**](https://github.com/PureNexusProject)
* [**GZR Community**](https://plus.google.com/communities/109330559573276360638)
* [**OmniROM**](https://github.com/omnirom/)
* [**AOSPA**](https://github.com/aospa/)
* [**ABC ROM**](https://github.com/ezio84)

How to Build?
-------------

To initialize your local repository using the AospExtended trees, use a 
command like this:

```bash
  repo init -u git://github.com/AospExtended/manifest.git -b 7.x
```
  
Then to sync up:
----------------

```bash
  repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch aosp_device_codename-userdebug
  mka aex -jx
```
