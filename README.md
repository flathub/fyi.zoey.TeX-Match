# TeX Match

___Find LaTeX symbols by sketching___

If you work with LaTeX, you know its difficult to memorize the names of all the symbols. TeX Match allows you to search through over 1000 different LaTeX symbols by sketching.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub fyi.zoey.TeX-Match
flatpak run fyi.zoey.TeX-Match
```

## Building

```
git clone git@github.com:flathub/fyi.zoey.TeX-Match.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install fyi.zoey.TeX-Match.json
```

---

**Technologies**: GNOME, GTK3, Rust
