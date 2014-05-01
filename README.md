# TietoMultiWindow for Android 4.2.2
TietoMultiWindow is a modification of Android Framework which enables to launch and see multiple applications at the same time. It is created by [Tieto](http://www.tieto.com), inspired by [Cornerstone] (https://github.com/Onskreen/cornerstone). 
For KitKat (4.4) version please visit [Multiwindow Jabol](https://github.com/tieto/multiwindow_for_android) page.

## Features
Here is a short demo of TietoMultiWindow : http://www.youtube.com/watch?v=cwvxWIt30lU

* Run multiple apps on android
* Arrange windows in tabs (similar to workspaces in Ubuntu)
* Two modes: floating and docked
	* Floating mode allows window move and resize
	* Docked mode allows to pin windows to left or right side
* Transparent for applications

## For Developers
Please be aware installing TietoMultiWindow requires to build the whole Android platform and flash it to a device. Tieto does not take any responsibility for results of flashing your device.
TietoMultiWindow consists of two parts: framework modification and client application for managing windows. Flexible API allows to create more sophisticated window managers. To download TietoMultiwindow execute:

    repo init -u https://github.com/tieto/multiwindow_for_android_platform_manifest.git -b tieto_multiwindow
    repo sync -j8

For more information about building Android please see https://source.android.com/source/building.html.

## Credits
Thanks to Tieto development team members:
* Pawel Augustyn
* Radoslaw Bieniek
* Szymon Bigos
* Sebastian Gozdz
* Dariusz Kluska
* Andrzej Listowiecki
* Mateusz Madetko
* Michal Stawinski
* Adrian Szymanski
* Dominik Sliwa 
* Stefan  Wysocki

## Licence
Projects:
* https://github.com/tieto/multiwindow_for_android_platform_manifest
* https://github.com/tieto/multiwindow_platform_frameworks_base
* https://github.com/tieto/multiwindow_platform_packages_apps_Launcher2
* https://github.com/tieto/multiwindow_platform_packages_apps_settings
* https://github.com/tieto/multiwindow_platform_packages_apps_TietoLauncher

are released under [Apache 2.0 Licence] (http://www.apache.org/licenses/LICENSE-2.0.html).

TietoMultiwindow application (http://github.com/tieto/multiwindow_packages_apps_TietoMultiWindow) is released under [GPLv3 Licence] (https://www.gnu.org/licenses/gpl-3.0-standalone.html).</br>

## About Tieto
Tieto’s Product Development Services is the unique telecom expert with global presence. For 30 years we have been in the forefront of mobile and telecom technology. When you think of all the mobile calls in the world – more than half of them are possible because of us! It is Tieto – the product development services – that keeps the telecom technology in motion.
