# WARNING: hxCodec is mostly deprecated, don't use hxCodec and instead use [hxvlc](https://github.com/MAJigsaw77/hxvlc)

# Nothin' Engine - hxCodec

The hxCodec fork that powers Nothin' Engine on FNF.

## Instructions

1. Install the latest stable version of `hxCodec` by running the following haxelib command.
   
    ```bash
    haxelib git hxCodec https://github.com/syncgit12/hxCodec
    ```

3. Add this code in the ***project.xml*** file.
    ```xml
    <haxelib name="hxCodec" if="desktop || mobile" />
    ```

    **OPTIONAL: Some defines you can add to your project**
    ```xml
    <!-- LibVLC Logging for hxCodec -->
    <haxedef name="HXC_LIBVLC_LOGGING" if="debug" />
    ```

## Linux Specific Instructions

In order to build a application with the library on ***Linux***, you **have to install** `libvlc` and `libvlccore` from your distro's package manager.

### Debian based distributions:
```bash
sudo apt-get install libvlc-dev libvlccore-dev 
```

### Arch based distributions:
```bash
sudo pacman -S vlc 
```

## Usage Example

Check out the [Samples Folder](samples/) for examples on how to use this library.

## Licensing
**hxCodec** is made available under the **Mozilla Public License 2.0\***. Check [LICENSE](./LICENSE) for more information.

\*Haxelib does not support MPL2.0; therefore, regardless of what Haxelib reports, this library's license is still **MPL2.0**.

![](https://raw.githubusercontent.com/videolan/vlc/master/share/icons/256x256/vlc.png)

[***libVLC***](https://www.videolan.org/vlc/libvlc.html) is the engine of **VLC** released under the **LGPLv2 License** (or later). Check [VideoLAN.org](https://www.videolan.org/legal.html) for more information.

## Credits

| Avatar | UserName | Involvement |
| ------ | -------- | ----------- |
| ![](https://avatars.githubusercontent.com/u/47796739?s=64) | [polybiusproxy](https://github.com/polybiusproxy) | Creator of **hxCodec**
| ![](https://avatars.githubusercontent.com/u/1677550?s=64) | [datee](https://github.com/datee) | Creator of **HaxeVLC**
| ![](https://avatars.githubusercontent.com/u/77043862?s=64) | [MAJigsaw77](https://github.com/MAJigsaw77) | Programmer, Android & Linux support
| ![](https://avatars.githubusercontent.com/u/4635334?s=64) | [EliteMasterEric](https://github.com/EliteMasterEric) | Additional Programmer
| ![](https://avatars.githubusercontent.com/u/84131849?s=64) | [RapperGF](https://github.com/RapperGF) | Rendering Overhaul & Testing
| ![](https://avatars.githubusercontent.com/u/49110074?s=64) | [swordcube](https://github.com/swordcube) | Testing Linux support
| ![](https://avatars.githubusercontent.com/u/107599365?v=64) | [Jonnycat](https://github.com/JonnycatMeow) | macOS support
| ![](https://avatars.githubusercontent.com/u/103241885?s=64) | [FutureDorito](https://github.com/Futuredorito) | iOS support
| ![](https://avatars.githubusercontent.com/u/82843871?s=64) | [mcagabe19](https://github.com/mcagabe19) | iOS support

| Avatar | UserName | Involvement |
| ------ | -------- | ----------- |
| ![](https://avatars.githubusercontent.com/u/144155299?s=64) | [Lunar](https://github.com/SyncGit12) | hxCodec 2.5.1 compatibility
