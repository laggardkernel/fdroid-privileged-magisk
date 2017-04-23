# F-Droid Privileged Extension (Magisk)

![F-Droid logo](https://f-droid.org/repo/icons/org.fdroid.fdroid.privileged.2000.png)

Help F-Droid acquire system privileges

**Note:** F-Droid will need root privileges to install this app as a system app.

[F-Droid](https://f-droid.org/repository/browse/?fdid=org.fdroid.fdroid) can make use of system privileges or permissions to install, update and remove applications on its own. The only way to obtain those privileges is to become a system app.

This is where the Privileged Extension comes in - being a separate app and much smaller, it can be installed as a system app and communicate with the main app via AIDL IPC.

This has several advantages:

- Reduced disk usage in the system partition
- System updates don't remove F-Droid
- The process of installing into system via root is safer
- Instead of this build, most users will want to install the "Over-The-Air" (OTA) update zip file is called F-Droid Privileged Extension.

License: Apache-2.0

**Website:** [https://f-droid.org](https://f-droid.org)

**Issue Tracker:** [https://gitlab.com/fdroid/privileged-extension/issues](https://gitlab.com/fdroid/privileged-extension/issues)

**Source Code:** [https://gitlab.com/fdroid/privileged-extension](https://gitlab.com/fdroid/privileged-extension)

**Donate:** [https://f-droid.org/about](https://f-droid.org/about)

**Flattr:** [![flattr badge](https://f-droid.org/wp-content/uploads/flattr-badge-large.png)](https://flattr.com/thing/343053)

For full details and additional technical information, see [this application's page](https://f-droid.org/wiki/page/org.fdroid.fdroid.privileged) on the F-Droid wiki.

### Packages

[![Download F-Droid button](https://f-droid.org/wp-content/uploads/2010/10/button.png)](https://f-droid.org/FDroid.apk)

Although APK downloads are available below to give you the choice, you should be aware that by installing that way you will not receive update notifications, and it's a less secure way to download. We recommend that you install the F-Droid client and use that.

### Changelog
[Changelog on Gitlab](https://gitlab.com/fdroid/fdroiddata/raw/master/metadata/org.fdroid.fdroid.privileged.txt)

### Credit
- [F-Droid Privileged Extension](https://f-droid.org/repository/browse/?fdid=org.fdroid.fdroid.privileged) by [F-Droid](https://f-droid.org/)
- [Magisk v9 - The Universal Systemless Interface \[Android 5.0+\]](http://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445) by [topjohnwu@XDA](http://forum.xda-developers.com/member.php?u=4470081)
- [The Magisk module](https://github.com/laggardkernel/fdroid-privileged-magisk) by [laggardkernel @Github](https://github.com/laggardkernel)

