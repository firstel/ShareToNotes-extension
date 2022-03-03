# ShareToNotes-extension

Thank you for installing ShareToNotes Extension!
ShareToNotes works with mshare.
Please follow the steps below to enable the extension.

## Homebrew

```
# Install mshare
brew tap mosugi/homebrew-formulae && brew install mshare
# Install mshare chrome extension native manifest
git clone https://github.com/mosugi/ShareToNotes-extension.git && ./ShareToNotes-extension/host/install_host.sh
```

## Manually

```
#fix xcode
sudo xcode-select -s /Applications/Xcode.app/Contents/Developer
# Install mshare
git clone https://github.com/mosugi/mshare.git && cd mshare && make install
# Install mshare chrome extension native manifest
git clone https://github.com/mosugi/ShareToNotes-extension.git && ./ShareToNotes-extension/host/install_host.sh
```
