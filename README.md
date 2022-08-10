# Virgil Font

[`fifthtry.github.io/virgil-font`](https://fifthtry.github.io/virgil-font) is a wrapper over [Virgil font](https://github.com/excalidraw/virgil).

# How To Use This Font

include `fifthtry.github.io/virgil-font` package into FPM.ftd file

```ftd
-- fpm.dependency: fifthtry.github.io/virgil-font

-- fpm.auto-import: fifthtry.github.io/virgil-font
```

Inside your .ftd file to change for any specific token use:

```
-- fpm.type.headline-small.font: $virgil-font.fonts.virgil-font

-- ftd.text:
role: $fpm.type.headline-small
```

[How to Use fonts](https://fpm.dev/how-to/how-to-use-fonts/).

# License

[Inter is distributed under SIL Open Font License 1.1](https://github.com/excalidraw/virgil/blob/main/LICENSE.md). We use the same license to be compatible with them.
