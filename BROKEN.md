system-settings-git:
==> WARNING: Package contains reference to $srcdir
usr/lib/ubuntu-system-settings/private/Ubuntu/SystemSettings/Bluetooth/libUbuntuBluetoothPanel.so

settings-components-git:
/usr/lib/qt5/qml/Ubuntu/Settings -> /usr/lib/qt/qml/Ubuntu/Settings

qmenumodel:
/usr/lib/qt5/qml/QMenuModel -> /usr/lib/qt/qml/QMenuModel

qtmir:
/usr/lib/qt5/plugins/platforms/libqpa-mirserver.so -> /usr/lib/qt/plugins/platforms

indicator-network-git:
/usr/lib/qt5/qml/Ubuntu/Connectivity -> /usr/lib/qt/qml/Ubuntu/Connectivity

ubuntu-download-manager:
/usr/lib/qt5/qml/Ubuntu/DownloadManager -> /usr/lib/qt/qml/Ubuntu/DownloadManager

content-hub:
/usr/lib/qt5/qml/Ubuntu/Content -> /usr/lib/qt/qml/Ubuntu/Content

unity8:
missing deps: qtmir-git
missing /usr/share/backgrounds/warty-final-ubuntu.png (should be /usr/share/wallpapers?) (https://t.me/ubports/136672)
references build path:  <Unknown File>:46:33: QML CroppedImageMinimumSourceSize: Cannot open: file:///mnt/antihype/Projects/AUR/tests/graphics/applicationIcons/dash.png
GLib-GIO-ERROR **: Settings schema 'com.canonical.Unity.Launcher' is not installed (comes from https://launchpad.net/ubuntu/xenial/+source/unity)
[2018-06-25:00:34:32.761] Failed to get all properties for "com.ubuntu.AccountsService.Input" : "No such interface 'com.ubuntu.AccountsService.Input'"
[2018-06-25:00:34:32.762] Failed to get all properties for "com.ubuntu.AccountsService.SecurityPrivacy" : "No such interface 'com.ubuntu.AccountsService.SecurityPrivacy'"
[2018-06-25:00:34:32.762] Failed to get all properties for "com.ubuntu.location.providers.here.AccountsService" : "No such interface 'com.ubuntu.location.providers.here.AccountsService'"
[2018-06-25:00:34:32.762] Failed to get all properties for "com.ubuntu.touch.AccountsService.SecurityPrivacy" : "No such interface 'com.ubuntu.touch.AccountsService.SecurityPrivacy'"
[2018-06-25:01:27:18.997] ubuntu-app-launch threw an exception getting app info for appId: "dialer-app" : Invalid app ID: dialer-app
[2018-06-25:01:27:18.997] ubuntu-app-launch threw an exception getting app info for appId: "messaging-app" : Invalid app ID: messaging-app
[2018-06-25:01:27:18.997] ubuntu-app-launch threw an exception getting app info for appId: "address-book-app" : Invalid app ID: address-book-app
GLib-GIO-ERROR **: Settings schema 'com.ubuntu.touch.system' is not installed (missing dep gsettings-ubuntu-touch-schemas-git)
GLib-GIO-ERROR **: Settings schema 'com.canonical.keyboard.maliit' is not installed (missing dep keyboard-component-git, https://github.com/ubports/keyboard-component/blob/master/data/schemas/com.canonical.keyboard.maliit.gschema.xml)
[2018-07-14:02:35:59.175] Cannot find any language packs, bailing out
--
Ivan Semkin 🇧🇾, [14.07.18 02:39]
can i skip the greeter somehow?
Marius Gripsgard, [14.07.18 02:41]
mkdir -p $HOME/.config/ubuntu-system-settings
    touch $HOME/.config/ubuntu-system-settings/wizard-has-run
Marius Gripsgard, [14.07.18 02:46]
@vanyasem but the desktop does not use the wizard anyway, so i think it should be safe to ignore for now
--
 MIR_SERVER_CURSOR=null QT_QPA_PLATFORM=mirserver unity8

system-settings:
missing deps: indicator-datetime (unpackaged)
module "Biometryd" is not installed (unpackaged)
Settings schema 'com.ubuntu.notifications.settings.applications' is not installed
Settings schema 'com.canonical.keyboard.maliit' is not installed

missing dep:
gsettings-qt-git

/usr/include/gtest/CMakeLists.txt exists in both 'libertine-git' and 'platform-api-git'

maliit-framework:
/usr/share/qt5/mkspecs/features/maliit-defines.prf -> /usr/share/qt/mkspecs/features/maliit-defines.prf

keyboard-component:
?? patch /usr/share/qt/mkspecs/features/maliit-defines.prf -> /usr/lib/qt/mkspecs/features/maliit-defines.prf