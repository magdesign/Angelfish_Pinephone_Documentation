Installation
============

Manjaro:

::

    sudo pacman -S angelfish

or open the Discover app and install it from there.

Mobian:

::

    sudo apt install git build-essential cmake extra-cmake-modules kirigami2-dev libkf5config-dev libkf5coreaddons-dev libkf5dbusaddons-dev libkf5i18n-dev libkf5purpose-dev libkf5windowsystem-dev libqt5sql5-sqlite libqt5svg5-dev qtbase5-dev qtquickcontrols2-5-dev qtwebengine5-dev
    sudo apt install qml-module-org-kde-purpose qml-module-qtwebengine
    git clone https://invent.kde.org/plasma-mobile/plasma-angelfish
    mkdir -p plasma-angelfish/build
    cd plasma-angelfish/build
    cmake -S .. -B .
    make -j4
    sudo make install


Postmarket/Alpine based:

::

    sudo apk add plasma-angelfish

The PostmarketOS build of Angelfish has no AdBlock functionality.

Uninstall
=========


Manjaro:

::

    sudo pacman -R angelfish



    