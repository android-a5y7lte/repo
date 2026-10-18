# Sailfish OS package repository for the Samsung Galaxy A5 2017 (a5y17lte)

Served with GitHub Pages at https://android-a5y7lte.github.io/repo/

| Path | Contents |
|---|---|
| `5.1.0.11/a5y17lte/` | Device adaptation for Sailfish OS 5.1.0.11 (droid-hal, droid-config, libhybris, middleware), Android App Support (`a5y17lte-android-support`) and the Waydroid packages it needs |

Images from [android-a5y7lte/exynos7880-ci](https://github.com/android-a5y7lte/exynos7880-ci)
already have this repository. On an older install add it with:

    devel-su ssu ar a5y17lte https://android-a5y7lte.github.io/repo/5.1.0.11/a5y17lte/
    devel-su pkcon refresh

Android App Support: `devel-su pkcon install a5y17lte-android-support`, then open
**Android** from the app grid and tap **Install Android**.

The Waydroid, waydroid-runner, waydroid-sensors, python3-gbinder and dnsmasq packages
are unmodified builds from [SailfishOS:Chum](https://build.sailfishos.org/project/show/sailfishos:chum)
(sources there). Packages are unsigned, as usual for community adaptations.
