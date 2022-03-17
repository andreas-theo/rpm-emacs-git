# Emacs-pgtk-git
This is a fork of Wojtek242-RPM's Emacs RPM build. It tracks Emacs' development
branch and builds Emacs with the pgtk flag.


# Building an RPM from git sources

Instructions based on this [blog
post](https://hobo.house/2017/09/03/automate-rpm-builds-from-git-sources-using-copr/)

# Testing build locally

```
sudo dnf builddep emacs.spec
spectool -g -R emacs.spec
rpmbuild -ba emacs.spec
```
