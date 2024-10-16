# Hawk tuProlog

A friendly Flatpak wrapper for [2p-kt] IDE.

[2p-kt]: https://github.com/tuProlog/2p-kt

## Install

1. Install `flatpak-builder` (and obviously `flatpak`) from your favorite package manager.
2. Clone this repository:

   ```bash
   git clone https://github.com/VaiTon/hawkTuProlog.flatpak.git
   cd hawkTuProlog.flatpak
   ```

3. Build and install the Flatpak bundle:

   ```bash
   flatpak-builder build it.unibo.tuprolog.ide.yml --user --force-clean --install
   ```

4. A new application named `TuProlog IDE` should be available in your application menu.
5. Enjoy logic programming!
