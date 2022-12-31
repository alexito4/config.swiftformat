# config.swiftformat

This is the [swiftformat](https://github.com/nicklockwood/SwiftFormat) I use in my personal projects.

## Version

Updated for version: `0.50.7`.

## How to update

- Configured using the [UI app](https://github.com/nicklockwood/SwiftFormat#xcode-source-editor-extension).
- Comparing it with the defaults by running `swiftformat --rules` to have a deecnt baseline.
- Review each rule in [Rules.md](https://github.com/nicklockwood/SwiftFormat/blob/master/Rules.md).

## How I run it

I have `swiftformat` installed globally via Homebrew so I can use it in any quick project without any setup.

```sh
swiftformat . --config ../format/config.swiftformat
```

## Author

Alejandro Martinez | https://alejandromp.com | [@alexito4](https://mastodon.social/@alexito4)