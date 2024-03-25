# Material Files Plus

[![Android CI status](https://github.com/Galacticai/MaterialFilesPlus/workflows/Android%20CI/badge.svg)](https://github.com/Galacticai/MaterialFilesPlus/actions) 
[![GitHub release](https://img.shields.io/github/v/release/Galacticai/MaterialFilesPlus)](https://github.com/Galacticai/MaterialFilesPlus/releases) 
[![License](https://img.shields.io/github/license/Galacticai/MaterialFilesPlus?color=blue)](LICENSE)

An open source Material Design file manager, for Android 5.0+. 
+ **Plus** support for seamless browsing of other devices.

## Preview

<p>
    <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/1.png" width="32%" />
    <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/2.png" width="32%" />
    <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/3.png" width="32%" />
    <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/4.png" width="32%" />
    <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/5.png" width="32%" />
    <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/6.png" width="32%" />
</p>

## Features

- Open source: Lightweight, clean and secure.
- Material Design: Follows Material Design guidelines, with attention into details.
- Breadcrumbs: Navigate in the filesystem with ease.
- Root support: View and manage files with root access.
- Archive support: View, extract and create common compressed files.
- NAS support: View and manage files on FTP, SFTP, SMB and WebDAV servers.
- Themes: Customizable UI colors, plus night mode with optional true black.
- Linux-aware: Like [Nautilus](https://wiki.gnome.org/action/show/Apps/Files), knows symbolic links, file permissions and SELinux context.
- Robust: Uses Linux system calls under the hood, not yet another [`ls` parser](https://news.ycombinator.com/item?id=7994720).
- Well-implemented: Built upon the right things, including [Java NIO2 File API](https://docs.oracle.com/javase/8/docs/api/java/nio/file/package-summary.html) and [LiveData](https://developer.android.com/topic/libraries/architecture/livedata).

## Inclusion in custom ROMs

Thank you if you choose to include Material Files in your custom ROM! However since several user complaints were received due to improper inclusion, please check the following suggestions on including this app properly for the good of end users:

- Please don't replace the AOSP [DocumentsUI](https://android.googlesource.com/platform/packages/apps/DocumentsUI/) app with this app. This app is not designed to replace DocumentsUI and can't handle a number of functionalities in DocumentsUI - in fact, it relies on DocumentsUI to do things like granting external SD card access.

- Please make sure this app can be uninstalled or at least disabled. Some users may not want this app for a variety of reasons, and get very upset when they can't remove it.

- Please avoid conflict with the Play/F-Droid version of this app. App stores cannot update apps signed with a different certificate, so you can either ship an APK that's signed by me (or F-Droid) so that users will be able to update it on Play/F-Droid, or fork this project and rename the package name when you need to sign the APK with a different certificate and potentially making other changes.

## License for [MaterialFilesPlus](https://github.com/Galacticai/MaterialFilesPlus)

    Copyright (C) 2024 Galacticai
    
    Anything made by this developer in MaterialFilesPlus is under GPL 3.0 license.
    The rest of the components are under their respective licenses.

## License for [MaterialFiles](https://github.com/zhanghai/MaterialFiles)

    Copyright (C) 2018 Hai Zhang

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
