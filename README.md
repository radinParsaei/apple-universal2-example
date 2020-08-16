# apple-universal2-example
## based on https://developer.apple.com/documentation/xcode/building_a_universal_macos_binary

### setup:
download xcode12 from https://developer.apple.com/download/ (apple-id is needed)

then extract downloaded .xip file and copy xcode-beta.app to `/Applications`

then use `sudo xcode-select -s /Applications/Xcode-beta.app`

now you have all dependencies!

use `make` to build a hello world universal binary
and `make clean` to clean generated apps
