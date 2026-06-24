# deltahost-releases

Release manifest (`update.json`) and installer assets for **DeltaHost**.
The in-plugin updater fetches `update.json` from the `main` branch and, if a
newer version is listed, downloads the matching per-platform ZIP from the
release assets and installs it silently.
